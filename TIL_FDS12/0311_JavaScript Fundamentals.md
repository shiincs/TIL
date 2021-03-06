# JavaScript Fundamentals

## 프로그래밍 기본

### 입력, 저장, 처리, 출력에 관한 문법

- 입력: prompt, form tag
- 저장: 변수, 쿠키, 웹 스토리지, 데이터베이스
- 처리: 연산, 분기, 반복
- 출력: `console.log`, 화면에 DOM 추가

변수: 어떤 것을 담는 그릇

여러가지 여러 종류를 담는 그릇: 배열 (리스트, 딕트, 튜플, 셋)

변수에 무엇인가를 담아서 사용?! - 컴퓨터는 암산 불가

변수: 만들기, 값 읽기, 값 바꾸기, 값 사용(연산의 피연자, 함수의 매개변수)

`a = "Hello JavaScript";` - a라는 이름을 가진 저장공간을 만들고, 거기에 "~~" 값을 저장(할당) 한다.

`=` 은 할당 연산자 / `=`의 의미는 일반적으로는 같다. 프로그래밍에서는 저장한다. `==`를 같다는 의미로 사용한다.



### 변수명을 만드는 방법

1. 숫자는 변수 이름 맨 앞에 사용하지 않는다.
2. 특수문자는 _(언더바)만 사용한다.
3. 변수명은 대소문자를 구분한다.
4. 명사, 동사로 변수명을 작성한다.
5. 예약어는 사용 금지



### 변수명을 작성하는 방법

1. 카멜 케이스(Camel Case): `yourName` 
   - 각 단어의 첫 글자를 대문자, 나머지는 소문자
2. 파스칼 케이스(Pascal Case): `YourName` 
   - 모든 단어의 첫 글자를 대문자, 나머지는 소문자
3. 스네이크 케이스(Snake Case): `your_name` 
   - 단어들 사이에 _(언더바)를 넣는 방법 전체 소문자.
4. 헝가리안 표기법: `strName`, `intNumber`
   - 변수명 앞에 어떤 데이터를 저장할 것인지 기록해두는 방법



### 프로그래밍 진행 방법

- 순차: 코드의 위에서부터 아래쪽으로 한줄씩 실행된다.
- 분기: A를 실행할지, B를 실행할지 선택하는 것 (조건에 따라서)
- 반복: A, B 중에 실행할 코드를 여러번 반복실행하고 싶을 때



### if문

if문은 if-else ~ if-else 키워드로 구성되어 있다.

if : 만약 조건식이 참이라면 해당 부분의 실행구문을 실행하겠다. (1번)

else if : 그게 아니라, 다음 조건식이 참 이라면 해당 부분의 실행구문 실행하겠다. (0 ~ 무제한)

else  : 1번



### 조건식

명제 - 참과 거짓을 판별할 수 있는 문장

true, false 라고 참 거짓을 표기 - Boolean, Bool

