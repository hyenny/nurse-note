# UC014 - 플러스노트 자동추천

회원이 플러스노트 자동추천글을 조회하는 유스케이스

## 주 액터(Primarty Actor)
회원


## 보조 액터(Secondary Actor)

## 사전 조건(Preconditions)
- 로그인한 상태이다.


## 종료 조건(Postconditions)


## 시나리오(Flow of Events)

### 기본 흐름(Basic Flows of Events)
1. 액터는 플러스노트 메뉴를 클릭한다.
2. 시스템은 플러스노트 목록을 출력한다.
3. 액터는 상세조회할 노트를 클릭한다.
4. 시스템은 플러스노트 상세 정보(글, 베스트댓글, 댓글 목록 자동추천글)를 출력한다.
  - 자동추천글 : 플러스노트의 분류 키워드를 포함하고 있는 다른 플러스노트 게시물을 검색하여 이를 출력한다.