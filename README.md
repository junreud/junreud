# 김준석 | AI Engineer

LLM 기반 AI 시스템 설계와 서비스화에 관심 있는 AI Engineer입니다.  
RAG 파이프라인 설계, 데이터 수집/전처리, vLLM 기반 추론 인프라 구성, 비용 최적화, VRAM 최적화 경험이 있습니다.  
풀스택 개발과 마케팅 도메인 경험을 바탕으로, 비즈니스 문제를 제품 관점에서 해결하는 AI 시스템을 지향합니다.

---

## 👤 About Me

- 고객상담 챗봇 프로젝트에서 RAG 설계, 데이터 전처리, 청킹 전략 수립, 그래프 아키텍처 설계, vLLM 인프라 최적화 담당
- 정량/비전 AI 대회 다수 참가 및 상위권 성과
  - Deepfake Detection: 459개 팀 중 10위
  - Hull Tactical - Market Prediction: 대회 최종 제출 완료 후, 제출 모델 기반 S&P500 실전 예측 6개월 운영 중 (현재 3개월 경과, 3,340개 팀 중 58위, 상위 1.7%)
  - 축구공 좌표 예측: 937개 팀 중 상위 10%
- 디지털 마케팅 및 아웃바운드 세일즈 경험 보유
- 마케팅 관리 대시보드를 직접 개발하며 제품 개발/배포 경험 축적

---

## 🛠️ Tech Stack

### Languages
- Python
- TypeScript
- JavaScript

### AI / ML
- PyTorch
- Transformers
- Scikit-learn
- Pandas
- NumPy
- LightGBM
- Optuna

### LLM / NLP
- RAG
- Prompt Engineering
- Embedding
- Vector Search
- Small Model SFT
- LLM Evaluation

### Serving / Backend
- vLLM
- FastAPI
- Express.js

### Infra / DevOps
- Docker
- Linux
- GPU Serving
- VRAM Optimization
- Caching Strategy

### Experiment
- Weights & Biases (W&B)

---

## 🏆 Competition

| Title | Content | Date | Host |
|------|--------|------|------|
| 📂 [Hull Tactical - Market Prediction](https://github.com/junreud/quant) | S&P500 기반 리스크 제어형 자산배분 모델 개발 / **최종 제출 완료 + 실전 예측 운영 중(6개월 계획, 3개월 진행)** | 2026.01 ~ 진행 중 | Kaggle |
| 📂 [HAI(하이)! - Hecto AI Challenge : 2025 하반기 헥토 채용 AI 경진대회](https://github.com/junreud/dacon-deepfake) | Vision-Language Model 기반 Deepfake Detection 모델 개발 / **459개 팀 중 10위** | 2025.12 ~ 2026.02 | DACON |
| 📂 [Track1 알고리즘 부문 : K리그-서울시립대 공개 AI 경진대회](https://github.com/junreud/football) | ML 기반 축구공 좌표 예측 모델 개발 / **937개 팀 중 상위 10%** | 2025.12 ~ 2026.01 | DACON |

---

## Projects

### 1) Customer Support Chatbot with RAG (진행 중)

고객 상담 자동화를 위한 LLM 기반 챗봇 시스템 프로젝트입니다.  
RAG 설계부터 데이터 파이프라인, 추론 인프라 최적화까지 서비스 운영 관점으로 구현하고 있습니다.

**What I did**
- 고객상담 시나리오 기반 RAG 파이프라인 설계
- 데이터 수집/정제 및 검색 품질 개선용 청킹 전략 수립
- Node Graph 기반 멀티스텝 아키텍처 설계
- vLLM 기반 추론 인프라 구성 및 캐싱 전략 설계
- 소형 모델 SFT 가능성 검토 및 VRAM 최적화 실험

**Tech**
- Python, PyTorch, vLLM, Qdrant, LangChain, Docker

---

### 2) Kaggle | Hull Tactical - Market Prediction

S&P500 시계열 데이터 기반 대회 프로젝트로, 커스텀 지표(Adjusted Sharpe)를 직접 최적화하는 리스크 제어형 allocation 시스템을 구현했습니다.

**What I did**
- Purged Walk-Forward CV 기반 검증 파이프라인 설계
- Return / Volatility / Market Regime 3-모델 구조 설계 및 통합 allocation 구현
- 시계열/레짐 피처 엔지니어링 + 중요도/상관/Crash divergence 기반 피처 선택
- 하이퍼파라미터 튜닝(Optuna), 실험 추적, 추론/제출 패키징 자동화
- 대회 최종 제출 모델 기반 실전 S&P500 예측 운영

**Result**
- 대회 최종 제출 완료
- 실전 예측 6개월 운영 중 (현재 3개월 경과)

**Tech**
- Python, LightGBM, Scikit-learn, Optuna, Pandas, NumPy

---

### 3) DACON | HAI(하이)! - Hecto AI Challenge : 2025 하반기 헥토 채용 AI 경진대회

Deepfake Detection 대회에서 VLM 기반 접근으로 모델을 개발해 459개 팀 중 10위를 기록했습니다.

**What I did**
- 데이터 분석 및 전처리
- VLM 기반 모델 실험 및 성능 개선
- 실험 결과 비교 및 오류 분석 반복

**Result**
- 459개 팀 중 10위

**Tech**
- Python, PyTorch, Vision-Language Model, Multimodal Modeling

---

## Experience

### Marketing Business & Outbound Sales
**기간: 2023.05 - 2025.05**

온라인 마케팅 아웃바운드 세일즈를 수행했으며, 이후 약 6개월간 마케팅 관련 사업을 운영했습니다.  
운영 과정에서 필요한 기능을 직접 웹페이지/대시보드로 구현하며 제품 개발과 배포 환경을 경험했습니다.

**What I learned**
- 고객 문제를 제품으로 해결하는 관점
- 기술보다 문제 정의가 우선이라는 점
- 운영 관점에서 효율과 비용 최적화의 중요성

---

## Education

### 중원대학교 식품공학과 중퇴
- 기간: 2019.02 - 2022.06

### SK Family 엔코아 플레이데이터 AI 21기
- 과정명: K-디지털트레이닝
- 기간: 2025.10 - 2026.03

---

## ✉️ Contact

- Email: [cngkdkr@gmail.com](mailto:cngkdkr@gmail.com)
- GitHub: [junreud](https://github.com/junreud)
- Blog / Portfolio: [링크]
- LinkedIn: [선택]
