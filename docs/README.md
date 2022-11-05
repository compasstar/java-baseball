# 미션 - 숫자 야구

숫자 야구 게임을 구현한 코드입니다.


## :rocket: 구현 기능


### 게임 시작 기능
- 숫자 야구 게임을 시작한다는 메시지를 출력함
- 컴퓨터 숫자 선택 기능으로 넘어감

### 컴퓨터 숫자 선택 기능
- 1에서 9사이 랜덤한 정수를 배열에 삽입
- 만일 배열 안에서 중복되는 숫자일 경우 다시 실행
- 배열의 크기가 3이 될 때까지 반복
- 플레이어 숫자 입력 기능으로 넘어감

### 플레이어 숫자 입력 기능
- 플레이어는 서로 다른 3개의 숫자를 입력
- [예외처리] 입력의 길이가 3이 아닌 경우
- [예외처리] 입력이 1 ~ 9 사이 숫자로 이루어지지 않은 경우
- [예외처리] 입력에 중복된 숫자가 있는 경우
- 정답 판별 기능으로 넘어감

### 정답 판별 기능
- 플레이어가 입력한 3개의 숫자가 정답이라면, 게임 종료 기능으로 넘어감
- 플레이어가 입력한 3개의 숫자가 정답이 아니라면, 힌트 제공 기능으로 넘어감

### 게임 종료 기능
- 숫자를 모두 맞혔다고 출력함
- 플레이어에게 1을 입력하여 게임을 새로 시작할 지, 2를 입력하여 종료할 지 물어봄
- [예외처리] 플레이어의 입력이 1 혹은 2가 아닌 경우
- 플레이어의 대답에 따라, 처음(컴퓨터 숫자 선택 기능)으로 돌아가거나 프로그램이 종료됨

### 힌트 제공 기능
- 스크라이크 개수 세기기능을 통해 스트라이크 개수를 셈
- 볼 개수 세기기능을 통해 볼 개수를 셈
- 스트라이크 개수, 볼 개수를 출력하거나 둘 다 0이라면 낫싱을 출력함
- 플레이어 숫자 입력 기능으로 넘어감

### 스트라이크 개수 세기 기능
- 같은 수가 같은 자리에 있는 숫자의 개수를 셈

### 볼 개수 세기 기능
- 같은 수가 다른 자리에 있는 숫자의 개수를 셈