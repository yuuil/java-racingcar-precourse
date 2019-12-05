# 프리코스 2주차 자동차경주게임



### 기능 요구사항

- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다. •자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
- 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 random 값을 구한 후 random 값이 4 이상일 경우 전진하고, 3 이하의 값이면 멈춘다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다. 



### 프로그래밍 요구사항

#### 1. 객체

- [ ]  Car 객체를 활용해 구현.
- [ ]  Car 기본 생성자를 추가할 수 없다.
- [ ]  name, position 변수의 접근 제어자인 private을 변경할 수 없다.
- [ ]  가능하면 setPosition(int position) 메소드를 추가하지 않고 구현한다.

#### 2. 프로그래밍

- [ ]  3항 연산자를 쓰지 않는다.
- [ ]  Indent depth는 3이 넘지 않도록 구현한다.



---



### 구현할 기능 목록

- [ ]  자동차 이름 입력받기 (각 자동차의 이름은 `쉼표(,)` 를 기준으로 구분)
- [ ]  시도할 회수 입력받기
- [ ]  랜덤값 생성
- [ ]  랜덤값에 따른 자동차 제어
- [ ]  우승자 출력 (우승자는 한 명 이상일 수 있음)