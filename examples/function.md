## Function

```js

function sayHello(name, age) {
    console.log('Hello!', name, "you have", age, "years of age.");
}

sayHello("hyeonjeong", 27);

function sayHello1(name, age) {
    return `Hello! ${name} you have ${age} years of age.`;
}

const greet = sayHello1("hyeonjeong", 27);
console.log(greet);


const calculator = {
    plus: function(a, b){
        return a + b;
    }
}

const plus = calculator.plus(5, 5);
console.log(plus);

```
