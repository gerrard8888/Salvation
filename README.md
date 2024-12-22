# 🌟 Salvation 팀 프로젝트 소개

![LoGo](https://github.com/gerrard8888/rfrf/blob/main/ss.png?raw=true)

---
## 📚 목차
- [팀 소개](#팀-소개)
- [프로젝트 개발 이유](#프로젝트-개발-이유)
- [프로젝트 개요](#프로젝트-개요)
- [기존 챗GPT와의 차이점](#기존-챗gpt와의-차이점)
- [실행 방법](#실행-방법)

---

## 팀 소개

### 팀 이름: **Salvation**

| 이름          | 역할           | GitHub Profile                                   |
|---------------|----------------|-------------------------------------------------|
| 석준성       | 팀장           | [@seok](https://github.com/JunSeong0820)         |
| 전영재       | 부팀장         | [@jeon](https://github.com/gerrard8888)        |
| 정호영       | 프로그래머     | [@jung](https://github.com/hoaeng/Salvation)   |
| 김태원       | 엔지니어       | [@kim](https://github.com/cronak2355)          |

---

## 프로젝트 개발 이유

**컨츄리 프로젝트**는 관광지 정보가 부족한 관광객에게 생성형 AI를 통해 맞춤형 관광 가이드 서비스를 제공하기 위해 개발되었습니다.

### 주요 동기:
1. **문제 정의**: 관광지에 대한 정보 부족으로 여행에 어려움을 겪는 관광객.
2. **해결 목표**: 생성형 AI를 활용하여 정보 접근성을 높이고, 풍부한 여행 경험을 지원.
3. **핵심 가치**:
   - **정보 접근성**: 모든 관광객이 쉽게 접근할 수 있는 정보 제공.
   - **개인화된 경험**: 각 관광객의 취향에 맞춘 맞춤형 추천.

---

## 프로젝트 개요

### 프로젝트 이름: **컨츄리 프로젝트**

### 주요 기능:
- **이미지 인식 기반 정보 제공**: 업로드된 이미지에 대한 문화재 및 관광지 정보 분석.
- **텍스트 기반 질문 응답**: 텍스트 질문에 대한 정확한 답변 제공.
- **코스 추천 시스템**: 관광객의 선호도에 맞춘 여행 코스 추천.

### 기술 스택:
- **프론트엔드**: streamlit
- **백엔드**: openai
- **데이터베이스**: 
- **배포**: 

![시스템 구조](https://via.placeholder.com/800x400)

---

## 기존 챗GPT와의 차이점

1. **목적 및 기능**:
   - **컨츄리 프로젝트**: 관광지 정보 제공 및 맞춤형 여행 가이드 서비스에 특화되어 있음.
   - **챗GPT**: 일반적인 대화 및 다양한 주제에 대한 정보 제공에 중점을 둠.

2. **정보 제공 방식**:
   - **컨츄리 프로젝트**: 이미지 인식 및 텍스트 질문 응답 기능을 통해 관광지에 대한 구체적인 정보를 제공.
   - **챗GPT**: 텍스트 기반의 대화형 응답으로, 특정 이미지나 관광지에 대한 정보 제공 기능이 없음.

3. **개인화**:
   - **컨츄리 프로젝트**: 사용자의 선호도에 따라 맞춤형 여행 코스를 추천.
   - **챗GPT**: 개인화된 추천 기능이 제한적이며, 일반적인 정보 제공에 중점을 둠.

4. **사용자 경험**:
   - **컨츄리 프로젝트**: 관광객의 요구에 맞춘 인터페이스와 기능 설계.
   - **챗GPT**: 범용적인 대화형 인터페이스로, 특정 분야에 최적화되지 않음.

---

## 실행 방법

### 1. 환경 설정

0. **사전 요구사항**
- Python 3.8 이상
- Streamlit
- OpenAI Python SDK


1. **프로젝트 클론**
   ```bash
   git clone https://github.com/hoaeng/Salvation.git
   cd Salvation
   ```

2. **필요한 패키지 설치**
   ```bash
   pip install --upgrade streamlit
   pip install -r requirements.txt
   ```

3. **환경 변수 설정**
   프로젝트 루트에 `.env` 파일을 생성하고 아래 내용을 추가:
   ```env
   API_KEY=your_api_key
   ```

### 2. 실행
1. **개발 서버 실행**
   ```bash
   streamlit run .\salvation.py
   ```

2. **프로덕션 빌드** (선택 사항)
   ```bash
   ```

### 3. 접속
   - 로컬에서: `http://localhost:3000`
   - 배포된 서버: `http://172.16.42.249:8501`
---

감사합니다! 🙌
