# 지하철 노선도 경로 조회 미션 (박준형)

<br>

## 프로그램 설명
- 등록된 지하철 노선도에서 경로를 조회하는 프로그램이다.

<br>

## 기능 목록

### 초기 설정
 1. 지하철역으로 교대역, 강남역, 역삼역, 남부터미널역, 양재역, 양재시민의숲역, 매봉역이 등록되어 있다.
 2. 지하철 노선으로 2호선, 3호선, 신분당선이 등록되어 있다.
 3. 노선에 역이 아래와 같이 등록되어 있다.(왼쪽 끝이 상행 종점)
     - 2호선: 교대역 - ( 2km / 3분 ) - 강남역 - ( 2km / 3분 ) - 역삼역
     - 3호선: 교대역 - ( 3km / 2분 ) - 남부터미널역 - ( 6km / 5분 ) - 양재역 - ( 1km / 1분 ) - 매봉역
     - 신분당선: 강남역 - ( 2km / 8분 ) - 양재역 - ( 10km / 3분 ) - 양재시민의숲역

### 경로 조회 기능
- 최단 거리, 최소 시간 조회가 가능하다.
- 역, 노선 그리고 구간이 필요하다.
- 구간에는 출발역, 도착역, 거리, 시간이 필요하다.
- 출발역을 입력 받아야 한다.
- 도착역을 입력 받아야 한다.
- 총 거리, 총 소요 시간을 출력 해야 한다.
- 출발역과 도착역 사이를 출력 해야 한다.


### 예외 상황
- 경로 조회 시 출발역과 도착역이 같으면 에러를 출력한다.
- 경로 조회 시 출발역과 도착역이 연결되어 있지 않으면 에러를 출력한다.
- 출발역과 도착역의 이름이 존재하지 않으면 에러를 출력한다.
- 그 외 정상적으로 프로그램이 수행되지 않은 경우 에러를 출력한다.
