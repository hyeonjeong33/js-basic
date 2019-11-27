## Array
- List data from DB.
```js

dayOfWeek = ["mon", "tue", "wed", "thu", "fri", "sat", "sun"]
console.log(dayOfWeek);

```

## Object
- We can put an array inside an object.
```js

const myInfo = {
    name: "hyeonjeong",
    age: 27,
    favMovies: ["Frozen", "Mamma mia"],
    favFood: [
        {
            name: " malatang",
            spicy: true
        },
        {
            name: "pizza",
            spicy: false
        }
    ]
}

console.log(myInfo);
console.log(myInfo.age);
myInfo.age = 29;
console.log(myInfo.age);
console.log(myInfo.favFood[0].spicy);


```