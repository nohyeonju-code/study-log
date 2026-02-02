# study-log

# 오늘 공부한 내용(2026-2/2)


## 주제
-화살표 함수 문법(js)

 ### 화살표 함수
-화살표 함수는 함수를 읽기 편하게 만들려고 있는것.
-한 줄 표현식이면 `return `과 `{}` 생략 가능
-여러 줄이면 `return` 과`{}` 필요


---

### 예제 

```js

const test01 = () => console.log("hello world");
//return, {} 생략이 가능하다


const test02 = () => {
      console.log("hello world");
      alert("안녕");
};
//return, {} 둘 다 생략이 불가능하다.


const test03 = () => console.log("안녕");

const test04 = x => console.log(x);
//매개변수가 하나 일때 ()는 생략 사능하다.

const test05 = (a,b) => {
      return a+b;
};
//매개변수가 둘 이상일때 ()는 생략 불가능하다.



