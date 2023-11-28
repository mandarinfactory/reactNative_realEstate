# reactNative_realEstate(집순위)

## 🖥️ 프로젝트 소개
React Native(expo)를 기반으로 공공데이터API(국토교통부_아파트매매 실거래 상세 자료, 기상청_단기예보 ((구)_동네예보) 조회서비스)를 이용해서 지역 기반 아파트 실거래가 및 날씨를 확인할 수 있는 앱을 만들었습니다.

## 🧭 웹사이트

## 🕰️ 개발 기간
- 23.09월 - 23.11월

## ⚙️ 개발환경
- 바닐라JS
- React Native
- tailwind CSS
- expo

## ⚙️ 사용API
- 국토교통부_아파트매매 실거래 상세 자료(https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15057511)
- 기상청_단기예보 ((구)_동네예보(https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15084084)

## 📌주요 기능
### 메뉴클릭시, 상점리스트 및 지도에 마커생성 - <a href="https://github.com/mandarinfactory/react_myLocalMap/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%EB%A9%94%EB%89%B4%ED%81%B4%EB%A6%AD%EC%8B%9C,-%EC%83%81%EC%A0%90%EB%A6%AC%EC%8A%A4%ED%8A%B8-%EB%B0%8F-%EC%A7%80%EB%8F%84%EC%97%90-%EB%A7%88%EC%BB%A4%EC%83%9D%EC%84%B1)">위키</a>
- 메뉴클릭시, 해당 상가분류에 따라 상가리스트를 데이터로 받게 했습니다.
- 해당 데이터를 이용해서 오른쪽에 상점리스트, 지도에는 마커를 생성시키게 구현했습니다.
- 각각 상점리스트나 마커를 클릭하면 해당 상점의 마커를 지도의 가운데로 이동시키게 구현했습니다.
- 또한, 클릭시 상세정보들이 추가적으로 나오게 modal창을 구현했습니다.
- 해당 modal창에서의 사진들은 메뉴별로 하드코딩으로 넣었습니다.
- 상가데이터는 공공데이터API를 이용했으며, 지도는 네이버지도 API를 이용했습니다.

### 도시검색시 구글API를 이용해 이동하게 구현 - <a href="https://github.com/mandarinfactory/react_myLocalMap/wiki/%EC%A3%BC%EC%9A%94%EA%B8%B0%EB%8A%A5(%EB%8F%84%EC%8B%9C%EA%B2%80%EC%83%89%EC%8B%9C-%EA%B5%AC%EA%B8%80API%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%B4-%EC%9D%B4%EB%8F%99%ED%95%98%EA%B2%8C-%EA%B5%AC%ED%98%84)">위키</a>
- input란에 한국 도시만 검색하게 제한을 두고 검색시 아래 연관 검색어로 나오게 구현했습니다.
- 관련 검색어내 원하는곳을 클릭시, 경/위도를 데이터로 가져와 네이버지도에서 이동하게끔 구현했습니다.
