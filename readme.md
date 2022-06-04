# CTF starter Hidiot

잊어버려서 정리하려고

Hidiot은 예전에 대회 나갔을 때 팀명

# CTF
### 1) 소개
CTF는 간단히 말해서 **해킹 대회**

wargame - 자신의 페이스로 진행할 수 있는 환경

### 2) 학습 사이트
[드림핵](https://dreamhack.io/)

### 3) 대회
매주 금~일 사이에 대회가 개최되고 [CTF time](https://ctftime.org/)에서 확인할 수 있습니다.

너무 어려운 대회에 참여하면, 성취감을 얻기 힘들기 때문에 레이팅보고 참가합니다.

![cover](./images/ctftime.png)

### 4) writeup
문제를 어떻게 풀었는 기술하는 작업
, 예시: [0xL4ugh-CTF-writeup](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup)

ctf time의 경우 대회 종료 후 [write up](https://ctftime.org/event/1660/tasks/)과 같이 유저들이 올리기도 하고

구글링, 유튜브 등등 으로 검색가능합니다.


### 5) wargame
좋은 워게임 사이트
- [ctflearn](https://ctflearn.com/)
- [picoCTF](https://picoctf.org/)
- [HackCTF](https://ctf.j0n9hyun.xyz/)
- [ctf-d](http://ctf-d.com/)

### 6) 지난 대회
대부분의 대회 종료 후 서버를 닫고, 문제를 공개하지 않습니다.

일부 대회의 경우 문제와 함께 답을 공개합니다.

- [squareCTF](https://squarectf.com/)   
    square는 미국의 모바일 결제 기업입니다. 매년 CTF 대회를 개최하고, docker로 문제를 제공합니다. 정답도 포함되어 있습니다.

# TIPS
사실 이것 때문에 만듬

# 1. crypto
### 1) [암호 알고리즘 판별](https://www.dcode.fr/cipher-identifier)
어떤 알고리즘인지 감이 안잡히는 경우 대략적으로 파악할 수 있습니다.   
[설명](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/crypto/cipher-identifier.md)

### 2) [비즈네르 암호(vigenere cypher)](https://gchq.github.io/CyberChef/#recipe=Vigen%C3%A8re_Decode('blorpy')&input=Z3dveHtSZ3Fzc2loWXNwT250cXB4c30)
1. 문자열, 2. key를 기반으로 암복호화하는 알고리즘 입니다.

[설명](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/crypto/vigenere.md)

### 3) [키보드 레이아웃](https://awsm-tools.com/text/keyboard-layout)


# 3. web
### 1) [크로스 사이트 스크립팅 - xss]((https://github.com/skyepodium/ctf-starter-hidiot/blob/main/web/xss.md))

# 4. SQLI
sql injection
1) cheetsheel
```sql
admin' or 1=1 -- -

admin ' --
```

### @) 탭
SQL 구분자 공백 이외에 탭을 구분자로 사용해도 동일하게 동작합니다.

### 3) or
|| 로 변경 가능하다.

### 4) -- 
MySql에서 -- 로 주석 처리하는 경우 -- 뒤에 구분자가 와야합니다.

구분자 예시)
```
공백, 탭
--
#
/**/
```

### 5) like
like로 필터링 우회가능
```sql
SELECT *
FROM USER
WHERE ID LIKE 'ad___'
```
### 6) 문자열 사이 공백
mysql에서 문자열 사이에 공백이 있으면 문자열 합성이 발생합니다.

```sql
SELECT *
FROM USER
WHERE ID LIKE 'ad'	'min'
```

### 7) 세미콜론
원래 SQL이 실행되기 위해서는 세미콜론이 있어야하는데, PHP - mysqli_query 와 같은 함수에서 자동으로 넣어줍니다.


# 5. stegnography
- 명암, 색상 변조  
스테그하이드 온라인    
https://stylesuxx.github.io/steganography/

- 숨겨진 문자열 찾기  
https://futureboy.us/stegano/decinput.html
# 6. 기타
1) 맥 아이피 확인
```
ifconfig | grep inet
```

# 7. https 서버
만약 해당 사이트가 https 프로토콜을 사용하고, 로컬의 서버가 http이면 전송이 불가능합니다.(https -> http 요청 불가)

따라서, https 서버가 필요하면 postbin을 사용할 수 있습니다.

[post bin](https://www.toptal.com/developers/postbin/)
