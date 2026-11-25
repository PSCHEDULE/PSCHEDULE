# 권성재

**Python · RAG Systems · AI Backend**

한국외국어대학교 컴퓨터공학전공에서 공부하고 있습니다. 임베딩 검색과 RAG 시스템을 구현하며, 문서 처리부터 검색·응답 평가까지 연결하는 작업을 해 왔습니다.

[포트폴리오](https://pschedule.github.io/) · [이력서 PDF](https://pschedule.github.io/assets/kwon-sungjae-resume.pdf) · [이메일](mailto:kw8590@naver.com)

## 프로젝트

### [Multilingual RAG Chatbot](https://github.com/PSCHEDULE/multilingual-rag-chatbot)
**3D MUSE 인턴 · 다국어 RAG 시스템 구현**

- **문제:** 한국어·영어·일본어·중국어 질문을 문서에 근거한 답변으로 연결
- **구현:** FAQ의 질문·답변을 함께 유지하는 Q+A 청킹, 검색·재정렬·응답 생성 파이프라인 구성
- **검증 기록:** 리포지토리 문서의 다국어 평가셋·스테이징 검증 기록. 실제 운영 배포·트래픽 전환은 수행하지 않음
- `Python` `FastAPI` `LangGraph` `Qdrant` `BGE-M3` `Docker`

[설계와 검증 기록](https://pschedule.github.io/projects/multilingual-rag.html)

### [Policy Pass](https://github.com/RAG-QnA-Eval-Lab/policy-pass-be)
**캡스톤 팀 프로젝트 · 청년정책 RAG 질의응답 백엔드**

- **문제:** 청년정책 문서에서 필요한 내용을 검색하고 질문에 답하는 백엔드 구성
- **담당:** FastAPI 백엔드 개발, FAISS 검색 구조 및 AWS 배포 환경 구성
- **설계:** 리포지토리의 `RAGService`가 검색·생성 객체를 주입받아 호출하고, 컨텍스트 제한과 출처 구성을 담당
- **테스트:** 검색·생성 대역을 사용한 서비스 테스트 7개 통과. `rag_service.py` 한 파일의 실행 가능 구문 97.83%, 분기 91.67% (2026. 11. 25. 측정)
- `Python` `FastAPI` `LangChain` `FAISS` `OpenAI Embedding` `AWS` `Docker`

[객체 관계와 테스트 설계](https://pschedule.github.io/projects/policy-pass.html)

### [Dot AI — 문서 기반 Q&A](https://github.com/PSCHEDULE/rag-evaluation-pipeline)
**개인 프로젝트 · 문서 업로드부터 출처가 있는 답변까지**

- **문제:** PDF·TXT·Markdown 문서를 바탕으로 질문하고 근거를 확인하는 흐름 구현
- **구현:** 청킹·임베딩·Chroma 검색·응답 생성, 파일명·PDF 페이지 출처 표시, 중복 임베딩 방지
- **구조:** Streamlit UI와 문서 처리 로직 분리. 업로드 객체의 `Protocol`과 색인 결과의 데이터 클래스 사용
- 세션 내 대화 기록을 표시하며, 질문별 검색과 응답은 독립적으로 수행
- `Python` `Streamlit` `LangChain` `Chroma` `OpenAI`

[Dot AI 설계·코드 보기](https://pschedule.github.io/projects/dot-ai.html)

### HUFS Lost & Found
**학부 팀 프로젝트 · AI 매칭 담당**

- **문제:** 분실물·습득물 정보에서 관련 있는 물품을 찾기
- **담당:** 임베딩 유사도 기반 매칭 기능의 AI 부분 개발
- `OpenAI Embedding` `Pinecone` `Firebase/GCP` `AWS`

[HUFS Lost & Found 구현 내용 보기](https://pschedule.github.io/projects/hufs-lost-found.html)

## 기술

| 영역 | 경험 기술 |
| --- | --- |
| 프로그래밍 | Python |
| AI 및 검색 | 임베딩 기반 검색, RAG 시스템 구성, 검색·응답 평가, 딥러닝 응용 |
| 백엔드 및 흐름 제어 | FastAPI, LangChain, LangGraph |
| 벡터 검색 | Qdrant, Chroma, FAISS, Pinecone |
| 도구 | Docker, Git, GitHub |

## 관심 분야

AI 시스템 구현 경험을 바탕으로 탐구하고 싶은 분야입니다.

- Physics-Informed Machine Learning · Neural Operator
- Engineering Surrogate Modeling · Simulation
- Simulation–Data–Optimization 기반 Industrial AI
- 물리·제조 시스템의 예측과 최적화

## 학력

**한국외국어대학교 공과대학 컴퓨터공학전공**  
2022. 03. ~ 2027. 02. 졸업 예정

관련 이수 교과목: 딥러닝응용, 컴퓨터비전개론, 자연어처리, 데이터베이스, 선형대수, 확률과통계, 공업수학, 자료구조, 알고리즘, 컴퓨터구조, 멀티코어컴퓨팅
