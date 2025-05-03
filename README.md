# 국민대학교 단과대 챗봇 (Kookmin College Chatbot)

단과대별로 맞춤 정보를 제공하는 국민대학교 특화형 챗봇입니다.

## 📌 주요 기능

- 단과대 선택 후 전공별 공지 및 정보 제공
- RAG 기반 자연어 질문 응답
- FastAPI + LangChain + React 기반 구조

## 📁 프로젝트 구조

backend/ # FastAPI, LangChain, FAISS
frontend/ # React, Tailwind (챗봇 UI)
data/ # 크롤링 데이터
docs/ # API 문서 및 아키텍처


## 🚀 실행 방법

### Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
'''

### Frontend
'''bash
cd frontend
npm install
npm run dev
'''

## 👥 협업 규칙
main: 배포/최종
dev: 통합 개발
feature/*: 기능 단위 브랜치 (ex. feature/rag-integration)

