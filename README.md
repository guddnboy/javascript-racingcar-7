# javascript-racingcar-precourse

## 기능 요구사항

- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.

- 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.

- 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.

  - 이름에 공백 포함 가능

- 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.

  - 0 입력 시 전원 우승

- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.

  - 값이 0 ~ 3 사이일 경우, 정지
  - 값이 4 ~ 9 사이일 경우, 전진

- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
  - 우승자가 여러명일 경우 입력 순서대로 출력
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.

- 사용자가 잘못된 값을 입력할 경우 "[ERROR]"로 시작하는 메시지와 함께 `Error`를 발생시킨 후 애플리케이션은 종료되어야 한다.
  - 횟수에 음수 입력 시 "[ERROR]"
  - 횟수에 숫자가 아닌 값 입력 시 "[ERROR]"
  - 자동차 이름이 6글자 이상일 경우 "[ERROR]"
  - 자동차 이름이 공백일 경우 "[ERROR]"
  - 자동차 이름이 연속적으로 쉼표만 작성된 경우 "[ERROR]"
  - 자동차 이름이 중복일 경우 "[ERROR]"

## **실행 결과 예시**

```
경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
pobi,woni,jun
시도할 횟수는 몇 회인가요?
5

실행 결과
pobi : -
woni :
jun : -

pobi : --
woni : -
jun : --

pobi : ---
woni : --
jun : ---

pobi : ----
woni : ---
jun : ----

pobi : -----
woni : ----
jun : -----

최종 우승자 : pobi, jun

```
