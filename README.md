# KUIAI-Hackathon
## Goal 
High-perfomance Anomaly Detection in Novelty
- 주어진 데이터 셋에서 정상만 가지고 학습한 뒤 정상/비정상을 판단
- 데이터의 특성(다중 클래스, 초고차원 데이터)에 따라 
- 신규 알고리즘을 개발(통계기반, 머신러닝, 딥러닝 관계없음) 하거나, 기존 Anomaly Detection에 활용되는 알고리즘 조합 및 프로제스 변경 등의 다양한 접근 

- 목표는 높은 검출성능, 빠른 학습 및 판단 속도, 가벼운 모델크기 3가지를 목표로 최대한의 결과 도출

- 데이터셋
  - [KAMP 제조데이터셋](https://www.kamp-ai.kr/front/dataset/AiData.jsp)

- 검증방법
  - 검출검증: 적용 알고리즘의 AUROC 수치, 언노멀 스코어 시각화, 혼동행렬(Confusion Matrix) 등으로 성능 검증
  - 속도검증: 학습 데이터 수량, 데이터 차원, 컴퓨터자원(CPU, RAM)을 명시하고 학습시간과 예측시간으로 성능검증
  - 모델 크기: 필수 검증사항은 아니지만, 학습된 모델의 크기를 표기 
