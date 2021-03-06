# Java GUI를 이용해 만든 typing game

## :sparkles: Description
"산성비 게임"을 모티브로 하여 단어가 내려오면 타이핑하여 맞추고, 점수를 올리는 게임이다.
플레이어가 한타/영타, 난이도를 설정해 플레이 할 수 있고 결과를 저장해 랭킹을 업데이트 한다.

## :bulb: Features
1. 메인 페이지
    - 한타/영타, 난이도 선택, 플레이어 정보 입력 후 "게임시작"
    - 보고싶은 게임 모드(한타/영타, 난이도 정보) 선택 후 "랭킹보기"<br>
    (홈버튼 눌러 메인페이지로 되돌아옴)
    - 한타/영타 선택 후 맨 아래 단어편집 버튼 눌러 단어 추가

2. 게임 페이지
    - 상단엔 플레이어 정보 확인
    - 난이도 별로 단어가 생성되는 속도와 떨어지는 속도 다름
    - 단어 틀릴때마다 떨어지는 속도 점점 빨라짐
    - 단어 틀릴때마다 점수 -10
    - 단어 맞추면 점수 +10
    - 단어가 바닥으로 떨어지면 생명 -1
    - 생명이 0이되면 게임 종료 (게임종료 / 다시시작 선택)

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/67352902/103322049-e9475400-4a7f-11eb-8329-a114a0b43de4.gif)
