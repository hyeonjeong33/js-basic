## if-else

#### example 1 >
```js

const age = prompt("how old are you");

if(age >= 18 && age <= 21) {
    console.log("you can drink");
}else if(age > 21) {
    console.log("go ahead")
}else {
    console.log("too young");
}

```

#### example 2 > DOM

```js

function handleOffline(){
    console.log("offfline")
}

function handleOnline(){
    console.log("online")
;}

window.addEventListener("offline", handleOffline)
window.addEventListener("online", handleOnline);

```

#### example 3 > DOM

```js

const title = document.querySelector("#title");

const BASE_COLOR = "rgb(52, 73, 94)"
const OTHER_COLOR = "#7f8c8d";

function handleClick(){
    const currentColor = title.style.color;
    if (currentColor === BASE_COLOR){
        title.style.color = OTHER_COLOR;
    } else {
        title.style.color = BASE_COLOR;
    }
}

function init(){
    title.style.color = BASE_COLOR;
    title.addEventListener("click", handleClick);
}
init();

```