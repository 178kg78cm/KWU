# KWU
## 약력
- **광운대학교 컴퓨터정보공학부 지능정보공학 전공**
- **군 복무**: 제32사단 병장 만기 전역 (2020.05.12 ~ 2021.11.15)
- **알락달락 KT 코딩교육 봉사** (2019.03 ~ 2019.08)
- **멋쟁이사자처럼 (Likelion) 활동**
  - 대학연합동아리 멋사 10기 활동 (2022)
  - 멋사 운영진 활동 (2023)
- **임베디드 SW 경진대회 수상**
  - 21회 임베디드 SW 경진대회 산학 부문 우수상 (2023.12.08)
- **LGAimers 5기 참가** (2024.07 ~ 2024.08)
  - 자동차 디스플레이 공정 데이터 기반 AI 모델 학습 프로젝트
- **드론 탐지 시스템 개발** (2024.01 ~ 2024.07)
  - YOLOv8 + SAHI 기반 객체 탐지 및 타임라인 기록
  - [GitHub Repository](https://github.com/178kg78cm/KWIAC-DroneDetectionSolution)
- **PVDF 수면 자세 분류 논문 발표** (2024.01 ~ 2024.11)
  - 대한의용생체공학회 2024 추계학술대회 우수 포스터 논문상 수상
  - CNN model-based sleep posture classification using PVDF sensor
- **현대오토에버 모빌리티 임베디드 SW 스쿨 수료** (2024.12 ~ 2025.06)
---

##  교육 이수 사항

### 현대오토에버 모빌리티 임베디드 SW 스쿨 수료
현대오토에버와 한국전파진흥협회가 주관하는 K-디지털 트레이닝 과정에 참여하여, 총 1000시간의 임베디드 SW 집중 교육을 이수하였습니다.

### 1. 기본 역량 강화
- 임베디드 시스템 기초: C 프로그래밍, 자료구조, RTOS, MCU 아키텍처 이해
- 차량 네트워크: CAN 프로토콜 설계, CANoe/CANalyzer 실습, DBC 파일 관리

### 2. 심화 기술 및 실무
- 차량용 Ethernet 기술: 100BASE-T1, 10BASE-T1S, SOME/IP, DoIP 실습
- AUTOSAR 아키텍처: BSW, RTE, SWC 구성 및 실시간 태스크 관리
- 기능안전/품질: Automotive SPICE, V-model, ISO 26262(HARA, ASIL 등급 분석)

### 3. 실습 중심 프로젝트
- PID 기반 속도 제어 시스템: STM32, Simulink 기반 제어기 설계 및 테스트
- 차량 통신 시스템 설계: Zonal/Domain 아키텍처 기반 CAN/Ethernet 통신망 구축
- 실시간 제어 시스템: TC275 및 Arduino 기반 제어 알고리즘 구현
- OTA 및 원격 진단 시스템: 차량 내 소프트웨어 업데이트 및 진단 프로토콜 설계

---

## 주요 프로젝트

### 1. PVDF 센서 기반 수면 자세 분류
> CNN 기반 모델로 수면 중 자세 분류

- **목표**: PVDF 센서의 데이터를 통해 수면 자세 자동 인식
- **입력 데이터**: (4, 7500, 24) 형태의 시간-주파수 변환 데이터
- **모델 성능**
  | 모델 | 정확도 | Precision | Recall | F1-score |
  |------|--------|-----------|--------|----------|
  | 2D CNN | 79.17% | 0.80 | 0.79 | 0.79 |
  | 3D CNN | 86.37% | 0.88 | 0.86 | 0.87 |
- [프로젝트 코드](https://github.com/178kg78cm/PVDF-Sleep-Position-Distinction)

---

### 2. 드론 탐지 시스템 (YOLOv8 + SAHI 기반)
> 객체 탐지 및 실시간 영상 기반 드론 식별 시스템

- **목표**: 드론, 비행기, 헬리콥터, 새 등 유사 객체 구분
- **기술 스택**: YOLOv8, SAHI, PyTorch, OpenCV
- **데이터**: 약 26,000장의 이미지 (Drone: 15,000장 포함)
- **기능**
  - 영상/카메라 기반 실시간 탐지
  - 객체 분류 및 타임라인 기록
  - GUI를 통한 탐지 결과 실시간 확인
- [GitHub Repository](https://github.com/178kg78cm/KWIAC-DroneDetectionSolution)

---

### 3. LG Aimers AI 모델 개발 프로젝트
> 자동차 디스플레이 공정의 정상/비정상 데이터 분류

- **문제**: 비정상 데이터 수가 매우 적은 상태에서 불균형 데이터 문제 해결
- **방법**
  - 결측치 제거 및 one-hot 인코딩
  - SVD 기반 차원 축소
  - SMOTE 기법을 통한 데이터 증강
  - Random Forest, MinMaxScaler 등 모델 조정
- **성과**: F1 score 19 → 21

---

## 교내 전공

### 1학년
- `C_programming`, `Advanced_C_programming`

### 2학년
- `객체지향 프로그래밍`
  - 3D Linked List 형태의 `Cube Class` 구현
- `Assembly Design`
  - Keil IDE로 Assembly 구현, Discrete Convolution
- `Data Architecture Design`
  - 이진 탐색 트리, FP-Growth, B+ Tree, 그래프 알고리즘 구현
- `컴퓨터공학기초실험`
  - Quartus 기반 ALU, BUS, RAM 설계 및 Testbench

### 3학년
- `컴퓨터구조`
  - MIPS CPU 및 MU0 Processor 구현
- `SPR & 프로젝트`
  - Spring Boot 기반 웹 사진 게시판 개발
  - Android 앱 개발
- `시스템 프로그래밍`
  - Linux 기반 Web Server 개발, IPC, 소켓 통신, Access Control 구현
- `운영체제`
  - 시스템 콜 Hooking, Scheduling 개선, Memory 구조 분석
- `수치해석 / 인공지능`
  - Bisection Method, PCA, LDA, Image Interpolation

### 4학년
- `소프트웨어 공학`
  - 주식 토론 게시판 및 거래 시스템 개발
- `머신러닝`
  - Naïve Bayes, GMM, KMeans, ResNet(CIFAR10) 구현
---

## 수상

| 연도 | 내용 |
|------|------|
| 2023.12 | 제21회 임베디드 SW 경진대회 산학부문 우수상 |
| 2024.11 | 대한의용생체공학회 추계학술대회 우수논문상 |
| 2024.08 | LG Aimers 5기 수료 |

---

## 참고 링크

- [PVDF 자세 분류 논문 요약](https://github.com/lkhyun/FSR-Sleep-Posture-Classification)
- [드론 탐지 프로젝트](https://github.com/178kg78cm/KWIAC-DroneDetectionSolution)
- [기타 실습 및 실험 저장소](https://github.com/lkhyun/KWU?tab=readme-ov-file)
- [객체 추적 프로젝트](https://github.com/lkhyun/Object-Tracking-Detection)
- [iGRAURD](https://github.com/Embedded-3/iGuard)


---
- Email: [jhh7550@gmail.com]
- GitHub: [https://github.com/178kg78cm](https://github.com/178kg78cm)
