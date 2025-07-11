<<<<<<< HEAD
# AI-is-not-idiot
**이해음(이해의 소리)**
AI 기반 문해력 향상 및 세대 간 소통 증진 교육 플랫폼

---
## 1. 플랫폼 개요
**‘이해음(이해의 소리)’**은 기초 문해력이 부족한 문화 소외 계층(다문화 가정, 비문해 어르신, 학습 취약 아동 등)을 위한 AI 기반 교육 플랫폼입니다.  
- 사용자 개개인의 학습 수준에 맞춰 **글 읽기 → 요약하기 → 피드백** 과정을 반복하며 문해력을 강화합니다.  
- 가족 구성원 간 정보 공유 및 상호 이해를 돕는 **세대 간 소통 채널**을 제공합니다.

---

## 2. 핵심 기능

### 2.1 수준별 맞춤형 콘텐츠 제공
- **단계 구분**  
  - 초급 / 중급 / 고급으로 구분된 난이도 선택  
  - 어휘 수준, 문장 길이, 내용 복잡도를 조절하여 학습 부담 완화  
- **주제별 다양한 글 제공**  
  - 생활 정보(예: 건강 정보, 공공 서비스 이용법)  
  - 흥미로운 이야기, 쉬운 뉴스 등  
- **음성 지원(TTS)**  
  - 글을 읽어주는 기능을 통해 듣기 학습 병행 가능

### 2.2 AI 기반 요약 및 피드백
- **요약문 분석**  
  - 사용자가 읽고 요약한 글을 AI가 분석하여  
    - 오해한 부분 교정  
    - 핵심 내용 추가 안내  
- **학습 이력 관리**  
  - 오답 노트처럼 사용자가 자주 어려워하는 부분 기록  
  - 학습 패턴을 파악하여 맞춤형 콘텐츠 추천

### 2.3 맞춤형 단어장
- **자동 단어 저장 및 추가 기능**  
  - 학습 중 어려웠거나 새로 알게 된 단어를 자동으로 저장  
  - 사용자가 직접 단어 추가 가능  
- **학습 지원 자료 제공**  
  - 단어 의미, 예시 문장, 그림 자료 등을 함께 제공  
- **주기적 복습 알림**  
  - 복습 알림을 통해 학습 효과 극대화

### 2.4 세대 간 소통 채널
- **가족 계정 기능**  
  - 부모님·자녀·어르신 등 가족 구성원별 계정 생성  
  - 동일 콘텐츠 학습 후 **요약본 비교 및 토론** 기능 제공  
- **공유 게시판**  
  - 가족 간 유용한 정보, 학습 팁 등을 자유롭게 공유  
- **협력형 퀴즈 및 활동**  
  - 부모님과 자녀가 함께 풀 수 있는 쉬운 퀴즈 제공  
  - 놀이처럼 즐길 수 있는 학습 경험 제공

---

## 3. 기대 효과
1. **개인 문해력 향상**  
   - 문화 소외 계층의 읽고 쓰는 능력을 강화하여  
   - 정보 접근성을 높이고 일상생활 불편 해소  
2. **세대 간 소통 증진**  
   - 가족 구성원 간 정보 공유 및 공동 학습을 통해  
   - 상호 이해를 높이고 소통 격차 해소  
3. **디지털 격차 해소**  
   - 디지털 기기 사용에 익숙하지 않은 어르신도 쉽게 사용 가능한 UX  
   - 재미있는 학습 경험으로 디지털 학습 환경에 대한 거부감 감소  
4. **사회 통합 기여**  
   - 다문화 가정 구성원들이 한국 사회에 더욱 쉽게 적응  
   - 문화적 장벽을 낮추고 사회 참여 기회 확대

---

## 4. 기술 스택 (예시)

### 4.1 프론트엔드
- **React / Vue.js**  
  사용자 친화적인 UI/UX 구현  
- **React Native / Flutter** (모바일 앱)  
  크로스 플랫폼 개발로 접근성 확대

### 4.2 백엔드
- **Node.js (Express) / Python (Django, Flask)**  
  안정적인 서비스 운영 및 확장성 고려  
- **RESTful API 설계**  
  클라이언트–서버 간 효율적 데이터 통신

### 4.3 데이터베이스
- **PostgreSQL**  
  관계형 데이터 관리 (유저 정보, 학습 이력 등)  
- **MongoDB**  
  비정형 데이터(텍스트 콘텐츠, 사용자 요약문 등) 저장

### 4.4 AI/ML
- **자연어 처리(NLP)**  
  - Transformer 기반 모델(BERT, GPT 등) 활용  
  - 텍스트 요약, 의미 분석, 피드백 생성  
- **음성 합성(TTS)**  
  - 글을 음성으로 변환하여 듣기 학습 지원  
- **음성 인식(STT, 선택 사항)**  
  - 사용자의 음성 요약 입력을 텍스트로 변환

### 4.5 클라우드 및 인프라
- **AWS / Google Cloud Platform / Microsoft Azure**  
  - 서버 관리, 데이터 저장, AI 서비스 연동  
  - 자동 확장(Auto Scaling) 및 로드 밸런싱  
- **CI/CD 파이프라인 구축**  
  - GitHub Actions, Jenkins 등으로 배포 자동화
=======
# 이해음 frontend (recat+vite)

## **1. 사용 기술 / 라이브러리**

- styled-components
- react-router-dom
- pnpm
- react

## **2. 실행 방법**

### version

- **node.js** v22.16.0  
  [설치하기 ->](https://nodejs.org/ko/download)
- **pnpm** v10.12.1  
  -> `npm i -g pnpm`

```
git clone frontend https://github.com/dolphin-kidnappers/AI-is-not-idiot.git
cd [clone project name]
pnpm i
pnpm run dev
```
>>>>>>> origin/frontend
