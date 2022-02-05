# C(발) 언어
한국 욕으로만 이루어진 프로그래밍 언어이다.
## 연산자
### 숫자 연산자
병신(**BYUNGSIN**): -1
새끼(**TSEQUI**): +1
개(**GE**): +5
씹(**TSIP**): +10
좆(**JOT**): +100
### 계산 연산자
더하기: 그냥 숫자 연산자 붙이면 더해진다.
곱하기: 두 숫자 연산자 사이에 점(.)을 붙인다.
나누기: 두 숫자 연산자 사이에 콤마(,)를 붙인다.
빼기: 원하는 값에 병신(-1)을 곱하고 더해준다. (중1 수학에 나오는 것)
### 대입 연산자
미친놈(**MICHINNOM**) 명령어를 사용하면 변수의 값을 바꿀 수 있다. 우선 두 변수에 원하는 값을 담은 다음 미친놈 명령어 뒤에 원하는 연산을 붙인다. 다음 코드는 시발 변수에 3을 할당하고, 다시 1을 더한다.
```
시발새끼새끼새끼
시이발새끼
미친놈시발시이발
```

## 변수
변수 선언 그딴건 없고 선언 + 할당 동시에 해야된다.
### 변수 선언
변수명은 시발(**SIBAL**)로 이루어졌고, 시발 시이발(**SIIBAL**) 시이이발(**SIIIBAL**) ... 이런식으로 간다.
### 변수 할당
숫자 연산자를 사용해서 변수의 값을 할당한다. 선언과 할당은 띄우지 않는다. 다음 코드는 시발이란 변수을 선언하고 3을 할당한다.
```
시이발새끼새끼 // 시이발=1+1=2
시발시이발.시이발병신 // 시발=시이발*시이발-1=2*2-1=3
```
혹은
```
시발새끼새끼새끼 // 시발=1+1+1=3
```
### 최적화
아무리 시발어라 해도 최상의 소프트웨어 환경을 위해 최적화 과정을 필요하다. 썅(**TSYANG**) 명령어는 주어진 변수를 삭제한다. 다음 코드는 시발에 3을 할당하고, 시발을 삭제한다.
```
시발새끼새끼새끼
썅시발
```

## 입출력
표준 입출력을 위한 여러 가지의 명령어들이 준비되어 있다.
### 입력
지랄(**JIRAL**) 명령어는 표준 입력으로 값을 받은 뒤에 그 값을 반환한다. 다음 코드는 표준 입력을 받아 시발 변수에 저장한다.
```
시발지랄
```
### 출력
#### 숫자
닭쳐(**DAKCHO**) 명령어는 뒤에 붙는 모든 숫자를 표준 출력으로 내보낸다. 다음 코드는 표준 출력으로 3을 내보낸다.
```
닭쳐새끼새끼새끼
```
#### 문자(ASCII)
아가리(**AGARI**) 명령어는 뒤에 붙는 모든 숫자를 아스키 문자로 변환해 표준 출력으로 내보낸다. 다음 코드는 표준 출력에 hi를 내보낸다.
```
아가리좆새끼새끼새끼새끼
아가리개좆
```
#### 문자(UTF-8)
씨부랄(**TSHIBURAL**) 명령어는 뒤에 붙는 모든 숫자를 UTF-8 문자로 변환하여 표준 출력으로 내보낸다. 아가리 명령어와 매우 비슷하기 때문에 코드는 생략한다. (TIP: 변수에 100 * 100을 저장해두고 계산하면 편하다)

## 반복문
꺼져(**KKUJEO**) 명령어를 이용해 원하는 줄로 이동할 수 있다. 꺼져 뒤에 줄의 번호를 붙이면 된다. 다음 코드는 3번째 줄로 이동하는 명령어이다.
```
꺼져새끼새끼새끼
```

## 조건문
등신(**DEUNGSIN**) 명령어를 이용하여 변수가 특정 조건을 만족할 때 명령을 실행할 수 있다. 다음 코드는 시발 변수가 3일 때 1번째 줄로 이동한다.
```
등신시발=새끼새끼새끼:꺼져새끼
```
