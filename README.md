# Developer_interview
개발자 인터뷰 질문 및 답변 모음집입니다.


## 1. 남세동 대표님의 보이저엑스 개발자 인터뷰 질문 모음

- 주로 개발자가 갖추어야 할 기본적인 지식에 대해서 묻고 있음

     a) 웹브라우저 URL에 www.naver.com을 치고 나서 네이버 첫페이지가 표시되기까지 일어나는 일을 본인이 알고 있는대로 최대한 상세하게 설명해 보라. 레이어를 아무리 내려가도 좋고, 설명이 아무리 길어져도 좋다. 10분 동안 해도 된다.

     b) 동시사용자 최대 100명, 채팅방1개, 텍스트만 주고 받는 것이 기능의 전부인 최소 스펙의 채팅 서버를 데모가 가능한 정도의 안정성을 확보하는 수준으로 만들어야 한다. 어떤 언어로 몇줄 정도에 어느 정도 기간에 만들 수 있는가?

     c) 디지털 시계 프로그램을 만들어야 한다. 초단위로 표시해야 한다. 어떻게 작성할 것인가? 그렇게 작성 하면 장점과 단점은 무엇인가?

     d) [전임자가 만든 어떤 프로그램이 있는데 생각보다 너무 느리게 동작하는 것 같다. 어떤 부분을 어떻게 보는 것이 좋을까?](https://github.com/RRoundTable/Developer_interview/blob/master/1-d.md)

     e) 메모리, 디스크, 네트워크의 성능과 관련되어서 알고 있는 숫자들을 모두 말해 보라.

     f) [압축이란 것은 어떻게 하는 것일까? 손실 압축과 비손실 압축의 차이는 무엇일까?](https://github.com/RRoundTable/Developer_interview/blob/master/1-f.md)

     g) [피보나치 수의 함수 f(n)을 작성하는 여러가지 방법에 대해서 떠오르는대로 모두 얘기해 보라.](https://github.com/RRoundTable/Developer_interview/blob/master/1-g.md)

     h) 데이터베이스에서 인덱스와 관련하여서 생각나는 기술적인 내용들에 대해서 모두 얘기해 보라.

     i) 어떤 처음 접하는 프로그래밍 언어로 위의 b와 같은 서버를 만들어야 한다. 빠르게 해야 하는 상황이라면 공부 시간 포함해서 얼마나 걸릴 것 같은가?

     j) 좋아하는 IDE에서 자주 사용 하는 기능들 또는 특별히 좋은 기능들에 대해서 얘기해 보라.

     k) 이 앱을 써보고 생각나는 좋은점들, 문제점들, 기술적인 부분과 기술 외적인 부분 모두를 얘기해 보라.


## 2. 남세동 대표님 : 딥러닝이라는 주제에 대해서 개발자 면접

- 1년 이하 정도 딥러닝을 열심히 해 본 개발자들이 일정 수준 이상으로 잘 대답할 것으로 기대하는 질문들이다.

딥러닝이라는 주제에 대해서 개발자 면접을 자주 하다 보니 어떤 질문을 하면 되는지 대략 정리가 되었다.

1년 이하 정도 딥러닝을 열심히 해 본 개발자들이 일정 수준 이상으로 잘 대답할 것으로 기대하는 질문들이다.

1. [요즘 Sigmoid 보다 ReLU를 많이 쓰는데 그 이유는?](https://github.com/RRoundTable/Developer_interview/blob/master/2-1.md)

- Non-Linearity라는 말의 의미와 그 필요성은?
- ReLU로 어떻게 곡선 함수를 근사하나?
- ReLU의 문제점은?
- Bias는 왜 있는걸까?

2. [Gradient Descent에 대해서 쉽게 설명한다면?](https://github.com/RRoundTable/Developer_interview/blob/master/2-2.md)

- 왜 꼭 Gradient를 써야 할까?
- 그 그래프에서 가로축과 세로축 각각은 무엇인가?
- 실제 상황에서는 그 그래프가 어떻게 그려질까?
- GD 중에 때때로 Loss가 증가하는 이유는?
- 중학생이 이해할 수 있게 더 쉽게 설명 한다면?
- Back Propagation에 대해서 쉽게 설명 한다면?

3. Local Minima 문제에도 불구하고 딥러닝이 잘 되는 이유는?

- GD가 Local Minima 문제를 피하는 방법은?
- 찾은 해가 Global Minimum인지 아닌지 알 수 있는 방법은?

4. [CNN에 대해서 아는대로 얘기하라](https://github.com/RRoundTable/Developer_interview/blob/master/2-4.md)

- CNN이 MLP보다 좋은 이유는?
- 어떤 CNN의 파라메터 개수를 계산해 본다면?
- 주어진 CNN과 똑같은 MLP를 만들 수 있나?
- 풀링시에 만약 Max를 사용한다면 그 이유는?
- 시퀀스 데이터에 CNN을 적용하는 것이 가능할까?

5. Word2Vec의 원리는?

- 그 그림에서 왼쪽 파라메터들을 임베딩으로 쓰는 이유는?
- 그 그림에서 오른쪽 파라메터들의 의미는 무엇일까?
- 남자와 여자가 가까울까? 남자와 자동차가 가까울까?
- 번역을 Unsupervised로 할 수 있을까?

6. Auto Encoder에 대해서 아는대로 얘기하라

- MNIST AE를 TF나 Keras등으로 만든다면 몇줄일까?
- MNIST에 대해서 임베딩 차원을 1로 해도 학습이 될까?
- 임베딩 차원을 늘렸을 때의 장단점은?
- AE 학습시 항상 Loss를 0으로 만들수 있을까?
- VAE는 무엇인가?

7. Training 세트와 Test 세트를 분리하는 이유는?

- Validation 세트가 따로 있는 이유는?
- Test 세트가 오염되었다는 말의 뜻은?
- Regularization이란 무엇인가?

8. Batch Normalization의 효과는?

- Dropout의 효과는?
- BN 적용해서 학습 이후 실제 사용시에 주의할 점은? 코드로는?
- GAN에서 Generator 쪽에도 BN을 적용해도 될까?

9. SGD, RMSprop, Adam에 대해서 아는대로 설명한다면?

- SGD에서 Stochastic의 의미는?
- 미니배치를 작게 할때의 장단점은?
- 모멘텀의 수식을 적어 본다면?

10. 간단한 MNIST 분류기를 MLP-CPU 버전으로 numpy로 만든다면 몇줄일까?

- 어느 정도 돌아가는 녀석을 작성하기까지 몇시간 정도 걸릴까?
- Back Propagation은 몇줄인가?
- CNN으로 바꾼다면 얼마나 추가될까?

11. 간단한 MNIST 분류기를 TF나 Keras 등으로 작성하는데 몇시간이 필요한가?

- CNN이 아닌 MLP로 해도 잘 될까?
- 마지막 레이어 부분에 대해서 설명 한다면?
- 학습은 BCE loss로 하되 상황을 MSE loss로 보고 싶다면?
- 만약 한글 (인쇄물) OCR을 만든다면 데이터 수집은 어떻게 할 수 있을까?

12. 간단한 MNIST DCGAN을 작성한다면 TF 등으로 몇줄 정도 될까?

- GAN의 Loss를 적어보면?
- D를 학습할때 G의 Weight을 고정해야 한다. 방법은?
- 학습이 잘 안될때 시도해 볼 수 있는 방법들은?

13. 딥러닝할 때 GPU를 쓰면 좋은 이유는?

- 학습 중인데 GPU를 100% 사용하지 않고 있다. 이유는?
- GPU를 두개 다 쓰고 싶다. 방법은?
- 학습시 필요한 GPU 메모리는 어떻게 계산하는가?

14. TF 또는 Keras 등을 사용할 때 디버깅 노하우는?

15. Collaborative Filtering에 대해 설명한다면?

16. AutoML이 뭐하는 걸까?

이상 공통 (기본) 질문들만 정리해 봤다.

## 3. 변성윤 님의 인터뷰 질문 모음 

- 데이터 분석가가 갖추어야할 역량에 대한 인터뷰 




### reference 
- [남세동 대표님](https://www.facebook.com/dgtgrade/posts/1630652416993618?__tn__=KH-R)
- [변성윤 님](https://zzsza.github.io/data/2018/02/17/datascience-interivew-questions/)
