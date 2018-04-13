recommendMovie
==============

Spark ml의 ALS 알고리즘을 활용한 영화 추천 모델 구축

  데이터
  ------
  * ratings(userID, movieID, rating(1 to 5))
  * movies(movieID, title)

  0.분석 환경
  ----------
        1-1 하둡 클러스터(의사 분산모드)
         > version:2.9.0
         > master: yarn-client
         > memory: 11GB
        1-2 spark
         > version: 2.2.0
        1-3 zeppelin
         > version: 0.7.3
  
  1.분석 방법
  ----------
   * 1-1 EDA 작업
   * 1-2 ALS (Alternatings Least Squares) 적용
   * 1-3 결과 확인
  
  
  2.코드 및 분석 결과 보기
  -----------------------
  
  1. [데이터 확인 및 EDA](https://www.zepl.com/UHMK7RFW2/spaces/SSJ7TIOG5/c84d738292964b0e90bb688f0e028348)
  2. [LSA 모델 적용 및 평가](https://www.zepl.com/UHMK7RFW2/spaces/SSJ7TIOG5/033cdeb7fb074ada81b65aa5611afc2b)
  
