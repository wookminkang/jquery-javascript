# jQuery->JavaScript REPOSITORY

## 자주 사용하는 제이쿼리 문법을 자바스크립트로 변환

### Add Class

- 클래스 추가하기

```JavaScript
$(el).addClass(className);
▼
el.classList.add(className);
```


### Append

- append를 이용하여 html 요소 생성하기.


```JavaScript
<div class="row"></div>
$(".row").append(el)
▼
const rowEl = document.querySelector(".row");
const plusDiv = document.createElement("div");
plusDiv.innerHTML = `<div><img src="/images/menu/abab.png"><p>hello!</p></div>`;
rowEl.append("plusDiv");

```

### Input value

- input value 값

```JavaScript
<input class="userName" value="kangminwook">
$(".userName").val();
▼
document.querySelector(".userName").value;
```