## 1차 변수 필터링
1) EDA를 통한 변수와 타겟과의 관계 파악 - customized describe 테이블, 상관관계, 시각화(histogram, boxplot)
2) DATA Leakage(시간 순서 위배, 타겟에 정보 제공) 변수들 삭제
3) 가설을 통한 데이터 파악 후 논리적으로 어긋나는 행 삭제

## 2차 변수 필터링
1) Information Value 추출 후 정렬
2) SelectKBest 추출 후 정렬
3) 기본 모델링 후 SHAP를 통해 변수 기여도 파악
