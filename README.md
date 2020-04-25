# MLB-Prediction

MLB 선수들의 성적 및 개인 정보를 기반으로 적정한 FA 금액 예측

<br>

### Goal

- 예측 모델을 통해 2019년 12월에 시작되는 메이저리그 FA 시장에서 선수들의 계약 금액 예측

  <br>

1. 스탯, 급여 데이터 수집 및 정리
2. 스탯 데이터에 따른 급여 예측 모델링 구현
3. 2019년 12월 메이저리그 선수들의 FA 급여 예측

<br>

### Data Used

- https://www.mlb.com/
  - 기본 선수 정보 및 복합 스탯에 대한 설명
- https://www.baseball-reference.com/
  - 선수 연도별 기록 및 세부 스탯
- https://www.espn.com/
  - 선수 이적 정보
- https://www.spotrac.com/
  - 선수 연봉 및 계약 정보

<br>

### Tech/Framework Used

- Crawing
  - BeautifulSoup
- Machine & Deep Learning
  - Simple Linear Regression
  - PCA Analysis
  - Neural Network
  - Random Forest 