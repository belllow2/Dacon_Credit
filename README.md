# Dacon_Credit Project
신용카드 사용자 연체 예측 AI 경진대회 \

# EDA
## 교육(Edu_type)
* 초졸, 중졸, 고중퇴, 고졸, 대졸 5개 범주 (항목 -> 범주로 변환)
## 직업
* Job에서 결측치 8171개 존재 -> DAYS_EMPLOYED 참조
* DAYS_EMPLOYED(일하지 않은 기간)이 양수면 'No Job' 변수 파생
* DAYS_EMPLOYED(일하지 않은 기간)이 음수면 'etc' 변수 파생
# Y_Data
## 신용등급
* 사용자의 신용카드 대금 연체를 기준으로 한 신용도

# 학습 모델
## XgBoost(K-Fold=5)

# Acknowledgements

https://www.dacon.io/competitions/official/235713/overview/description
