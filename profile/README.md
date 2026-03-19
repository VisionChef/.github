# 🍳 VisionChef

> **사용자가 가진 식재료를 AI가 시각적으로 파악해 맞춤형 요리를 제안하는 스마트 쿠킹 서비스**
>
> 단순한 레시피 검색을 넘어, 실시간 소통을 통해 요리의 완성까지 밀착 가이드하는 **인터랙티브 AI 코파일럿**입니다.

<br>

## 📌 프로젝트 소개

VisionChef는 냉장고 속 재료를 카메라로 찍으면, AI가 재료를 자동으로 인식하고 만들 수 있는 요리를 추천해줍니다.
추천에서 그치지 않고, 요리 과정 전반을 실시간으로 함께하는 **쿠킹 코파일럿** 경험을 제공합니다.

<img width="1519" height="1103" alt="image" src="https://github.com/user-attachments/assets/817f5504-e18b-4faa-93cf-766ee598cd26" />


<br> <br> <br>





## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| 🥦 **식재료 시각 인식** | CV 모델이 사진 속 식재료를 자동으로 감지 |
| 🍽️ **맞춤 레시피 추천** | 보유 재료 기반 RAG&LLM 레시피 생성 |
| 🎙️ **음성 인터랙션** | STT/TTS로 손 안 쓰고 요리하며 소통 |
| 💬 **실시간 코파일럿** | 요리 중 질문하면 즉시 답변 & 가이드 |

<br>

## 🛠️ 기술 스택

**AI**
- Computer Vision — 식재료 객체 탐지
- LLM + RAG — 레시피 생성 및 질의응답
- STT / TTS — 음성 입출력

**Web**
- FastAPI + Uvicorn
- SQLite
- Jinja2

<br>

## 📁 레포지토리 구조

```
VisionChef-org/
├── llm/          # RAG, Prompt, STT, TTS
├── cv-model/     # 식재료 인식 모델
├── Web/          # FastAPI 서버 + Jinja2 
└── .github/      # 조직 프로필
```

<br>

## 👥 팀원

<img width="1103" height="1080" alt="제목을 입력해주세요  (16)" src="https://github.com/user-attachments/assets/cd26320f-f517-4652-8717-1d6cb22f2a8b" />


<br>

---

<p align="center">
  인하대학교 인공지능공학과  &nbsp;|&nbsp; VisionChef Team
</p>
