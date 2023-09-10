프로젝트 팀 농스트라다무스

1. 개요
1.1 데이터 전처리
데이터 수집
결측치/이상치 파악
이상치 대체
변수간 관계 파악
파생변수 생성
1.2 모델링
목표
품목별 모델링
앙상블
결과
2. 파일구성
Data 폴더: Raw데이터 및 전처리 데이터 일체
Code 폴더: 각각 .Rmd/.ipynb
01_Preprocess.Rmd
02_Modeling_MLR.Rmd
03_Modeling_LSTM.ipynb
3. 코드실행 유의사항
데이터들을 'data' 폴더에 위치시켜 주시기 바랍니다.

4. 개발환경
4.1 로컬
CPU : Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz 2.59 GHz
RAM : 16.0GB
GPU : No GPU Computing
4.2 R
R 버전 : 4.3.1
readr: 2.1.4
readxl: 1.4.3
dplyr: 1.1.2
data.table: 1.14.8
magrittr: 2.0.3
skimr: 2.1.5
ggplot2: 3.4.2
esquisse: 1.1.2
DataExplorer: 0.8.2
lubridate: 1.9.2
stringr: 1.5.0
naniar: 1.0.0
VIM: 6.2.2
imputeTS: 3.3
fastDummies: 1.7.3
corrplot: 0.92
nortest: 1.0-4
4.3 Python
Google Colab Pro
