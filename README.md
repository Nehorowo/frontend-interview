# Frontend interview questions

## Практическая часть
1. ### Что функция x выведет в консоль?
```javascript
function x() {
    for (var i = 1; i <= 5; i++) {
        setTimeout(function() {
            console.log(i);
        }, i * 1000)
    }
}
```