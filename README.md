<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3A1C71,50:5B86E5,100:36D1DC&height=110&section=header"/>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://capsule-render.vercel.app/api?type=venom&color=0:3A1C71%2C50:5B86E5%2C100:36D1DC&height=250&section=header&text=Hello%2C%20I%27m%20Jaehoon%20Jung&fontSize=46&fontColor=ffffff&fontAlignY=38&animation=fadeIn"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://capsule-render.vercel.app/api?type=venom&color=0:3A1C71%2C50:5B86E5%2C100:36D1DC&height=250&section=header&text=Hello%2C%20I%27m%20Jaehoon%20Jung&fontSize=46&fontColor=111111&fontAlignY=38&animation=fadeIn"
  />
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=venom&color=0:3A1C71,50:5B86E5,100:36D1DC&height=250&section=header&text=Hello%2C%20I%27m%20Jaehoon%20Jung&fontSize=46&fontColor=ffffff&fontAlignY=38&animation=fadeIn"
    alt="Header Banner"
  />
</picture>

<br/>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1400&color=36D1DC&center=true&vCenter=true&width=780&lines=AI+Service+Developer+%C2%B7+LLM+Engineer;Document+AI+%C2%B7+RAG+%C2%B7+Agent+%C2%B7+Fine-tuning;FastAPI+%C2%B7+Django+%C2%B7+LangGraph+%C2%B7+Qdrant"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1400&color=111111&center=true&vCenter=true&width=780&lines=AI+Service+Developer+%C2%B7+LLM+Engineer;Document+AI+%C2%B7+RAG+%C2%B7+Agent+%C2%B7+Fine-tuning;FastAPI+%C2%B7+Django+%C2%B7+LangGraph+%C2%B7+Qdrant"
  />
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1400&color=36D1DC&center=true&vCenter=true&width=780&lines=AI+Service+Developer+%C2%B7+LLM+Engineer;Document+AI+%C2%B7+RAG+%C2%B7+Agent+%C2%B7+Fine-tuning;FastAPI+%C2%B7+Django+%C2%B7+LangGraph+%C2%B7+Qdrant"
    alt="Typing SVG"
  />
</picture>

<br/>

<a href="mailto:fpdlwo@gmail.com">
  <img src="https://img.shields.io/badge/Email-fpdlwo%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/JeaHoon-J">
  <img src="https://img.shields.io/badge/GitHub-JeaHoon--J-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="YOUR_PORTFOLIO_URL">
  <img src="https://img.shields.io/badge/Portfolio-View-1E56D8?style=for-the-badge"/>
</a>

</div>

---

## About Me

비정형 도메인 문서를 구조화하고, **RAG·Agent·Fine-tuning 기능을 실제 AI 서비스로 구현하는 개발자**입니다.

- LangGraph 기반 Agent Workflow 및 조건부 Routing 설계
- QLoRA 멀티태스크 Fine-tuning과 정량 평가·품질 검증
- FastAPI·Django 기반 AI 기능 연동과 서비스 운영 경험
- RFP·회의록·특허 텍스트 구조화 및 분석 경험

---

## Featured Projects

### ALPLED
**sLLM 기반 CBD 산출물 생성·추적 Multi-Agent Platform**

나라장터 RFP와 회의록을 분석해 요구사항 정의서 등 CBD 산출물 6종을 생성하고, 변경 추적과 정합성 검증을 지원하는 플랫폼입니다.

- Requirement Agent 및 Architecture Agent 설계·구현
- Task1~3 데이터셋과 QLoRA 멀티태스크 Adapter 설계
- JSON Schema·Requirement ID 기반 구조 및 추적성 검증
- WBS 기반 일정 관리와 팀 이슈 조율 수행

**Result**  
`Requirement F1 0.4810 → 0.9201` · `Recall 0.3345 → 0.8569`

**Tech**  
`Python` `PyTorch` `Hugging Face` `QLoRA` `LangGraph` `Qdrant` `FastAPI` `Django` `AWS` `RunPod`

[Repository](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN24-FINAL-3Team) · [Portfolio Detail](YOUR_PORTFOLIO_URL)

<br/>

### VISA LA VISTA
**SQL Agent 기반 해외 대학 입시 정보 챗봇**

내부 MySQL DB에서 대학 정보를 우선 조회하고, 미등록 질문은 공식 웹 검색으로 전환해 근거 기반 답변을 제공하는 AI 서비스입니다.

- LangGraph 기반 SQL Agent Workflow 구현
- Query 검증·Self-Correction·재시도 로직 적용
- DB 결과 없음 시 Web Search Fallback 전환
- Django·FastAPI·MySQL 연동 및 SSE 최종 응답 전달
- `user_id·chat_id` 기반 대화 이력 저장

**Validation**  
`DB 등록 대학 질문 정확 응답 50/50` · `검색 전환 및 공식 출처 경로 검증`

**Tech**  
`Python` `LangGraph` `Gemma3` `Ollama` `FastAPI` `Django` `MySQL / AWS RDS` `Web Search` `SSE`

[Repository](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN24-4th-5Team) · [Portfolio Detail](YOUR_PORTFOLIO_URL)

---

## Research & Publication

### A data-driven approach to establishing a patent strategy by generating a patent map based on generative topographic mapping
**제1저자 · 데이터 분석 · 모델 설계 · 논문 작성**

특허 청구항을 SAO 구조로 변환하고, GTM 기반 기술 포지셔닝과 공백 기술·전략 패턴을 분석한 연구입니다.

- Technology Nodes `1,600`
- Vacant Nodes `637`
- Pattern Candidates `110`
- Top 4 우선 특허 전략 도출
- SSCI 저널 *Technological Forecasting and Social Change* 게재

[Paper](https://drive.google.com/file/d/1mJ-fuK-m4-yinEn7PfBqeI-I8WnF-Tha/view?usp=drive_link)

---

## Collaboration Projects

- **식약처** — 블록체인 기반 식품 이력추적·공유주방 안전관리 데이터 흐름 및 플랫폼 구조 정리
- **아모레퍼시픽** — SIRI 기반 스마트팩토리 기술 수준 평가 항목 및 결과 구조화
- **광개토연구소** — 특허 데이터 전처리·SAO 분석·BLEU/ROUGE 기반 생성 텍스트 평가
- **유수소프트** — 이미지 분석 기반 반려동물 추천 서비스 적용 방향 정리

---

## Tech Stack

### LLM / Agent / Evaluation

<p>
  <img src="https://img.shields.io/badge/LangGraph-FF6F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/QLoRA-8A2BE2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LLM%20Evaluation-5B86E5?style=for-the-badge"/>
</p>

### Backend / Infrastructure

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/RunPod-6C3BF7?style=for-the-badge"/>
</p>

### Data / Storage

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ChromaDB-5A45FF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
</p>

---

## Education & Training

- **동국대학교 일반대학원 · 산업시스템공학 석사 졸업
  - [데이터 테크놀로지·기술경영 연구실](https://sites.google.com/dgu.ac.kr/dtmlab/home?authuser=0)
  - 특허·NLP 기반 기술 포지셔닝 및 전략 연구

- **SK Networks Family AI Camp 24기**
  - Machine Learning · Deep Learning · LLM · RAG · Agent · AI Service Development

---

## Contact

<div align="center">

<a href="mailto:fpdlwo@gmail.com">
  <img src="https://img.shields.io/badge/Email-fpdlwo%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://github.com/JeaHoon-J">
  <img src="https://img.shields.io/badge/GitHub-JeaHoon--J-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="YOUR_PORTFOLIO_URL">
  <img src="https://img.shields.io/badge/Portfolio-View-1E56D8?style=for-the-badge"/>
</a>

</div>

<br/>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3A1C71,50:5B86E5,100:36D1DC&height=120&section=footer"/>

</div>
