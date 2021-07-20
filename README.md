# Linear Regression

## 1. 개발목적
Linear Regression을 공부하고 이를 실제로 구현 해보기위한 학습적 목적으로 개발했음.

## 2. 설명
데이터셋은 잘 알려져있는 켈리포니아 집값 예측을 위한 데이터셋을 이용했으며
이 데이터의 특성은 'longitude'	'latitude'	'housing_median_age'	'total_rooms'	'total_bedrooms'	'population'	'households'	'median_income' 'median_house_value'으로
구성되어있음. 이 특성 중 'median_house_value' 특성을 예측하는 모델을 구현했음.

## 3. 문제점
2021/07/20 프로그래밍 후 작동까지 아무 이상 없었지만 train score와 test score가 많이 낮은 것으로 보아 과소적합이 발생한 것으로 추정됨. 이를 해결하기 위해 특성들끼리의 관계와 데이터값과 모델예측값의 관계를 알아보며 개선해나가고 있지만 많은 진전이 없음. 추후 개선예정
