# reactNative_realEstate(집순위)

## 🖥️ 프로젝트 소개
React Native(expo)를 기반으로 공공데이터API(국토교통부_아파트매매 실거래 상세 자료, 기상청_단기예보 ((구)_동네예보) 조회서비스) 및 주소기반API를 이용해서 지역 기반 아파트 실거래가 및 날씨를 확인할 수 있는 앱을 만들었습니다.

## 🧭 웹사이트

## 🕰️ 개발 기간
- 23.09월 - 23.11월

## ⚙️ 개발환경
- 바닐라JS
- React Native(expo)

## ⚙️ 사용API
- 국토교통부_아파트매매 실거래 상세 자료(https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15057511)
- 기상청_단기예보 ((구)_동네예보(https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15084084)
- 주소기반산업지원서비스(https://business.juso.go.kr/addrlink/openApi/apiExprn.do?cPath=99MA)

## 📌주요 기능
### 현재위치 날씨칸 - <a href="https://github.com/mandarinfactory/reactNative_realEstate/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%ED%98%84%EC%9E%AC%EC%9C%84%EC%B9%98-%EB%82%A0%EC%94%A8%EC%B9%B8)">위키</a>
- 공공데이터API(기상청_단기예보 ((구)_동네예보) 조회서비스)를 이용해서 현재 위치 날씨를 알려주도록 구현했습니다.
- 해당 위치를 가져와서 API에서 사용할 수 있는 library를 사용하여 위치변환을 해서 사용했습니다.
- 날씨 및 해당위치가 보이도록 구현했습니다.
  
### 시/구 검색칸 - <a href="">위키</a>
- 검색칸에 시/구를 검색하면 연관검색어로 나오게 했습니다.
- 연관검색어내 클릭시, 해당 시/구로 업데이트되서 아파트 실거래가가 변하도록 구현했습니다.
- 옆 나침반 아이콘을 클릭시, 다시 현재 위치 기반으로 돌아오게 구현했습니다.

### 현재위치(시/구 기준)아파트 실거래가 순위칸 - <a href="">위키</a>
- 공공데이터API(국토교통부_아파트매매 실거래 상세 자료)를 이용해 현재위치데이터를 추가하여 현재위치의 아파트 실거래가 데이터를 가져온 후,
  해당 데이터의 금액을 내림차순을 통해 순위별로 나오게 구현했습니다.
  
### 실거래가 순위칸을 클릭시 상세페이지로 이동 - <a href="">위키</a>
- 실거래가 순위칸을 클릭하면 상세페이지로 이동하게 구현하였습니다.
- 상세페이지는 해당 아파트에 좀 더 자세한 정보 및 지도에 해당 아파트에 마커가 나오게 구현했습니다.
