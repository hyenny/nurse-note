# UC004 - 개인정보 관리
회원이 개인정보를 조회하고 변경하는 유스케이스

## 주 액터(Primarty Actor)
회원

## 보조 액터(Secondary Actor)

## 사전 조건(Preconditions)
- 로그인한 상태이다.

## 종료 조건(Postconditions)
- 

## 시나리오(Flow of Events)

### 기본 흐름(Basic Flows of Events)
1. 액터가 회원정보 수정 메뉴에서 개인정보 수정 버튼을 클릭할 때 이 유스케이스를 시작한다.
2. 변경하려는 정보의 버튼을 클릭하면 한 번 더 암호 입력을 요청하는 창을 출력한다. 
3. 시스템은 올바른 암호를 입력했는지 비교한다.
        - 일치한다면 성공적으로 변경되었다는 알림 창을 출력한다.
        - 일치하지 않는다면 암호가 일치하지 않는다라는 알림 창을 출력한다.  

## UI 프로토타입
<img src="./images/personalInfo.png" width="400" height="400">

