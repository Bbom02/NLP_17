# NLP_17
2020-1 COSE461 자연어처리 텀 프로젝트 제출용 README.md 

### Task

- 첫 번째 과제: 한국어 데이터에 대한 binary classification
- 두 번째 과제: 영어 데이터셋에 대한 multi-class classification

### 출처

- 첫 번째 과제: http://aidev.co.kr/chatbotdeeplearning/8709
- 두 번째 과제: https://github.com/yashsharan/Multi-Class-sentiment-analysis
                https://github.com/Nirvan101/Sentiment-Analysis-

### 실행 방법

1) 구글 콜랩에서 /content/drive/My Drive/Colab Notebooks안에 ipynb 실행 파일을 위치시킨다.
2) 실행 파일과 같은 경로에 깃헙에 업로드한 data 폴더를 업로드 한다.
3) 드라이브 마운트를 실행하고, 런타임 유형 변경에서 하드웨어 가속기로 GPU를 설정한다.
4) shift + enter로 하나의 셀 씩 실행한다. (첫 번째 과제는 구글 콜랩 프로를 사용했다.)

### 데이터 경로에 대한 설명

- 사전에 주어진 데이터는 (ratings.txt, ratings_train.txt, ratings_test.txt, friends_dev.json, friends_test.json, friends_train.json가 해당) 모두 data 폴더에 있다. 
- 테스트 없이 학습 이후 바로 예측 데이터를 이용하여 sample.csv를 출력하게 된 multi-class classification을 수행하기 위해 사전에 friends_dev.json, friends_test.json, friends_train.json를 concat한 friends.csv를 같은 경로에 준비했다. 
- 또한 테스트 데이터로 첫 번째 과제는 주어진 ko_data와 ko_sample을 모두 사용했으나, 두 번째 과제는 Id는 인덱스를 이용하여 만들었기 때문에 en_data만 사용했다. 
