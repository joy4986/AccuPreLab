# 전처리 요건

1. 결측치 처리
* 결측치 존재하는 컬럼 없음

2. 불필요한 데이터 삭제 – 컬럼
* Unique 50% 넘는 컬럼 삭제 : id

3. 가변수화
* 수치형 데이터가 아닌 컬럼 : Gender, Vehicle_Age, Vehicle_Damage

4. 아웃 라이어 처리 
* Q1 – 1.5IQR 보다 작고 Q3+1.5IQR 보다 큰 아웃라이어 row 삭제

| 컬럼 | total | outlier |
|-----|------|--------|
| id  |  381109  |  0 |
| Age  |   381109 | 0 |
| Driving_License | 381109 | 812 |
| Region_Code | 381109 | 0 |
| Previously_Insured | 381109 | 0 |
| Annual_Premium | 381109 | 10320 |
| Policy_Sales_Channel | 381109 | 0 |
| Vintage | 381109 | 0 |
| Response | 381109 | 46710 |
