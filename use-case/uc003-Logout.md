# UC003 - 로그아웃(Logout)
회원이 시스템을 종료하기 위해 로그아웃하는 유스케이스

## 주 액터(Primarty Actor)
회원

## 보조 액터(Secondary Actor)

## 사전 조건(Preconditions)
- 로그인한 상태이다. 

## 종료 조건(Postconditions)
- 로그아웃

## 시나리오(Flow of Events)

### 기본 흐름(Basic Flows of Events)
1. 액터가 로그아웃 버튼을 클릭할 때 이 유스케이스를 시작한다.
2. 시스템은 '정말로 로그아웃하시겠습니까?' 확인하는 내용을 출력한다. 
    - 확인 버튼을 누르면, 시스템은 로그아웃한 후 '메인' 유스케이스로 간다.
    - 취소 버튼을 누르면 확인 창이 닫힌다. 



### 예외 흐름(Exception Flows)
- 1.1. 로그아웃 버튼을 누르지 않더라도 1시간이 지나면 자동으로 로그아웃 처리된다. 


