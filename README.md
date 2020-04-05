# machine-learning

이 repository는 파이썬 머신러닝 완벽 가이드 책을 보고 스스로 정리한 파일들을 올려놓은 것입니다. 

# 새롭게 알게 된 사실

1.  
 고정된 학습 데이터로 학습을 하다보니 실제 테스트 데이터를 적용할 경우 예측 성능이 과도하게 많이 떨어진다는 사실과,  
의도치 않게 학습 데이터에만 편향되게 모델이 유도된다는 사실을 알게 되었고, 이를 해결하기 위하여 교차 검증이라는 방법에 대해 공부했다.  

2.  
레이블 인코딩의 문제점  
 숫자 값의 경우 크고 작음에 대하여 특성이 적용되기 때문에 예를 들어 레이블의 값이 0,1,2 이렇게 있을 때 2가 더 큰 숫자이므로 가중치가 부여되어서 더 중요하게 인식할 가능성이 있다. 단순 코드이지 숫자 값에 따른 순서나 중요도로 인식되어서는 안 된다. 레이블 인코딩은 선형 회귀와 같은 머신러닝 알고리즘에는 적용하지 않아야 하며, 트리 계열의 머신러닝 알고리즘은 숫자의 이러한 특성을 반영하지 않기 때문에 레이블 인코딩도 별 문제가 없다.
