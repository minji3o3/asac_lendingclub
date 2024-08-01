# 💸대안신용평가의 가능성 - 대출상환 예측 프로젝트
> 본 연구는 SK C&C 기업연계프로젝트로, **대출상환 여부**를 예측하는 신용도 평가모형 개발 프로젝트입니다.

## 프로젝트 수행 과정
프로젝트 수행 과정은 다음과 같이 진행됩니다.
1. 미국 P2P 대출 기업 **Lending Club의 데이터 셋** 활용, 총 141개의 컬럼과 약 300만개의 행으로 구성
2. *8타겟 정의** - EDA를 통한 타겟 변수의 이진화 작업 수행
3. **변수 선택**
   - EDA를 통한 변수와 타겟과의 관계 분석 후 변별력 없는 변수 삭제
   - DATA Leakage(시간 순서 위배, 타겟에 정보 제공) 변수들 삭제
   - 가설을 통한 데이터 검증 후 논리적으로 어긋나는 행 삭제
   - 통계기반의 변수선택법을 통해 변별력 없는 변수 삭제
4. **데이터 전처리**
5. **모델링/하이퍼파라미터튜닝**
6. **XAI로 결론 도출**

