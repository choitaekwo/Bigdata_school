# 빅데이터 과제 에러

과제: 원본 데이터를 수정하여 "업체별 승차 횟수" 구하기
--

1. pyspark를 설치했으나 jupyter lab 에서 spark 를 찾지 못하는 문제 발생.
  
      <img src = "C:\Users\midst\Desktop\No_module_pyspark.png" width = 200 height = 100>
      
--Solution: findspark 라는 라이브러리를 불러와서 pyspark를 찾게 한다.

      !(C:\Users\midst\Desktop\find pyspark.png raw = true)
      
2. 원인 파악 불가.

      <img src = "C:\Users\midst\Desktop\data_parsing_error.png" width = 400 height = 400>
      
--Solution: 해당 셀 한 번 더 실행하니까 잘 됨.

      <img src = "C:\Users\midst\Desktop\data_parsing_error_solve.png">
      
----
그 외에 syntax 에러를 제외하고는 정상적으로 동작하였음.
