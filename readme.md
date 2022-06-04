# CTF starter Hidiot

### 1) 소개
**CTF(Capture the Flag)** 는 간단히 말해서 **해킹 대회**

wargame - 자신의 페이스로 진행할 수 있는 환경

### 2) 학습 사이트
[드림핵](https://dreamhack.io/)

### 3) wargame
좋은 워게임 사이트
- [ctflearn](https://ctflearn.com/)
- [picoCTF](https://picoctf.org/)
- [HackCTF](https://ctf.j0n9hyun.xyz/)
- [ctf-d](http://ctf-d.com/)

### 4) 대회
매주 대회가 개최되며 일정은 [CTF TIME](https://ctftime.org/)에서 확인할 수 있습니다.

대회 난이도가 높으면 성취감을 얻기 힘들기 때문에 낮은 레이팅 부터 시작하거나 워게임 부터 진행합니다.

![cover](./images/ctftime.png)

### 5) writeup
문제를 어떻게 풀었는 기술하는 작업
, 예시: [0xL4ugh-CTF-writeup](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup)

ctf time의 경우 대회 종료 후 [write up](https://ctftime.org/event/1660/tasks/)과 같이 유저들이 올리기도 하고

구글링, 유튜브 등등 으로 검색가능합니다.

### 6) 지난 대회
대부분의 대회 종료 후 서버를 닫고, 문제를 공개하지 않습니다. 일부 대회의 경우 문제와 함께 답을 공개합니다.

- [squareCTF](https://squarectf.com/)   
    square는 미국의 모바일 결제 기업입니다. 매년 CTF 대회를 개최하고, docker로 문제를 제공합니다. 정답도 포함되어 있습니다.

# 1. crypto
### 1) [Cyber chef](https://gchq.github.io/CyberChef/) 🔥
다양한 암호 알고리즘의 디코딩, 인코딩을 온라인으로 지원합니다.

사용법이 간편하고, 문자열 입력값에 따라 가장 유사항 디코딩 알고리즘도 추천해줍니다.

### 2) [암호 알고리즘 판별](https://www.dcode.fr/cipher-identifier) 
어떤 알고리즘인지 감이 안잡히는 경우 대략적으로 파악할 수 있습니다.   

### 3) Base64 🔥
기본중의 기본으로 정말 여러가지로 응용해서 나옵니다.   
- [[ctflearn] Base 2 2 the 6](https://skyepodium.tistory.com/entry/ctflearn-Base-2-2-the-6?category=1029036)

### 4) [비즈네르 암호(vigenere cypher)](https://gchq.github.io/CyberChef/#recipe=Vigen%C3%A8re_Decode('blorpy')&input=Z3dveHtSZ3Fzc2loWXNwT250cXB4c30)
문자열과 key를 기반으로 암복호화하는 알고리즘 입니다.     

- [[ctflearn] Vigenere Cipher](https://skyepodium.tistory.com/entry/ctflearn-Vigenere-Cipher?category=1029036)

- [구현](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/crypto/vigenere.md)

### 5) 진법과 아스키
정말 다양한 방법들이 있습니다, cyber chef를 적극 이용합니다.

- [[ctflearn] Character Encoding](https://skyepodium.tistory.com/entry/ctflearn-Character-Encoding?category=1029036)     
- [[ctflearn] Reverse Polarity](https://skyepodium.tistory.com/entry/ctflearn-Reverse-Polarity?category=1029036)

### 6) [모스부호](https://onlineasciitools.com/convert-morse-to-ascii)
- [[cflearn] Morse Code](https://skyepodium.tistory.com/entry/cflearn-Morse-Code?category=1029036)

### 7) [키보드 레이아웃](https://awsm-tools.com/text/keyboard-layout)
키보드 배열 다르게 해서 암호 문제로 제출됩니다.    
- [[BCACTF 3.0] New Keyboard](https://skyepodium.tistory.com/entry/BCACTF-30-New-Keyboard?category=1028047)

# 3. web
### 1) [크로스 사이트 스크립팅 - xss](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/web/xss.md)
- [BYU CTF 2022 - Social Media](https://skyepodium.tistory.com/entry/BYU-CTF-2022-Social-Media-%ED%81%AC%EB%A1%9C%EC%8A%A4%EC%82%AC%EC%9D%B4%ED%8A%B8-%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8C%85?category=1028047) - 정석적인 쿠키 탈취 문제

- [[BSidesSF CTF] web-tutorial-1](https://skyepodium.tistory.com/entry/BSidesSF-CTF-web-tutorial-1?category=1028047) - 응용 문제
# 4. SQL Injection
### 1) [cheet sheet](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/sqli/sheet.md)

### 2) 기초
- [[ctflearn] Basic Injection](https://skyepodium.tistory.com/entry/ctflearn-Basic-Injection?category=1029036)

### 2) blind sql injection
- [SquareCTF 2020 - Deep Web Blog](https://velog.io/@skyepodium/SquareCTF-Writeup)

# 5. stegnography
### 1) [foremost](http://foremost.sourceforge.net/) 🔥
포렌식용 툴인데, 파일 카빙할 때 사용 가능합니다. 개인적으로 제일 좋아합니다.

윈도우에서는 [WSL(Windows Subsystem for Linux)](https://docs.microsoft.com/ko-kr/windows/wsl/install) 에 설치합니다.

- [[ctflearn] Binwalk](https://skyepodium.tistory.com/entry/ctflearn-Binwalk?category=1029036)

### 2) [binwalk](https://github.com/ReFirmLabs/binwalk)
이미지에 숨겨진 파일을 추출합니다.   
- [[ctflearn] Binwalk](https://skyepodium.tistory.com/entry/ctflearn-Binwalk?category=1029036)

### 3) [zsteg](https://github.com/zed-0xff/zsteg)
이미지에 숨겨진 문자열을 찾아냅니다.

- [[BCACTF 3.0] My New Friend](https://skyepodium.tistory.com/entry/BCACTF-30-My-New-Friend)

### 4) stegsolve
색, 명암을 변경하여 숨겨진 문자열을 찾습니다.

### 5) exiftool
파일속에 숨겨진 정보를 찾습니다.
- [[ctflearn] WOW…. So Meta](https://skyepodium.tistory.com/entry/ctflearn-WOW%E2%80%A6-So-Meta?category=1029036)

### 6) 스테그하이드 온라인
명암, 색상을 변조합니다.
https://stylesuxx.github.io/steganography/

### 7) 숨겨진 문자열 찾기  
https://futureboy.us/stegano/decinput.html

### 8) strings
바이너리 파일을 문자열을 추출하는 함수
[[ctflearn] Forensics 101](https://skyepodium.tistory.com/entry/ctflearn-Forensics-101?category=1029036)

# 6. 팁
### 1) robots.txt
robots.txt는 웹 크롤러가 해당 경로에 접근하지 말라는 의미로 domain/robots.txt에 지정합니다.

robot 어쩌구 저쩌구 나오면 힌트가 있을 확률이 높고, 그것이 아니더라도 여러 CTF 대회에서 먼저 확인하는 부분중 하나 입니다.
- [[ctflearn] Where Can My Robot Go?](https://skyepodium.tistory.com/entry/ctflearn-Where-Can-My-Robot-Go?category=1029036)

# 7. 기타
### 1) | 파이프라인
다음과 같이 쓰는 경우가 많습니다. `|` 파이프라인은 앞의 결과를 뒤 함수의 인풋으로 넣습니다.
```
cat flag.txt | grep flag{
```
### 1) grep
grep 은 특정 내용이 포함된 문자열을 필터링 하는 함수입니다.
```
cat flag.txt | grep flag{
```
### 3) 맥 아이피 확인
```
ifconfig | grep inet
```

### 4) ls -al
숨겨진 파일을 찾습니다.
[[ctflearn] Taking LS](https://skyepodium.tistory.com/entry/ctflearn-Taking-LS?category=1029036)

### 5) https 서버
만약 사이트가 https 프로토콜을 사용하고, 로컬의 서버가 http이면 전송이 불가능합니다.(https -> http 요청 불가)

따라서, https 서버가 필요하면 postbin을 사용할 수 있습니다. 사용법 간단합니다.

[post bin 사이트](https://www.toptal.com/developers/postbin/)
