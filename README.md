# Linear Regression

## 1. 개발목적
Linear Regression을 공부하고 이를 실제로 구현 해보기위한 학습적 목적으로 개발했음.

## 2. 설명
데이터셋은 잘 알려져있는 켈리포니아 집값 예측을 위한 데이터셋을 이용했으며
이 데이터의 특성은 'longitude'	'latitude'	'housing_median_age'	'total_rooms'	'total_bedrooms'	'population'	'households'	'median_income' 'median_house_value'으로
구성되어있음. 이 특성 중 'median_house_value' 특성을 예측하는 모델을 구현했음.

## 3. 문제점
2021/07/20 프로그래밍 후 작동까지 아무 이상 없었지만 train score와 test score가 많이 낮은 것으로 보아 과소적합이 발생한 것으로 추정됨. 이를 해결하기 위해 특성들끼리의 관계와 데이터값과 모델예측값의 관계를 알아보며 개선해나가고 있지만 많은 진전이 없음. 추후 개선예정

2021/07/21 다시 한번 소스코드를 읽고 문제점을 파악해본 결과, 선형회귀라는 알고리즘 자체에는 문제가 없으며 데이터를 분석하고 추출하고 사용하는 부분이 많이 부족하다는 것을 느꼈음. 이 부분을 지금 당장 개선하기보다는, 개발목적에 따라 선형회귀모델을 구현하는데 성공했으니 문제점에 대해서는 차근차근 공부해나가며 데이터 관련 지식을 배운 후 개선할 예정임.
