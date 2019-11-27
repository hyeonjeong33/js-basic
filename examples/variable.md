## Variable(변수)
- 생성 -> 초기화 -> 사용
- ES5 -> var
- ES6 -> let, const

```js

let a = 2;
let b = a + 3;
console.log(a, b);

a = 512;
console.log(a);

const con = 64;
con = 5555; // TypeError, Const cannot be changed

```
