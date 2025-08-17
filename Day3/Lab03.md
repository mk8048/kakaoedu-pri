# 성별 예측



## 1. Joined 테이블 생성
1. Notebooks 탭 > `cpu-notebook`의 `CONNECT` 클릭
2. Other 중 `Terminal` 클릭
3. kubectl.ipynb 파일 다운로드
   #### **Lab5-2-5**
   ```bash
   wget https://raw.githubusercontent.com/kakaocloud-edu/tutorial/main/DataAnalyzeCourse/src/day3/ipynb/kubectl.ipynb
   ```
   - kubectl.ipynb 파일 생성 확인 및 더블 클릭 후 내부 코드 실행

## 2. 성별 예측 실습
1. speed.ipynb 파일 다운로드
   - **Note**: 위에서 생성한 Notebook(`cpu-notebook`)에서 입력

   #### **lab4-3-6**
   ```bash
   wget https://raw.githubusercontent.com/kakaocloud-edu/tutorial/main/DataAnalyzeCourse/src/day3/ipynb/speed.ipynb
   ```
   - speed.ipynb 파일 생성 확인 및 더블 클릭 후 내부 코드 실행

2. speed 생성 확인

## 4. Notebook에서 Object Storage에 쌓인 데이터 확인
1. data_check.ipynb 파일 다운로드
   - **Note**: 위에서 생성한 Notebook(`cpu-notebook`)에서 입력

   #### **lab4-3-6**
   ```bash
   wget https://raw.githubusercontent.com/kakaocloud-edu/tutorial/main/DataAnalyzeCourse/src/day3/ipynb/data_check.ipynb
   ```

   - kubectl.ipynb 파일 생성 확인 및 더블 클릭 후 내부 코드 실행

2. data 생성 확인

## 5. Notebook에서 전처리 진행
1. preprocessed_user_behavior_prediction.ipynb 파일 다운로드
   - **Note**: 위에서 생성한 Notebook(`cpu-notebook`)에서 입력

   #### **lab4-3-6**
   ```bash
   wget https://raw.githubusercontent.com/kakaocloud-edu/tutorial/main/DataAnalyzeCourse/src/day3/ipynb/preprocessed_user_behavior_prediction.ipynb
   ```

   - preprocessed_user_behavior_prediction.ipynb 파일 생성 확인 및 더블 클릭 후 내부 코드 실행

2. processed_user_behavior.csv 확인
3. 카카오 클라우드 콘솔 > Beyond Storage Service > Object Storage
4. data-catalog-bucket 클릭
5. preprocessed_user_behavior_prediction.parquet 적재 확인
    - **Note**: /data-catalog-dir/preprocessed/preprocessed_user_behavior_prediction.parquet 확인
