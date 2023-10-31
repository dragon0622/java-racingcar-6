### 기능 목록 ###

[o] 사용자에게 자동차 이름과 전진횟수를 입력받는다. -Input.carName(), Input.gameRound()

[o] 전진횟수만큼 난수를 발생시킨다. -RandomNum.number()

[o] 발생시킨 난수가 4이상 시 자동차를 전진시킨다. -Action.moveCar()

[o] 횟수가 1회 진행될때의 상황을 출력한다. -Output.printResult()

[o] 마지막 회차까지 진행했을때 우승자를 출력한다.(동차는 허용한다.) -Output.printWinner()



### 예외 처리 ###

[-] 자동차 이름이 5자를 초과하거나 1보다 작을 수 없다. -carNumberLengthException()

[-] 자동차의 이름은 서로 중복 될 수 없다. -carNumberSameException()

[-] 이름 구분은 이름 사이 한개의 ','로만 이루어 진다. -lotsOfCommaException()

[-] 이름을 구분할때 띄어쓰기가 들어갈 수 없다. -blankException()

[-] 라운드는 정수로만 입력할 수 있다. -noIntRoundException()

