
# Paired Question

## Data description

kor_Pair_test.csv
kor_pair_train.csv

train  6,888 개
test 688개           

label               
같은 질문 0               
다른 질문 1                 
                       
## ![Quick peek](./data.png)

## Fix

- csv 리더 사용시 데이터 로딩 에러를 교정하기 위해 tsv로 저장하고 에러 데이터에 대한 교정 수행
- 파일명 통일
- dos2unix 수행

kor_pair_test.tsv
kor_pair_train.tsv
