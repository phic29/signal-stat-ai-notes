# 공부 방향 개요: AI, 통계, 신호처리 기반 알고리즘 개발을 위한 정리

이 노트는 실무와 개인 공부를 통해 정리한 AI, 통계, 신호처리 관련 내용을 체계적으로 기록하기 위한 개요입니다.  
GitHub와 Tistory 블로그에 병행 업로드하며, 단순한 정리보다는 실험 코드와 통합하여 **기억에 남을 수 있는 정리**를 목표로 합니다.

---

## 1. 정리 목적

- **회사 실무에서 배운 개념의 체계적 기록**
- **논문, 논의된 이슈, 실험 결과의 정리**
- **내가 만든 코드, 실험, 모델 튜닝 결과의 재사용성 확보**
- Tistory 블로그와 연계하여 외부 공유 목적도 고려

---

## 2. 중점 정리 분야

### (1) AI/ML
- SwinTransformer / ConvNeXt 구조 분석 및 1D 변형
- Knowledge Distillation 이론과 실습 (Swin-T → ConvNeXt)
- Self-Supervised Learning (SupMAE, MAE, SimCLR 등)

### (2) Signal Processing
- 1D Biomedical Signal 전처리 및 분석
- FFT, Filtering, Denoising 기법 등 정리
- Sensor-based 데이터 분류/회귀 문제 실험

### (3) Statistics
- 기초 통계 및 검정: t-test, ANOVA 등
- 회귀분석, 베이지안 통계 등 모델링 관련 내용
- 실험 설계 및 데이터 정제 방법

---

## 3. 앞으로의 구조 계획

- `notes/`: 이론 정리 및 블로그 초안
- `notebooks/`: 실험 코드 및 시각화 결과
- `projects/`: Toy 프로젝트 및 실사용 코드
- `blog_backup/`: Tistory 블로그 업로드 글 백업

---

## 4. 목표 및 원칙

- **복습 가능한 기록**: 단순 복붙이 아닌 '왜'를 설명
- **실행 가능한 실험 코드와 함께 기록**
- **개인 학습이지만, 외부인이 봐도 흐름이 보이게**

> "정리는 학습의 끝이 아니라 시작이다."