# 1. AI의 이해
•  인공지능(Artificial Intelligence): 인간의 지적능력(추론, 인지)을 컴퓨터로 구현하는 모든 기술.

•  머신러닝(Machine Learning): 알고리즘으로 데이터를 분석·학습하여 판단이나 예측을 하는 기술.

•  딥러닝(Deep Learning): 인간의 뉴런과 비슷한 인공신경망 알고리즘을 활용하여 정보를 학습하고 처리하는 기술(머신러닝 일종).

•  알고리즘(Algorithm): 연산의 반복을 포함하는 정해진 단계에서 수학적 문제를 해결하는 절차, 문제를 해결하거나 어떤 목적을 달성하기 위한 단계별 절차를 의미하기도 함.

•  지도학습(Supervised Learning): 문제와 정답을 알려주고 학습시키는 방법.

•  분류(Classification) 모델: 결괏값이 명확하게 나눠진 범주형 타입인 데이터를 예측하는 모델. 예를 들어 귤, 사과 이미지를 학습한 후 귤과 사과로 범주를 명확히 구분하여 예측.

•  회귀(Regression) 모델: 결괏값이 수치형인 데이터를 예측하는 모델.

•  비지도학습(Unsupervised Learning): 정답이 정해지지 않은 데이터를 처리하여, 데이터 간의 관계나 유사성을 발굴하는 학습 방법.

•  군집화(Clustering): 데이터 자체가 가진 특성과 상관관계를 기계가 스스로 학습하여 유사한 데이터끼리 그룹화하는 비지도학습 기법.

•  강화학습(Reinforcement Learning): 상(Reward)과 벌(Penalty)을 통해 정답을 도출할 가능성이 큰 방향으로 스스로 개선하도록 만드는 학습 방법.

•  자연어 처리(Natural Language Processing, NLP): 인간의 언어를 기계가 표현하도록 하는 기술.

•  컴퓨터 비전(Computer Vision): 영상인식 처리와 관련된 기술.

# 02. AI 구현 프로세스
## 1) 문제 정의

•  정형 데이터(Structured Data): 행과 열의 정형화된 구조로 고정된 필드에 저장되며 값과 형식이 일관된 데이터(관계형 데이터베이스, 엑셀 등).

•  반정형 데이터(Semi-structured Data): 구조와 형태를 가지나, 값과 형식에 일관성을 갖고 있지 않은 데이터(로그, 스크립트 등).

•  비정형 데이터(Unstructured Data) : 구조와 형태가 정해지지 않으며 고정된 필드에 저장되지 않은 데이터(텍스트,이미지, 오디오, 비디오 등).



## 2) 데이터 수집

•  크롤링(Crawling): 다양한 웹사이트에서 뉴스, 게시판 등의 웹 문서와 콘텐츠 수집.

•  깨끗한 데이터: ‘이상치’가 없고 ‘결측치(Missing Values)’가 없는 데이터.

•  데이터 편향: 수집된 데이터의 불균형이 일어나 특정값으로 치우친 것.

•  데이터 결측치: 손실되고 비어 있는 값.

## 3) 데이터 분석 및 전처리
•  수치형 데이터(Numerical Data): 숫자로 구성된 데이터. 연속형 데이터와 이산형 데이터로 구분.

•  문자형 데이터(Object Data): 문자로만 이루어지거나 문자와 숫자로 구성된 데이터.

•  범주형 데이터(Categorical Data): 범주를 나눌 수 있는 데이터. 순서를 매길 수 있는 순서형(Ordinal) 데이터(예: 1등급, 2등급 등)와 순서를 매길 수 없는 명목형(Nominal) 데이터(예: 남녀 등)로 구분.

•  불리언형(Boolean) 데이터: 논리값인 참과 거짓 중 하나로 표현되는 데이터.

•  개수(Counts): 데이터 개수.

•  평균값(Mean): 각 데이터를 모두 더한 후 데이터 개수로 나눈 값. 산술평균을 의미.

•  중앙값(Median): 데이터를 크기 순서대로 배열했을 때 중앙에 위치하는 값.

•  최빈값(Mode): 데이터 중 빈도수가 가장 큰 값.

•  최솟값(Minimum): 데이터 중 가장 작은 값.

•  최댓값(Maximum): 데이터 중 가장 큰 값.

•  분산(Variance): 데이터가 평균으로부터 얼마나 떨어져 있는지 정도를 나타내는 값. 각 관측치에서 평균을 뺀 차이값의 제곱의 평균임.

•  표준편차(Standard Deviation): 데이터가 평균으로부터 떨어진 정도를 나타내며 분산의 제곱근.

•  사분위수(Quartile): 모든 데이터를 순서대로 배열했을 때 4등분한 지점에 있는 값.

•  첨도(Kurtosis): 데이터 분포가 정규분포 대비 뾰족한 정도를 나타내는 값.

•  왜도(Skewness): 데이터 분포가 정규분포 대비 비대칭한 정도를 나타내는 값.

•  데이터 전처리(Data Preprocessing): 주어진 데이터를 깨끗하게 만들어주는 결측값 처리, 이상치 처리 등 데이터 정제(Data Cleaning) 과정.

•  데이터 시각화(Data Visualization): 데이터 분석결과를 쉽게 이해할 수 있도록 시각적으로 표현하고 전달하는 과정.

•  히스토그램(Histogram): 수치형 데이터의 구간별 빈도수를 나타낸 시각화 기법.

•  분포차트(Density Plot): 히스토그램과 마찬가지로 수치형 데이터의 구간별 빈도수를 나타내는 시각화 기법이나, 추가로 범주형 데이터 속성을 반영하여 각 클래스가 해당 구간 내에 얼마만큼 빈도를 차지하는지 보여줌.

•  박스차트(Boxplot): 수치형 데이터의 통계 정보를 기반으로 그 분포를 박스모양으로 나타낸 시각화 기법. 데이터의 분포와 이상치 등 통계적 특성을 한눈에 파악 가능.

•  카운트플롯(Countplot): 막대그래프, 범주형 데이터에 대한 값의 개수를 보여 줌.

•  산점도(Scatterplot): 두 수치형 데이터 사이의 관계를 보여주는 시각화 기법. 좌표평면 상의 점으로 두 수치형 데이터의 위치를 표시함으로써 상관관계 표현.

•  히트맵(Heatmap): 두 수치형 데이터 사이의 관계를 보여주는 시각화 기법, 색상을 활용하여 두 데이터 간의 상관관계 표현.

•  결측치(Missing Value): 비어 있는 데이터이며, 해당 행(Row)이나 칼럼(Clolumn)을 제거하거나 값 채우기/대체하기 등 추가 처리가 필요.

•  이상치(Outlier): 전체 데이터의 추세·패턴 등에서 벗어난 값을 가진 데이터.

•  인코딩(Encoding): 사람이 인지할 수 있는 형태(ex : 문자형)의 데이터를 컴퓨터가 이해할 수 있는 형태로 변환.

•  오디널인코딩(Ordinal Encoding): 데이터 간에 순서가 있는 카테고리 데이터에 적용.

•  원핫인코딩(One-Hot Encoding): 1과 0으로만 범주형 데이터를 표현하는 인코딩 기법, 타깃값은 1이고 나머지는 모두 0인 배열로 만듦.

•  스케일링(Scaling): 변수 간 비교를 위해 수치 간 단위를 맞추려고 수치의 크기를 변경하는 것, 대표적인 스케일링 기법으로 Min-Max Scaling, Standard Scaling이 있음.

•  Min-Max Scaling: 값을 0과 1 사이로 축소해 비율의 값을 갖게 됨(가장 작은 값은 0, 가장 큰 값은 1).

•  Standard Scaling: 평균과 표준편차를 이용하여 스케일링하는 기법.

## 4) AI 모델링
•  모델학습: 손실 함수(Loss function)를 최소화하는 방향으로 AI 알고리즘 내에 있는 가중치(Weight)를 계속 업데이트하는 과정.

•  훈련 데이터(Train Data): 실제 AI 모델학습에 사용할 데이터.

•  검증 데이터(Valid Data): 학습결과 중간 검증을 위한 데이터.

•  평가 데이터(Test Data): 최종 성능평가용으로 사용할 데이터.

•  과대적합(Over Fitting): 학습을 너무 많이 진행해서 학습 데이터의 특성에만 맞춰 학습한 상태. 학습 데이터에 대해서는 성능이 잘 나오지만, 검증 데이터나 테스트 데이터의 성능이 잘 나오지 않는 경우.

•  과소적합(Under Fitting): 학습을 너무 적게 진행한 상태.

•  하이퍼 파라미터(Hyper Parameter): 머신러닝 모델이 학습할 수 없고 사람이 지정하는 파라미터.

•  에폭(Epoch): 전체 데이터 샘플을 학습하는 횟수, 훈련 데이터(Train Data) 전체를 몇 번 반복해서 학습할지 정하는 파라미터.

•  배치 사이즈(Batch Size): 1회 파라미터 업데이트를 위해 학습하는 샘플. 하나의 Epoch 시 메모리 한계와 속도 저하를 막기 위해 전체 데이터를 쪼개서 학습하는데, 쪼개진 데이터를 Batch라고 하며. 그 크기를 Batch size라고 함.

•  이터레이션(Iteration): 데이터 크기를 배치 사이즈로 나눈 횟수만큼 모델의 가중치 업데이트가 일어나는데, 이 횟수를 ‘이터레이션’이라고 부름. 예를 들어 1,000만 개의 데이터를 10,000개씩 쪼갠다면 배치 사이즈는 10,000이고 이를 1,000번 반복함. 이 반복하는 과정을 이터레이션(Iteration)이라고 부름.

•  조기종료(Early Stop): 대표적인 과대적합(Over Fitting) 방지 기법의 하나며, 지정한 학습 횟수(Epochs)에 도달하지 않았어도 조건을 충족시킨다면 학습을 종료시키는 기법.

•  드롭아웃(Drop Out): 과적합을 줄이기 위해 임의로 노드를 제거해주는 확률 수준.

•  Optimizer 함수: 딥러닝 모델의 매개변수(Weight)를 조절해서 손실 함수(예측값-실제값 차이 활용)의 값을 최저로 만드는 과정의 함수. Adam을 많이 사용.

•  Learning Rate(학습률): 경사하강법(Gradient Descent)에서 경사를 따라 최소점을 찾기 위해 반복적으로 내리막길을 내려가야 하는데, 이때 이동하는 보폭(Step size). Learning Rate는 너무 작거나 커도 안되며 적절히 설정하는 것이 중요. Learning Rate가 크면 학습의 보폭이 커서 최저점을 지나칠 가능성이 높고, Learning Rate가 작은 경우 학습 시간이 매우 오래 걸리며 최저점에 도달하지 못함.

### [회귀 모델(Regression Model) 성능평가 지표]

•  오차(Error): ‘(실제값-예측값)의 평균’이며 작을수록 좋음.

•  평균절대오차(Mean Absolute Error): ‘(실제값-예측값)의 절댓값의 평균’이며 작을수록 좋음.

•  평균제곱오차(Mean Square Error, MSE): ‘(실제값-예측값)의 제곱의 평균’이며 작을수록 좋음.

•  평균제곱근오차(Root Mean Square Error, RMSE): 평균제곱오차에 제곱근을 씌운 것이며 작을수록 좋음

•  결정계수(R2 Score, R squared): 독립변수가 종속변수를 얼마나 잘 설명하는지 나타내며, 값이 1에 가까울수록 좋음.

### [분류 모델 (Classification Model) 성능평가 지표]

•  정확도(Accuracy): 분류모델이 전체 데이터 중 몇 개나 정확하게 예측했는지 나타내는 지표.

•  정밀도(Precision): ‘내가 A라고 예측한 개수 중 내가 맞힌 A의 개수’를 나타낸 지표.

•  재현율(Recall): ‘전체 데이터 중 A의 개수 중 내가 맞힌 A의 개수’를 나타낸 지표.

•  F1스코어(F1-score): 정밀도와 재현율을 조화 평균하여 한 번에 포괄적으로 보기 위한 지표.

•  초기 모델(Baseline Model, 베이스라인 모델): 성능의 기준이 되는 모델.

•  피처 엔지니어링(Feature Engineering): 전처리된 데이터를 가공해 모델의 성능을 더 높이기 위한 작업. 문자를 숫자로 바꿔주는 ‘인코딩’, 수치형 데이터의 범위를 조절해주는 ‘스케일링’, 기존 피처(Feature)를 통해 새로운 피처를 만드는 ‘파생변수생성’ 등이 있음.

# 03. EZ로 AI 실습하기(분류)
•  타깃변수(Target Variable): 라벨 칼럼(Label Column)과 동의어.

•  라벨(Label): 예측·분석을 목적으로 하는 결과 데이터로 ‘타깃(Target), 종속변수, 출력값(Ouput), Y’ 라고도 불림.

•  피처(Feature, 특성): 입력 데이터로 ‘독립변수, 입력값(Input), X’라고도 불리며, 예측·분석하고자 하는 ‘타깃’에 영향을 미치는 요소.

•  변수(Variable): 계속 변하는 값. 특정 지어지지 않아서 하나 이상의 값을 가짐. 데이터를 저장하기 위해 프로그램에 의해 할당받은 메모리 공간을 의미하기도 함.

•  스케일링(Scaling): 변수 간의 비교를 위해 수치 간 단위를 맞추려고 수치의 크기를 변경하는 것. 대표적 스케일링 기법으로 Min-Max Scaling, Standard Scaling이 있음.

•  Min-Max Scaling: 값을 0과 1 사이로 축소해 비율의 값을 갖게 됨(가장 작은 값 0, 가장 큰 값 1).

•  Standard Scaling: 평균과 표준편차를 이용하여 스케일링하는 기법.

•  인코딩(Encoding): 사람이 인지할 수 있는 형태(ex : 문자형)의 데이터를 컴퓨터가 이해할 수 있는 형태로 변환.

•  라벨 인코딩(Label Encoding): 범주형 데이터의 n개 종류의 값들을 0에서부터 n-1값으로 단순히 연속적인 숫자를 부여. 범주형 데이터 중 순서형 데이터에 적합.

•  오디널 인코딩(Ordinal Encoding): 데이터 간에 순서가 있는 카테고리에 적용.

•  원핫 인코딩(One-hot Encoding): 1과 0으로만 범주형 데이터를 표현하는 인코딩 기법. (타깃값은 1이고 나머지는 모두 0인 배열로 만듦).

•  소프맥스 함수(Softmax Function): 다중 클래스 분류에 사용. Input값이 여러 개인 경우, 여러 개의 선형방정식의 출력값을 0~1 사이로 정규화하여 전체 합이 1이 되도록 하는 함수.

•  시그모이드 함수(Sigmoid Function): Input값이 1개인 경우, 선형방정식의 출력을 0과 1 사이의 값으로 하여 이진 분류를 위해 사용. 출력이 0.5보다 크면 양성클래스이고 0.5보다 작으면 음성클래스로 판단.

•  Sparse: 원핫 인코딩에서 타깃값은 1이고 나머지는 0으로만 표현하는데, 이처럼 대부분 0으로 표현하는 방법을 Sparse Vector(벡터)라고 부름. AIDU ez에서 원핫 인코딩은 데이터 인코더를 sparse로 설정해야 함. ※ Sparse : (밀도가)희박한

예)사과=[0, 0, 1, 0, 0]처럼 표현.

•  Dense: 변수들의 값을 0과 1 외에도 실숫값으로 표현하는 벡터. 벡터의 차원이 조밀해 졌다고 dense vector라고 함. ※ Dense: 밀집한

예)공책=[0.2, 1.5, -2.4, 1.6, 1.1]처럼 표현.

•  교차 검증: 훈련(Train) 데이터와 평가(Test) 데이터를 K번(fold 수) 변경하고 학습 및 평가하여 모델을 검증하는 방법. K가지의 훈련·평가 데이터셋을 사용하여 모델을 학습·평가하고 해당 결과의 평균과 표준편차 등을 확인하여 일반화된 모델 여부를 검증.

·장점: 모델의 신뢰성 향상, 특정 데이터셋에 대한 과대적합 방지 등.

·단점: 모델 훈련과 평가 소요 시간 증가.

# 04. EZ로 AI 실습하기(회귀)

•  ReLU 함수(Rectified Linear Unit): 입력값이 0보다 작으면 0으로 출력, 0보다 크면 입력값 그대로 출력하는 함수. 가장 많이 사용되는 활성화 함수(Activation Function).

•  FC 레이어(Fully Connected Layer): 심층신경망(DNN)의 계층 중 각각의 뉴런은 직전 계층과 직후 계층에 있는 모든 뉴런과 상호 연결되어 있는데, 이를 Fully Connected Layer라고 표현.

•  FC 레이어 수: 딥러닝 모델의 FC 레이어 수를 뜻함.

•  FC 레이어 크기: 각 FC 레이어를 구성하는 노드(Node) 수를 뜻함.

•  드룹아웃(Drop out): 모델의 과적합(Overfitting)을 줄이기 위해 레이어 내의 노드를 임의로 제거해주는 확률을 설정하는 값.

# 05. 머신러닝

•  머신러닝(Machine Learning) 학습방법: 지도학습(분류, 회귀), 비지도학습(군집화), 강화학습(상벌을 통해 학습)이 있음.

•  단순 선형 회귀(Simple Linear Regression): 독립변수(피처)와 종속변수(라벨, 타깃변수)를 각각 하나씩 가지는 선형 회귀. 1차함수 형태(y=ax+b)와 유사. 단순 선형 회귀 모델에서 학습이란 데이터를 활용하여 독립변수로 종속변수를 가장 잘 예측하는 절편과 기울기를 찾는 과정이라고 할 수 있음.

•  목적 함수(Objective Function): 머신러닝 학습과정에서 최적화된 모델을 정의하는데 기준이 되는 값. 비용함수(Cost Function) 또는 손실 함수(Loss Function)라고 함.

•  경사하강법(Gradient Descent): 목적 함수가 최솟값을 갖도록 파라미터를 반복적으로 변경하는 방법. 목적 함수를 기준으로 모델을 최적화하기 위해 모델을 반복적으로 학습하여 파라미터를 찾는 방법. 손실 함수의 경사를 따라 최적의 모델을 찾는 알고리즘.

## [머신러닝 알고리즘]

•  선형 회귀(Linear Regression): 입력 데이터와 타깃(Target) 사이의 관계가 선형(직선)일 것이라고 가정하고, 그 직선을 바탕으로 새로운 입력 데이터의 타깃(Target)을 추론하는 회귀 모델. 단순 선형 회귀와 다중 선형 회귀(Multiple Linear Regression)가 있음.

예시) 시험성적≈ß1*공부시간

•  다중 선형 회귀(Multi Linear Regression): 데이터를 설명할 수 있는 여러 개의 독립변수를 이용하여 종속변수를 예측.

예시) 시험성적≈ß0+ß1*공부시간+ß2*지각 횟수

•  로지스틱 회귀(Logistic Regression): 이름은 회귀이지만 분류 문제에 사용되는 모델임. 선형방정식을 사용한 분류 알고리즘으로 선형 회귀와는 달리, 시그모이드 함수나 소프트맥스 함수의 결과 확률을 바탕으로 클래스 분류 가능.

•  시그모이드 함수(Sigmoid Function): Input값이 1개인 경우, 선형방정식의 출력을 0과 1 사이의 값으로 하여 이진 분류를 위해 사용. 출력이 0.5보다 크면 양성 클래스이고 0.5보다 작으면 음성 클래스로 판단

•  소프트맥스 함수(Softmax Function): 다중 클래스 분류에 사용. Input값이 여러 개인 경우, 여러 개의 선형방정식의 출력값을 0~1 사이로 정규화하여 전체 합이 1이 되도록 하는 함수.

•  K-최근접이웃(K-Nearest Neighbor, KNN): 가중치나 편향 파라미터 없이 새로운 데이터를 예측하기 위해 예측하려는 데이터로부터 가장 거리가 가까운 K개의 최근접 데이터를 참조하는 알고리즘. 회귀와 분류 문제에 모두 사용 가능.

•  의사결정나무(Decision Tree): 회귀와 분류 문제에 모두 사용 가능. 의사결정 규칙을 나무(Tree) 구조로 만들어 차례로 과정을 거치며 의사결정 규칙을 학습하고, 어떤 과정을 거쳐 결론을 냈는지 파악할 수 있어서 예측과정을 이해하기 쉬움.

•  랜덤 포레스트(Random Forest): 의사결정나무 모델을 가지고 배깅(Bagging)이라는 앙상블 기법을 적용한 알고리즘. 배깅은 여러 개의 단일 모델을 병렬 형태로 합친 것을 의미.

•  부스팅(Boosting): 부스팅은 여러 개의 단일 모델을 직렬 형태로 합친 것이며, 부스팅 알고리즘으로 Adaboost, Gradient Boosting, XGBoost, LightGBM 등이 있음.

# 06. 딥러닝



•  인공신경망(Artificial neural network, ANN): 뇌의 뉴런을 모방한 모델로, 입력계층, 출력계층, 은닉계층으로 구성되어 있음.

•  활성화 함수(Activation Function): 입력신호의 가중함이 분계점(Threshold)을 넘어서면 출력신호를 생성하는 함수. 입력을 출력하는 도달점을 분계점(Threshold)이라고 부름.

•  심층신경망(Deep Neural Network, DNN): 입력계층과 출력계층 사이에 은닉계층을 2개 이상 가지고 학습하는 인공신경망. 각각의 뉴런은 직전 계층과 직후 계층에 있는 모든 뉴런과 상호 연결되어 있는데, 이를 Fully Connected Layer(FC)라고 표현하기도 함.

•  가중치(Weight): 출력값과 정답값을 비교하여 오차를 최소화하기 위해 임의값을 조금씩 조정하는 파라미터.

•  역전파(Back Propagation): 실제값과 모델의 결괏값에서 구한 오차를 Output에서 Input 방향으로 보내는 것. 가중치(Weight)를 조정하면서 오차를 줄여 정답과 일치하게 하도록 딥러닝은 순전파(Forward Propagation)뿐만 아니라 역전파를 수행.

•  손실 함수(Loss Function): 신경망 학습의 목적 함수로 출력값(예측값)과 정답(실제값)의 차이를 계산. 모델의 예측 성능을 높이기 위해서는 손실이 작은 함수를 구하는 것이 중요. 손실 함수를 비용 함수(Cost Function)라고 부르기도 함.

•  합성곱신경망(Convolutional Neural Network, CNN): 합성곱 연산을 사용하는 심층신경망 모델 이미지 분류 시 주로 사용하는 모델.

•  순환신경망(Recurrent Neural Network, RNN): 시퀀스 데이터(순서가 있는 데이터)의 패턴을 인식하고 예측할 수 있는 알고리즘. 자연어 처리나 시계열 모델을 만들 때 사용됨.





