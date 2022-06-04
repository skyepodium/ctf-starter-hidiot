# 비즈네르 암호

[블로그 설명](https://velog.io/@skyepodium/Vigenere-Cipher-%EB%B9%84%EC%A6%88%EB%84%A4%EB%A5%B4-%EC%95%94%ED%98%B8-%EA%B5%AC%ED%98%84)

# 1. 개요
비즈네르 암호는 다음 표를 가지고, 암호화 하는 방법입니다. 

[cyber chef](https://gchq.github.io/CyberChef/#recipe=Vigen%C3%A8re_Decode('blorpy')&input=Z3dveHtSZ3Fzc2loWXNwT250cXB4c30)를 사용하기만 하다가 한번 직접 만들어보려구

# 2. 코드
```python
class vigenere:
    def __init__(self):
        self.__make_table()

    def __make_table(self):
        self.t = []
        for i in range(26):
            self.t.append([c if c < 26 else c - 26 for c in range(i, i+26)])

    def __get_base_by_is_upper(self, c):
        return ord('A') if c.isupper() else ord('a')

    def encode(self, s:str, key:str):
        # 1. init
        res = ""
        key_idx = 0

        # 2. loop
        for c in s:
            if not c.isalpha():
                res += c
            else:
                k = key[key_idx]
                key_idx += 1
                if key_idx >= len(key): key_idx = 0

                c_base = self.__get_base_by_is_upper(c)
                k_base = self.__get_base_by_is_upper(k)
                col_idx = ord(c) - c_base
                row_idx = ord(k) - k_base

                res += chr(self.t[row_idx][col_idx] + c_base)

        return res

    def decode(self, s:str, key:str):
        # 1. init
        res = ""
        key_idx = 0

        for c in s:
            if not c.isalpha():
                res += c
            else:
                k = key[key_idx]
                key_idx += 1
                if key_idx >= len(key): key_idx = 0

                c_base = self.__get_base_by_is_upper(c)
                k_base = self.__get_base_by_is_upper(k)
                row_idx = ord(k) - k_base
                col_idx = 0
                for c_idx, val in enumerate(self.t[row_idx]):
                    if chr(val + c_base) == c:
                        col_idx = c_idx
                        break

                res += chr(col_idx + c_base)

        return res


r = [
    {
        "plain_text":"flag{CiphersAreAwesome}",
        "cyper_text":"gwox{RgqssihYspOntqpxs}",
        "key":"blorpy"
    },
    {
        "plain_text": "divert troops to east ridge",
        "cyper_text": "vstwbr lbmgzq ly cscr jsbyo",
        "key": "sky"
    }
]

for c in r:
    v = vigenere()

    plain_text, cyper_text, key = c["plain_text"], c["cyper_text"], c["key"]
    encrypted = v.encode(plain_text, key)

    print("===================================")
    print("encrypted", encrypted)
    print("is_same", encrypted == cyper_text)

    decrypted = v.decode(cyper_text, key)
    print("decrypted", decrypted)
    print("is_same", decrypted == plain_text)
    print("===================================")
    print()
```