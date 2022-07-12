# JavaScript

## 변수
  1. `let`    재할당 가능
  2. `const`  재할당 불가능
  3. `var`    과거에는 많이 사용했지만, 현재는 여러 단점들 때문에 사용 지양

## 데이터 타입
  1. 숫자
  ```javascript
  console.log(10)       // 10
  const age = 20
  console.log(age)      // 20
  ```
  2. 문자열
  ```javascript
  console.log('string') // string
  console.log('30')     // 30 (문자열)
  const string = 'poem'
  console.log(string)   // poem
  ```
  3. Boolean
  ```javascript
  console.log(true)     // true
  const bool = false
  consol.log(bool)      // false
  ```
  4. null, undefined
  ```javascript
  const name1 = null
  const name2
  console.log(name1)    // null
  console.log(name2)    // undefined
  ```
  
## 연산자
  1. 문자열 붙이기
  - `+`를 사용하여 이어 붙일수 있다. (문자와 숫자를 이어붙이면 숫자가 문가로 인식됨)
  ```javascript
  console.log('My ' + 'name ' + 'is ' + 'xiara125')   // My name is xiara125
  console.log('I ' + 'have ' + 3 + ' car')            // I have 3 car
  ```
  - 템플릿 리터럴(Template literals)
  ```javascript
  const carPrice = 250000
  console.log(`이 차는 ${carPrice}원 입니다.`)           // 이 차는 250000원 입니다.
  ```
  2. 산술연산자
  - 숫자 데이터 연산 가능
  `+`   덧셈
  `-`   뺄셈
  `*`   곱셈
  `/`   나눗셈
  `%`   나머지
  `**`  거듭제곱
  ```javascript
  console.log(25 % 7)                               // 4
  ```
  3. 증감연산자
  - 자신의 값을 증가시키거나 감소시킴
  
  
