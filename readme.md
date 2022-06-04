# CTF starter Hidiot

CTF 에 참여할 때 자주 사용하는 내용을 정리

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
### 1) [크로스 사이트 스크립팅 - xss](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/web/xss.md)

# 4. SQL Injection
### 1) [cheet sheet](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/sqli/sheet.md)

### 2) blind sql injection
[SquareCTF 2020 - Deep Web Blog](https://velog.io/@skyepodium/SquareCTF-Writeup)

# 5. stegnography
### 1) foremost
포렌식용 툴인데, 파일 카빙용으로 사용 가능합니다. 개인적으로 제일 좋아합니다.

윈도우에서는 [WSL(Windows Subsystem for Linux)](https://docs.microsoft.com/ko-kr/windows/wsl/install) 에 설치합니다.

[[ctflearn] Binwalk](https://skyepodium.tistory.com/entry/ctflearn-Binwalk?category=1029036)

### 2) binwalk
이미지에 숨겨진 파일을 추출합니다.   
[[ctflearn] Binwalk](https://skyepodium.tistory.com/entry/ctflearn-Binwalk?category=1029036)

### 3) [zsteg](https://github.com/zed-0xff/zsteg)
이미지에 숨겨진 문자열을 찾아냅니다.

[[BCACTF 3.0] My New Friend](https://skyepodium.tistory.com/entry/BCACTF-30-My-New-Friend)

### 4) stegsolve
색, 명암을 변경하여 숨겨진 문자열을 찾습니다.

### 5) 스테그하이드 온라인
명암, 색상을 변조합니다.
https://stylesuxx.github.io/steganography/

### 6) 숨겨진 문자열 찾기  
https://futureboy.us/stegano/decinput.html
# 6. 기타
### 1) 맥 아이피 확인
```
ifconfig | grep inet
```

### 2) https 서버
만약 사이트가 https 프로토콜을 사용하고, 로컬의 서버가 http이면 전송이 불가능합니다.(https -> http 요청 불가)

따라서, https 서버가 필요하면 postbin을 사용할 수 있습니다.

[post bin](https://www.toptal.com/developers/postbin/)
