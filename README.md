# 데이터 분석 Toy프로젝트 입니다
## 분석 결과 파일은 'market_human_seoul_final.ipynb' 입니다
## 공공데이터포털 사이트에서 '소상공인시장진흥공단_상가(상권)정보_서울_202303.csv'파일과 '행정안전부_지역별(행정동) 성별 연령별 주민등록 인구수_20230430.csv'파일을 다운받아 분석했습니다
### ✅프로젝트 기간
- 📅 2023.05.17 ~ 2023.05.26
### ✅프로젝트 목적
- ✏️서울 인구수에 따른 상권의 종류를 분석하고 그 이유를 찾아내는 것이 목표
### ✅작업인원
- 1명
### 개발환경
- Python 3.8.10, 아나콘다 23.1.0, Jupyter notebook
### 가설
1. 사람이 많은 지역이 소상공인업종수가 많을 것이다.
2. 인구에 따른 상권분석
  - 인구가 가장 많은 송파구에는 음식점이 가장 많을 것이다.
  - 인구가 가장 적은 중구에는 음식이 아닌 다른 업종이 더 많을 것이다.
3. 서울의 음식점 중 한식이 가장 많을 것이다.
4. 서울 각 지역별 상권이 많은 곳은 번화가, 상업지구일 것이다.
### 시각화
- 가설 1
![image](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/f2e42ec8-f6a1-4471-a018-a285d2fd5c98)
- 가설 2
![스크린샷 2023-07-05 131934](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/3425e079-825c-4c7e-8df9-03d7eb6b2e40)
- 가설 3
![스크린샷 2023-07-05 132007](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/1569d45d-9e48-4f2a-be1a-9b8e8d80733a)
![스크린샷 2023-07-05 132027](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/3e76c037-1fc8-4f8d-b86a-14665782897c)
- 가설 4
![image](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/35c337b8-afe7-43f6-a011-602e0a3a3b20)
![image](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/b37e79a6-918e-4cf3-9e1d-8fea500a1626)
![image](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/8d7f0330-872f-4e8b-98b7-67ee7f27af04)
![image](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/398860a5-44a3-4e33-af30-4d3984503c12)
![image](https://github.com/yoon265536/dataAnalysisPrj/assets/134990199/07b233d1-7a28-4adb-a548-ad90b1e10114)
### 분석 결과
1. 서울지역 인구수는 송파구가 가장 많지만 업종수가 가장 많은 곳은 강남구다
인구수가 가장 적은 곳은 중구지만 업종수가 가장 적은 곳은 도봉구다
도봉구의 인구수가 중구에 비해 2배 이상 많음에도 불구하고, 도봉구의 업종수가 중구에 비해 2배 이상 낮다
따라서 인구수에 따른 업종 수는 서로 상관관계가 없다

2. 인구가 가장 많은 송파구는 음식이 25%로 가장 많았다
인구가 가장 적은 중구는 소매업이 33%로 가장 많았다
즉 인구수에 따른 업종의 종류는 상관관계가 있다

3. 서울 모든 지역에서 한식이 가장 많은 비율을 차지했다

4. 서울의 각 지역별 상권이 가장 많은 곳은 번화가, 상업지구이다
