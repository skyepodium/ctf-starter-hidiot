# CTF starter Hidiot

### 1) 소개
**CTF(Capture the Flag)** 는 간단히 말해서 **해킹 대회**

### 2) 학습 사이트
[드림핵](https://dreamhack.io/) - 정말 좋아요

### 3) wargame
wargame은 자신의 페이스로 진행할 수 있는 환경입니다.      

- [picoCTF](https://picoctf.org/)
- [ctflearn](https://ctflearn.com/)
- [ctf-d](http://ctf-d.com/)
- [HackCTF](https://ctf.j0n9hyun.xyz/)

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
### 1) [Cyber chef](https://gchq.github.io/CyberChef/) 🔥🔥🔥
다양한 암호 알고리즘의 디코딩, 인코딩을 온라인으로 지원합니다.

사용법이 간편하고, 문자열 입력값에 따라 가장 유사한 디코딩 알고리즘도 추천해줍니다.

### 2) [암호 알고리즘 판별](https://www.dcode.fr/cipher-identifier) 
어떤 알고리즘인지 감이 안잡히는 경우 대략적으로 파악할 수 있습니다.   
- [[EZCTF] No kidding](https://skyepodium.tistory.com/entry/EZCTF-No-kidding)

### 3) Base64 🔥🔥🔥
기본중의 기본으로 정말 여러가지로 응용해서 나옵니다.
- [base64 repair](https://base64.guru/tools/repair)
- [[ctflearn] Base 2 2 the 6](https://skyepodium.tistory.com/entry/ctflearn-Base-2-2-the-6?category=1029036)
- [[pico CTF] login](https://skyepodium.tistory.com/entry/pico-CTF-login)
- [파이썬 구현](https://velog.io/@skyepodium/base64-%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EA%B5%AC%ED%98%84)

### 4) [ROT13 - caesar cypher](https://gchq.github.io/CyberChef/#recipe=ROT13(true,true,false,13))
쉬운 문제로 종종 출제되거나 다른 문제에 응용됩니다.
- [[pico CTF] caesar](https://skyepodium.tistory.com/entry/pico-CTF-caesar)

### 5) [비즈네르 암호(vigenere cypher)](https://gchq.github.io/CyberChef/#recipe=Vigen%C3%A8re_Decode('blorpy')&input=Z3dveHtSZ3Fzc2loWXNwT250cXB4c30)
문자열과 key를 기반으로 암복호화하는 알고리즘 입니다.     

- [[ctflearn] Vigenere Cipher](https://skyepodium.tistory.com/entry/ctflearn-Vigenere-Cipher?category=1029036)
- [[Vigenere Cipher] 비즈네르 암호 구현](https://velog.io/@skyepodium/Vigenere-Cipher-%EB%B9%84%EC%A6%88%EB%84%A4%EB%A5%B4-%EC%95%94%ED%98%B8-%EA%B5%AC%ED%98%84)

### 6) 진법과 아스키
정말 다양한 방법들이 있습니다, cyber chef를 적극 이용합니다.

- [[ctflearn] Character Encoding](https://skyepodium.tistory.com/entry/ctflearn-Character-Encoding?category=1029036)     
- [[ctflearn] Reverse Polarity](https://skyepodium.tistory.com/entry/ctflearn-Reverse-Polarity?category=1029036)

### 7) [모스부호](https://onlineasciitools.com/convert-morse-to-ascii)
- [[EZCTF] More sense](https://skyepodium.tistory.com/entry/EZCTF-More-sense)
- [[cflearn] Morse Code](https://skyepodium.tistory.com/entry/cflearn-Morse-Code?category=1029036)

### 7) [키보드 레이아웃](https://awsm-tools.com/text/keyboard-layout)
키보드 배열 다르게 해서 암호 문제로 제출됩니다.    
- [[BCACTF 3.0] New Keyboard](https://skyepodium.tistory.com/entry/BCACTF-30-New-Keyboard?category=1028047)

# 2. web
### 1) [Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg) 🔥🔥🔥
웹이 어떤 프레임워크로 구성되어있는지 확인해주는 크롬 확장 프로그램, 개인적으로 정말 잘쓰고 있어서 추천!!!   

![cover](./images/wappalyzer.png)


### 2) [크로스 사이트 스크립팅 - xss](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/web/xss.md)
- [BYU CTF 2022 - Social Media](https://skyepodium.tistory.com/entry/BYU-CTF-2022-Social-Media-%ED%81%AC%EB%A1%9C%EC%8A%A4%EC%82%AC%EC%9D%B4%ED%8A%B8-%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8C%85?category=1028047) - 정석적인 쿠키 탈취 문제

- [[BSidesSF CTF] web-tutorial-1](https://skyepodium.tistory.com/entry/BSidesSF-CTF-web-tutorial-1?category=1028047) - 응용 문제

### 3) Header
- [[pico CTF] Who are you?](https://skyepodium.tistory.com/entry/pico-CTF-Who-are-you)

### 4) file traversal
웹 디렉토리 찾는 문제, 자주 출제됩니다.

[Forbidden Paths](https://skyepodium.tistory.com/entry/pico-CTF-Forbidden-Paths)

### 5) 웹쉘
네트워크로 받은 파라미터를 통해 시스템 콜을 사용하는 취약점입니다.
- [UMassCTF 2021 - Hermit - Part 1](https://velog.io/@skyepodium/UMassCTF-2021-writeup)

### 6) 자바스크립트 재정의
클라이언트 사이드에서 자바스크립트로 필터링 하고 있다면, 다음 문제처럼 그냥 재정의 해버립시다.
- [[SECCON Beginners CTF 2022] Util](https://skyepodium.tistory.com/entry/SECCON-Beginners-CTF-2022-Util)

### 7) 커맨드라인 인젝션
';' 세미콜론으로 커맨드 구분해서 나오는 경우가 있습니다.
- [[SECCON Beginners CTF 2022] Util](https://skyepodium.tistory.com/entry/SECCON-Beginners-CTF-2022-Util)

### 8) [자바스크립트 난독화 예쁘게](https://beautifier.io/)
난독화 된것을 원래대로는 못돌리고, 예쁘게 포맷팅해서 분석해야합니다.

[[pico CTF] Client-side-again](https://skyepodium.tistory.com/entry/pico-CTF-Client-side-again)

### 9) 크롬 브라우저 **Search in all files**
웹앱의 모든 리소스에서 문자열을 검색할 때 유용합니다.
- [[pico CTF] Search source](https://skyepodium.tistory.com/entry/pico-CTF-Search-source)

### 10) 특이한 문제
- [PDF - latex](https://skyepodium.tistory.com/entry/SECCON-Beginners-CTF-2022-textex)

# 3. php
php는 웹에 분류되지만, 자주 출제됩니다.

### 1) php파일로 인식될 수 있는 확장자
```
php
php3
php4
php5
php7
pht
phtml
phar
```
### 2) [php pregreplace](https://skyepodium.tistory.com/entry/php-pregreplace)
문자열 필터링
### 3) php filter bypass
특정 문자열 필터를 바이 패싱 하는 문제
- [[EZCTF] I made a blog!](https://skyepodium.tistory.com/entry/EZCTF-I-made-a-blog) - base64 사용

# 4. SQL Injection
### 1) [cheet sheet](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/sqli/sheet.md)

### 2) 주석 처리
sql 에서 주석 처리는 DB 마다 다르지만 MySql에서는 '--' 으로 할 수 있습니다.

다만, 이는 where 절에서 가능하며
INSERT 구문의 value에서는 불가능합니다.

### 3) 기초
- [[ctflearn] Basic Injection](https://skyepodium.tistory.com/entry/ctflearn-Basic-Injection?category=1029036)

### 4) blind sql injection 🔥 
브루트 포스와 함께 사용하며, 내가 생각하는 데이터가 맞는지 맞추면서 진행됩니다.
- [SquareCTF 2020 - Deep Web Blog](https://velog.io/@skyepodium/SquareCTF-Writeup)

### 5) union sql injection 🔥
union을 사용하는 방법으로 유용합니다.
- [[BSidesSF CTF] Sequels: A New Bug](https://skyepodium.tistory.com/entry/BSidesSF-CTF-Sequels-A-New-Bug)

# 5. forensics
### 1) Hex editor 🔥🔥🔥
헥스 에디터는 필수품으로 정말 많은 분야에서 사용됩니다.
- windows - https://mh-nexus.de/en/hxd/
- mac - ihex

- [[pico CTF] information](https://skyepodium.tistory.com/entry/pico-CTF-information)

### 2) [Wireshark](https://www.wireshark.org/) 🔥🔥🔥
와이어 샤크 - 패킷 덤프를 분석하는 프로그램
- [[pico CTF] shark on wire 1](https://skyepodium.tistory.com/entry/pico-CTF-shark-on-wire-1)      
- [[n00bzCTF] tcpdump](https://skyepodium.tistory.com/entry/n00bzCTF-tcpdump)

### 3) fcrack
zip 파일을 여는 프로그램
- [CyberYoddha CTF - Crack the Zip!](https://velog.io/@skyepodium/CyberYoddha-CTF-Writeup#2-crack-the-zip)

# 6. stegnography
### 1) [foremost](http://foremost.sourceforge.net/) 🔥
포렌식용 툴인데, 파일 카빙할 때 사용 가능합니다. 개인적으로 제일 좋아합니다.

윈도우에서는 [WSL(Windows Subsystem for Linux)](https://docs.microsoft.com/ko-kr/windows/wsl/install) 에 설치합니다.

```
foremost -t all a.png
```

- [[ctflearn] Binwalk](https://skyepodium.tistory.com/entry/ctflearn-Binwalk?category=1029036)

### 2) [binwalk](https://github.com/ReFirmLabs/binwalk)
이미지에 숨겨진 파일을 추출합니다.   
```
binwalk --extract --dd=".*" a.png
```
- [[pico CTF] Matryoshka doll](https://skyepodium.tistory.com/entry/pico-CTF-Matryoshka-doll)

### 3) [zsteg](https://github.com/zed-0xff/zsteg)
이미지에 숨겨진 문자열을 찾아냅니다.

- [[BCACTF 3.0] My New Friend](https://skyepodium.tistory.com/entry/BCACTF-30-My-New-Friend)

### 4) stegsolve
색, 명암을 변경하여 숨겨진 문자열을 찾습니다.
- [[EZCTF] Neo](https://skyepodium.tistory.com/entry/EZCTF-Neo)
- [CyberYoddha CTF - Steg 2](https://velog.io/@skyepodium/CyberYoddha-CTF-Writeup#4-steg-2)
- [syskronCTF - 5. Wednesday](https://velog.io/@skyepodium/syskronCTF-Writeup#5-wednesday)

### 5) exiftool
파일속에 숨겨진 정보를 찾습니다.
- [[ctflearn] WOW…. So Meta](https://skyepodium.tistory.com/entry/ctflearn-WOW%E2%80%A6-So-Meta?category=1029036)
- [[ctflearn] Snowboard](https://skyepodium.tistory.com/entry/ctflearn-Snowboard)

### 6) [스테가노그라피 온라인](https://stylesuxx.github.io/steganography/)
숨겨진 문자열을 찾습니다.
- [[EZCTF] Nobody's perfect](https://skyepodium.tistory.com/entry/EZCTF-Nobodys-perfect)

### 7) [스테그하이드](https://futureboy.us/stegano/decinput.html) 🔥
- [[EZCTF] Bernie](https://skyepodium.tistory.com/entry/EZCTF-Bernie)

### 8) strings
바이너리 파일을 문자열을 추출하는 함수
- [[ctflearn] Forensics 101](https://skyepodium.tistory.com/entry/ctflearn-Forensics-101?category=1029036)

- [[pico CTF] strings it](https://skyepodium.tistory.com/entry/pico-CTF-strings-it)



# 7 . reversing
### 1) [기드라](https://ghidra-sre.org/) 🔥🔥🔥
NSA에서만든 C언어 디컴파일러, 영화에 나오는 그 곳 맞습니다.
- 디 어셈블러 - 바이너리 코드의 어셈블리 코드 확인
- 디 컴파일러 - 바이너리 코드로 부터 원래의 코드 확인

리버싱을 하려면 디 컴파일러가 필요합니다. 유명한 도구는 IDA인데 가격이 비싸서, 무료인 기드라를 사용합니다. 

### 2) [jadx-gui](https://velog.io/@skyepodium/%EB%A7%A5-jadx-gui-%EC%84%A4%EC%B9%98)
jar를 디컴파일 하는 경우 jadx-gui를 사용합니다.


# 8. pwnable 🔥🔥🔥
### 1) [pwntools](https://github.com/Gallopsled/pwntools)
exploit 파이썬 라이브러리
파이썬2 기반이어서 가상환경 구축하고 사용합니다.
다양한 기능이 있고, 효율성이 좋아서 사용합니다.

### 2) 쉘코드
```
// 32bit - 26 바이트
\x31\xc0\x50\x68\x6e\x2f\x73\x68\x68\x2f\x2f\x62\x69\x89\xe3\x31\xc9\x31\xd2\xb0\x08\x40\x40\x40\xcd\x80'
```
### 3) 코드 분석
- [CyberYoddha CTF - Password 1](https://velog.io/@skyepodium/CyberYoddha-CTF-Writeup#1-password-1)


### 3) Buffer over flow
포너블의 시작, 버퍼 오버 플로우에서 시작합니다. 정말 중요
- [0xL4ugh CTF - Leak](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup#3-leak)
- [meta CTF - Baffling Buffer 0](https://velog.io/@skyepodium/Meta-CTF-Writeup#1-baffling-buffer-0)
- [meta CTF - Baffling Buffer 1](https://velog.io/@skyepodium/Meta-CTF-Writeup#2-baffling-buffer-1)

### 4) format string
포맷 스트링 공격 몇번 해보면 감이 옵니다.
- [0xL4ugh CTF - Trigger Happy](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup#2-trigger-happy)

# 9. programming
보안과는 관련없이 프로그래밍을 하는 문제가 있습니다. 파이썬으로 진행하면 유리한 점이 많습니다.
- [[pwnable.kr] coin1](https://velog.io/@skyepodium/pwnable-coin1)

# 10. 팁
### 1) robots.txt
robots.txt는 웹 크롤러가 해당 경로에 접근하지 말라는 의미로 domain/robots.txt에 지정합니다.

robot 어쩌구 저쩌구 나오면 힌트가 있을 확률이 높고, 그것이 아니더라도 여러 CTF 대회에서 먼저 확인하는 부분중 하나 입니다.
- [[ctflearn] Where Can My Robot Go?](https://skyepodium.tistory.com/entry/ctflearn-Where-Can-My-Robot-Go?category=1029036)
- [pico CTF - where are the robots](https://play.picoctf.org/practice?category=1&page=1&search=where%20are%20the%20robots)

### 2) [매직 해시](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/hash/magic-hash.md)
불리언 문맥에서 0으로 평가받을 수 있는 해시들의 모음입니다.

# 11. 기타
### 1) | 파이프라인
다음과 같이 쓰는 경우가 많습니다. `|` 파이프라인은 앞의 결과를 뒤 함수의 인풋으로 넣습니다.
```
cat flag.txt | grep flag{
```
### 2) grep
grep 은 특정 내용이 포함된 문자열을 필터링 하는 함수입니다.
```
cat flag.txt | grep flag{
```
### 3) 맥북 아이피 확인
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
