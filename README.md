# 🙌 댓글 분석을 통한 유튜브 영상 평가

# 🙋‍♀️ 팀원
박현준 임성은 정유진 허윤지 이호진 김경범 이강훈 


# ❓ 프로젝트 소개
### 서비스 명 : 긍정이니 😀

### 기대 효과

유튜브 영상의 싫어요 수는 의도와는 다르게 쓰여 2021년 초부터 없어졌다. 가령, 싫어요 테러행위가 그 예시이다. 

그러나 싫어요 수 표시 기능이 없어지면서 영상의 가치를 판단할 수 없다는 문제점이 대두되었다. 

따라서 본 프로젝트의 댓글 분석을 통한 영상 호감도 평가는, 영상의 가치를 판단할 수 있는 척도가 될 것이다.


### 프로젝트 한 줄 소개
👉 구글의 BERT를 기반으로 한국어에 최적화시킨 자연어 처리 모델인 **KoBERT**를 유튜브 댓글로 학습시켰다.


### 프로젝트 진행 과정 
Selenium을 활용하여 다양한 영상들의 댓글을 크롤링했다. 가져온 모든 댓글들은 직접 호감도를 라벨링하였다. 

훈련 및 평가 모델로 Ko-BERT를 이용하였고, `batch_size`, `learning_rate`와 같은 파라미터를 조정하며 최종 서비스를 도출했다.  

완성된 서비스는 영상에 대한 시청자들의 호감도를 수치화하여 출력한다. 

| |과정|
|------|---|
|1|유튜브 댓글 크롤링을 통해 데이터 생성|
|2|이모지나 시간 표시를 삭제시키는 등의 데이터 전처리|
|3|데이터 라벨링|
|4|호감도 평가 모델 제작 및 학습|
|5|모델 평가와 시각화|

![image](https://github.com/khuda-4th/ml_toy_project_team1/assets/111333350/5f9fe1ae-3483-4dfd-8663-d99a877a90bc)






# 🚗 성능 평가
링크: https://www.youtube.com/watch?v=JOmsVop-orE

![image](https://github.com/khuda-4th/ml_toy_project_team1/assets/111333350/78387b10-86f5-4cd1-bf20-a31f620847fe)
![image](https://github.com/khuda-4th/ml_toy_project_team1/assets/111333350/3b285e89-cb88-4cf8-a069-efe710382f1b)


# 🛠 프로젝트 기간
23.08.30 - 23.09.06 