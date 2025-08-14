# 🏭 VODA

**VODA**는 AI 기반 결함 감지와 품질 등급 분류를 자동화하는 스마트 팩토리 시스템입니다.  
하드웨어(Arduino + Raspberry Pi)와 소프트웨어(Frontend, Backend, AI 서버) 전반을 아우르며, Google Cloud Storage와 CI/CD 자동화를 통해 안정적이고 효율적인 생산 품질 관리 환경을 제공합니다.

---

## 📦 프로젝트 구성

| Repository | 설명 |
| ---------- | ---- |
| **Frontend Dashboard**<br/>[`zezeone-dashboard`](https://github.com/your-org/zezeone-dashboard) | Next.js + Tailwind CSS 기반 실시간 품질 모니터링 대시보드 |
| **Raspberry Pi Controller**<br/>[`zezeone-raspi`](https://github.com/your-org/zezeone-raspi) | Arduino 제어, 카메라 촬영, GCS 업로드, 헬스체크 수행 |
| **Defect AI Server**<br/>[`zezeone-defect-ai`](https://github.com/your-org/zezeone-defect-ai) | YOLO 기반 결함 감지 API 서버 |
| **Backend API Server**<br/>[`zezeone-backend`](https://github.com/your-org/zezeone-backend) | Spring Boot 기반 사용자 인증, 품질 데이터 제공 |
| **Grade Rule Server**<br/>[`zezeone-grade-rule`](https://github.com/your-org/zezeone-grade-rule) | Green Dot 분석 기반 A/B 등급 판정 API 서버 |

---

## 🛠️ 기술 스택

**공통**
- **클라우드**: Google Cloud Storage
- **CI/CD**: GitHub Actions
- **컨테이너**: Docker

**Frontend**
- Next.js 14, Tailwind CSS, Zustand, Recharts, D3.js

**Backend**
- Java 21, Spring Boot 3.4.3, MongoDB, Spring Security

**AI 서버**
- FastAPI, Python (YOLO / OpenCV / scikit-learn), MongoDB

**임베디드**
- Raspberry Pi, Arduino Uno, OpenCV, pySerial

---

## 🔍 주요 기능

- **실시간 결함 감지**
  - SNAP1 신호 → AI 서버로 전송 → 불량 여부 판단
- **품질 등급 분류**
  - SNAP2 신호 → Rule 기반 서버로 전송 → A/B 등급 판정
- **대시보드 시각화**
  - 불량률, 균일도, 생산량, Green Dot 분석 결과 실시간 표시
- **데이터 관리**
  - MongoDB 저장 및 GCS 업로드
- **헬스체크**
  - 카메라, AI 서버, Rule 서버, GCS 연결 상태 주기 점검

---

## 🖇️ 시스템 아키텍처

![System Architecture](https://github.com/user-attachments/assets/sample-architecture.png)

---

## 🚀 빠른 시작

각 레포지토리 README를 참고해 주세요.

1. **Frontend Dashboard**: [README](./zezeone-dashboard/README.md)
2. **Raspberry Pi Controller**: [README](./zezeone-raspi/README.md)
3. **Defect AI Server**: [README](./zezeone-defect-ai/README.md)
4. **Backend API Server**: [README](./zezeone-backend/README.md)
5. **Grade Rule Server**: [README](./zezeone-grade-rule/README.md)

---

## 📬 문의

스마트팩토리 ZEZE ONE 팀


