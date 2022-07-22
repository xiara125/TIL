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
  console.log(`이 차는 ${carPrice}원 입니다.`)            // 이 차는 250000원 입니다.
  ```
  
  2. 산술연산자(Numeric operators)
  - 숫자 데이터 연산 가능
    - `+`   덧셈
    - `-`   뺄셈
    - `*`   곱셈
    - `/`   나눗셈
    - `%`   나머지
    - `**`  거듭제곱
  ```javascript
  console.log(25 % 7)                                 // 4
  ```
  
  3. 증감연산자(Increment Decrememt operators)
  - 자신의 값을 증가시키거나 감소시킴
    1. `count`에 값을 더한 후 `precount`에 할당  
    ```javascript
    let count = 1
    const precount = ++count
    cosole.log(count)                                 // 2
    cosole.log(precount)                              // 2 
    ```
    2. `postcount`에 먼저 할당 후 값을 `count`에 더함
    ```javascript
    let count = 1
    const postcount = count++
    cosole.log(count)                                 // 2
    cosole.log(precount)                              // 1
    ```
    
  4. 대입연산자(Assignment operators)
  - `=` : 어떤 값을 어떤 변수에 할당
  - `+=`, `-=` : 연산과 대입을 한번에 사용 가능
  ```javascript
  const dressPrice = 200000
  const bagPrice = 300000
  let totalPrice = 0
  
  totalPrice += dressPrice
  console.log(totalPrice)                            // 200000
  totalPrice += bagPrice
  console.log(totalPrice)                            // 500000
  
  totalPrice -= dressPrice
  console.log(totalPrice)                            // 300000
  ```
  
  5. 비교연산자(Comparison operators)
  - 숫자값을 비교하는 연산자, 이것을 통해 얻는 값이 `boolean`
  ```javascript
  console.log(2 < 5)                                 // true
  console.log(2 <= 7)                                // true
  console.log(2 > 5)                                 // false 
  console.log(2 >= 7)                                // false
  ```
  
  6. 논리연산자(Logical operators)
  - `||` : or
  - `&&` : and
  - `!`  : not
  ```javascript
  let isOnSale = true
  let isDiscountItem = true

  console.log(isOnSale && isDiscountItem)            // true
  console.log(isOnSale || isDiscountItem)            // true

  isOnSale = false
  console.log(isOnSale && isDiscountItem)            // false
  console.log(isOnSale || isDiscountItem)            // true

  isDiscountItem = false
  console.log(isOnSale && isDiscountItem)            // false
  console.log(isOnSale || isDiscountItem)            // false

  console.log(!isOnSale)                             // true
  ```
  
  7. 일치연산자(Equality operators)
  - 주어진 두 값이 일치하는지 비교
  ```javascript
  console.log(1 === 2)                               // true
  console.log(1 === 2)                               // false
  console.log(javascript === javascript)             // true
  console.log(javascript === Javascript)             // false
  ```
  - `==`  : 값만 비교
  - `===` : 값과 데이터타입 비교
  ```javascript
  console.log(1 == "1")                            // true
  console.log(1 === "1")                           // false
  ```
  
## 조건문
  1. if
  ```javascript
  const dressPrice = 50000
  if(dressPrice < 40000) {
      console.log('드레스을 사겠습니다.')
  } else {
      console.log('너무 비싸요. 드레스를 사지 않겠습니다.')
  }
  ```
  2. else, else if
  ```javascript
  const dressPrice = 50000
  if(dressPrice < 40000) {
      console.log("이 드레스를 사겠습니다.")
  } else if (dressPrice <= 50000) {
      console.log("조금 더 고민해볼게요")
  } else {
      console.log("너무 비싸요. 사지 않겠습니다.")
  }
  ```
