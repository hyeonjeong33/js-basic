## DOM (Document Object Model)

#### example 1 >
```js

const title = document.getElementById("title");

console.log(title);

title.innerHTML = "From JS";

title.style.color = "red";

document.title = "Practice";

```

#### example 2 >

```js

const title = document.querySelector("#title");

const CLICKED_CLASS = "clicked";

function handleCLick(){
    const hasClass = title.classList.contains(CLICKED_CLASS);
        /*
        if (hasClass){
            title.classList.remove(CLICKED_CLASS);
        } else {
            title.classList.add(CLICKED_CLASS);
        }
        */
    title.classList.toggle(CLICKED_CLASS);
}

function init() {
    title.addEventListener("click", handleCLick);
}

init();

```