# - PORTFOLIO -
---
## portfolio 1. 데이터 직군 채용 공고 추천시스템
### 1. 프로젝트 개요
> 1.1 프로젝트 주제
> * 데이터 직군 구직자를 위한 채용 공고 추천 웹 어플리케이션 제작
> * 데이터 직군 구직자 개개인의 특성에 맞는 맞춤형 추천

> 1.2 프로젝트 구현 내용
> * 웹 페이지를 통해 사용자로부터 직군, 경력, 기술스택, 업무경험 등의 정보 입력
> * 입력된 정보를 바탕으로 채용 사이트의 공고 내용과 비교
> * TF-IDF 분석과 KNN, Cosine 유사도 분석을 통해 최적 채용 공고 추천

> 1.3 개발 환경
> * FLASK, heroku, bootstrap, vscode, PostgreSQL, colab, sklearn, pandas

### 2. 프로젝트 구조
> 2.1 프로젝트 절차

<img src="/etc/img/pf1_project_flow.png" width="70%" height="70%"></img><br/>
> 2.2 데이터 파이프라인

<img src="/etc/img/pf1_pipeline.png" width="70%" height="70%"></img><br/>

### 3. 데이터셋
> * 출처: 채용사이트 'wanted' Web API
> * 데이터수: 약 1,000여 채용공고
> * feature: 기술스택, 직군명, 자격요건, 주요업무, 우대사항, 회사명, 로고이미지, 채용공고 웹페이지, 경력사항

### 4. 분석 기법
> 4.1 TF-IDF (Term Frequency - Inverse Document Frequency)
> * 문서 집합에서 한 단어가 얼마나 중요한지를 수치적으로 나타낸 가중치
> * 한 문서에서 단어가 등장하는 빈도가 높을수록 커지고, 해당 단어를 포함하는 문서가 많을수록 반비례하여 작아진다.

<img src="/etc/img/tfidf.png" width="40%" height="40%"></img><br/>
> 4.2 KNN (K-Nearest Neighbor) 알고리즘
> * 거리 기반 분류분석 머신러닝 알고리즘
> * 새로운 데이터를 입력 받았을 때 이 데이터와 가장 근접한 데이터들의 종류가 무엇인지 확인 및 분류

<img src="/etc/img/knn.png" width="40%" height="40%"></img><br/>
> 4.3 코사인 유사도 (Cosine Similarity)
> * 두 벡터 간의 코사인 각도를 이용하여 구할 수 있는 두 벡터의 유사도
> * 문서 단어 행렬이나 TF-IDF 행렬을 통해서 문서의 유사도를 구하는 경우 각각의 특징 벡터를 이용하여 연산

<img src="/etc/img/cosine.png" width="70%" height="70%"></img><br/>
### 5. 웹 어플리케이션 구현
> * 웹페이지 접속 주소: https://cp1-datajob.herokuapp.com/
---
## portfolio 2.
---
