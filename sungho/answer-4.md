* 중심극한정리는 왜 유용한걸까요?  
키워드: 정규분포
짧은 답: 모집단의 모수를 기반으로 표본평균의 분포가 정규분포로 정해지기 때문에, 특정 사건이 일어날 확률을 예측할 수 있다. ??

이유: 표본의 크기가 커질수록 표본 평균의 분포는 모집단의 분포 모양과는 관계없이 정규분포에 가까워진다


* 엔트로피(entropy)에 대해 설명해주세요. 가능하면 Information Gain도요.  
키워드: 혼잡도, 
짧은 답: 엔트로피는 주어진 데이터의 혼잡도. 정보이득은 특정 속성을 선택하게됨으로써 데이터를 더 잘 구분하게 되는 것.

지식: decision algorithm에서는 엔트로피르 낮추는 방향으로 데이터의 조건을 찾는다.


* 뉴럴넷의 가장 큰 단점은 무엇인가? 이를 위해 나온 One-Shot Learning은 무엇인가?  
키워드: fine0-tuning

특정 task에만 적합하도록 fine-tuning할수밖에 없다. 이를 위해서 unseen data와 학습하지 않은 task에 대해서도 처리 가능하도록 one-shot learning이 가능한 모델이 나왔다.

one-shot learning은 모델이 테스트 데이터 x를 한번만 보고도 기존 학습 데이터의 라벨 중에서 예측값을 선택할 수 있는 것.

* 요즘 Sigmoid 보다 ReLU를 많이 쓰는데 그 이유는?  
sigmoid는 기울기가 0에 가까워지면서 gradient vanishing의 위험이 존재한다.

  * Non-Linearity라는 말의 의미와 그 필요성은?  

  비선형 함수를 통해 특정 범위 내로 뉴런의 출력을 한정짓기 위함이다. 

  * ReLU로 어떻게 곡선 함수를 근사하나?  
  0보다 작은 값에 대해서는 0으로, 0보다 같거나 크다면 곡선 함수를 그대로 출력하는 형태로 근사한다.

  * ReLU의 문제점은?  
  0보다 큰 뉴런의 출력에 대해서 값이 지나치게 비대해질 가능성이 있다.

  * Bias는 왜 있는걸까?  
  variance를 조절하는 것만으로는 모델의 출력을 조절할 수 없으므로 bias까지 조절해서 학습 데이터를 근사한다.


* 다른 좋은 머신 러닝 대비, 오래된 기법인 나이브 베이즈(naive bayes)의 장점을 옹호해보세요.  

키워드: cost
짧은 답: 간단한 분류 문제의 경우 적은 cost를 투자해도 문제 해결이 가능하다.

* 회귀 / 분류시 알맞은 metric은 무엇일까?  
키워드: MSE, MAE, confustion matrix
짧은 답: 회귀에서는 MSE, MAE.
분류에서는 confusion matrix.