# :book: markdown 작성법

제일 큰 제목은 대체로 문서상 한 번만 나오는게 맞음

## 제목(heading)

제목은 문서의 구조와 관련이 있음. h1 ~ h6까지 존재하며, #을 붙여서 표현 가능.

## 목록(list)

### 순서 있는 목록

문장 맨 처음에 1.하고 띄어쓰기하면 자동으로 목록으로 바뀜

1. 수업을 한다.
   1. 슬라이드 진행
   2. Tab / Tab + Shift
2. 쉬는시간을 갖는다.
3. 수업을 한다.
4. 밥을 먹는다.
   1. 메뉴를 고른다.
   2. 주문을 한다.
   3. 먹는다.
   4. 계산을 한다.
5. 수업을 한다.

### 순서 없는 목록

문장 맨 처음에 -를 쓰고 띄어쓰기 하면 자동으로 바뀜

- git
  - 리포 초기화 하기
  - 스테이징 하기
- CLI 명령어
- markdown 문법



## 본문 꾸미기(inline deco)

인용구(있어 보이는 말)

> 오늘도 나는 공부를 한다
>
> 열.심.히



나는 오늘 **github** 특강을 듣는다.	**볼드처리 : -Ctrl + B-

git은 *VCS이다*.								*이탤릭 : -Ctrl + I-

폴더를 이동할 때는, `cd` 명령어를 사용한다.

폴더를 생성할 때는, `mkdir` 명령어를 사용한다.	`///

## 코드 블럭(code block)

backquote(backtic)3개로  + Enter로 코드블럭 생성

```python
a = 1
b = 2
c = a + b
print(c)

def my_func(n):
	return n + 1
```

## 표(table)

우클릭 - 삽입 - 표

pope(|)로 열을 구분하고 Enter로 표 생성. ctrl + Enter로 행 추가

| 명령어  | 설명      | 사용 예시   |
| ------- | --------- | ----------- |
| `mkdir` | 폴더 생성 | `mkdir aaa` |
| `cd`    | 폴더 이동 | `cd aaa`    |
| `touch` | 파일 생성 | `touch aaa` |
| `rm`    | 파일삭제  | `rm aaa1`   |

## 수식(TeX)

달러사인($) 두 개로 블럭 생성. 내부 작성법은 따로 학습해야 함.
$$
\begin{align*}
y = y(x,t) &= A e^{i\theta} \\
&= A (\cos \theta + i \sin \theta) \\
&= A (\cos(kx - \omega t) + i \sin(kx - \omega t)) \\
&= A\cos(kx - \omega t) + i A\sin(kx - \omega t)  \\
&= A\cos \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big) + i A\sin \Big(\frac{2\pi}{\lambda}x - \frac{2\pi v}{\lambda} t \Big)  \\
&= A\cos \frac{2\pi}{\lambda} (x - v t) + i A\sin \frac{2\pi}{\lambda} (x - v t)
\end{align*}
$$


# 일번

