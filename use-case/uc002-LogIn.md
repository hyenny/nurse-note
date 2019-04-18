#UC002 - 로그인(LogIn)
회원이 시스템을 이용하기 위해 로그인하는 유스케이스

## 주 액터(Primarty Actor)
회원

## 보조 액터(Secondary Actor)

## 사전 조건(Preconditions)
- 회원에 가입한 상태이다. 

## 종료 조건(Postconditions)
- 입력 로그인 정보와 시스템 회원 등록 정보가 일치했다. 

## 시나리오(Flow of Events)

### 기본 흐름(Basic Flows of Events)
1. 액터가 로그인 버튼을 클릭할 때 이 유스케이스를 시작한다.
2. 시스템은 로그인 폼을 출력한다.
3. 액터는 아이디, 패스워드를 입력하고 로그인 상태 유지 여부를 체크한 후 SIGN IN 버튼을 클릭한다.
4. 시스템은 로그인 정보를 확인한 후 '메인' 유스케이스로 간다.

### 대안 흐름(Alternative Flows)
3.1. 액터가 페이스북 버튼을 클릭하면,
    - 시스템은 '페이스북으로 로그인하기' 유스케이스로 간다.
3.2. 액터가 구글 버튼을 클릭하면,
    - 시스템은 '구글로 로그인하기' 유스케이스로 간다.
3.3. 액터가 카카오 버튼을 클릭하면
    - 시스템은 '카카오 아이디로 로그인하기' 유스케이스로 간다.

### 예외 흐름(Exception Flows)
4.1. 아이디, 패스워드 입력 항목이 한 개라도 값이 비어 있으면,
    - 시스템은 필수 입력 항목이 비어 있음을 알리는 내용을 출력한다.
4.2. 아이디가 일치하지 않으면,
    - 시스템은 입력된 아이디가 일치하지 않음을 알린다.
4.3. 패스워가 일치하지 않으면,
    - 시스템은 입력된 암호가 일치하지 않음을 알린다.


