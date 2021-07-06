1. ~/TIL 폴더 생성
2. toucj linux-command.md 로 생성
3. typora로 열기

# :computer:CLI 명령어

Unix 명령어를 학습합니다.



## summary

| 명령어        | 사용 예시           | 설명      |
| ------------- | ------------------- | --------- |
| `ctrl`  + `c` | `를 닫지 않았을 때, | c취소     |
|               |                     |           |
| `mkdir`       | `mkdir <dirname>`   | 폴더 생성 |





## 단축키 명령어

- 취소 => `ctrl` + `c`
- 터미널 청소 => `ctrl` + `l`
- 단어 삭제 => `ctrl` + `w`
- 터미널 종료 => `ctrl` + `d`
- 이전 / 다음 명령허 불러오기  => 상하 방향키
- 커서 이동 => 좌우 방향키



## 프롬프트(prompt $)

터미널의 `$`마크는, 명령이 입력 준비 완료를 의미

즉, `$`마크가 없을 경우에는, 명령어를 입력해도 제대로 동작하지 않습니다.



## 폴더

mkdir <dir_name>

~~~
$ mkdir <dir_name>
~~~



### 폴더 생성하기

~~~~
$ mkdir <dir_name>
~~~~



### 폴더 이동하기

~~~
$ cd <dir_name>
~~~



### 폴더 삭제하기

~~~
# 안전삭제
rm -r <dir_name>

# 강제삭제
rm -rf <dir_name>
~~~



## 파일

### 파일 생성하기

~~~
$ touch <file_name>	# 확장자까지 반드시 작성
~~~



### 파일 삭제하기

~~~~
$ rm <filename>
~~~~



### 파일 실행하기(컴퓨터 기본 실행 프로그램)

~~~
# windows
$ start <filename>

# macOS , linux
$ open <filename>
~~~



## 복사/이동

### 복사

~~~
$ cp <original_name> <copy_name>
~~~



### 이동

~~~
# 이름 바꾸기
$ mv <original_name> <another_name>

# 이동하기
$ mv <original_name> <another_path>
~~~



## 편집기
