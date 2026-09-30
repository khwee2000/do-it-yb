<div align="center">

# 링크룸 (LinkRoom)

**청년의 이야기와 다시 연결되는 방: 청년을 정책·사람과 이어 주는 AI 상담 파트너**

![Team](https://img.shields.io/badge/GitHub%20Org-doit--yb-181717?style=flat-square&logo=github&logoColor=white)
![AI 상담](https://img.shields.io/badge/AI%20%EC%83%81%EB%8B%B4-STT%20%C2%B7%20LLM%20%C2%B7%20RAG-6E56CF?style=flat-square)

<img src="https://raw.githubusercontent.com/doit-yb/.github/main/profile/linkroom.png" width="800" alt="LinkRoom 홈 화면">

**사회는 "쉬었음"이라 부르지만, 우리는 "뭘했음"이라 답합니다.**

</div>

## 소개

말해도 되는 공간, 연결되는 다음 단계. 링크룸은 청년의 목소리를 이해하고 정책 기회와 사람에게 다시 이어 주는 AI 상담 파트너입니다.

팀 **뭘했음 청년**([doit-yb](https://github.com/doit-yb))이 기획하고 개발하는 프로젝트이며, 개발 저장소와 자세한 소개는 조직 페이지에서 볼 수 있습니다.

## 해결하려는 문제

1. **상담 기록 누락**: 상담사가 대화를 들으면서 기록까지 하다 보니 일부 정보가 문서화 과정에서 빠짐
2. **상담 후 행정·정리 부담**: 요약, 분류, 보고서 작성이 모두 수작업
3. **후속 활용의 어려움**: 상담 데이터가 의미 단위로 구조화되어 있지 않아 정책 추천이나 위기 탐지에 쓰기 어려움
4. **맥락 단절**: 상담사가 바뀌면 맥락이 끊기고, 상담이 행동으로 이어지지 못함

## 주요 기능

- AI가 상담 음성을 실시간으로 이해
- 감정·키워드·상황을 의미 단위로 추출
- 상담 일지 자동 생성
- 청년의 상황에 맞춘 정책·기회 RAG 추천
- 상담 결과를 하나의 **Re:Connect Report**로 제공해 "대화 → 회복 → 행동"으로 이어지는 상담 경험 제공

## 기술 스택 (계획)

| 영역 | 후보 |
|---|---|
| Frontend | React / Flutter (상담 화면, STT 결과, 요약 결과, 문서 미리보기, 대시보드) |
| Backend | FastAPI (Python) 또는 Node.js (Express), REST API |
| AI Model | Whisper (Small), Gemma 등 요약 LLM |
| Database | MongoDB / PostgreSQL / Supabase 중 택1 |
| Infra | GitHub, HuggingFace / Colab / Local GPU (모델 개발) |

## 팀 구성

| 역할 | 이름 | 담당 |
|---|---|---|
| PM | 한민우 | 파이프라인 설계, 방향성 설정 |
| Frontend | 김민수 | 웹/앱 UI 구현 |
| Backend | 한승우 | API 서버, 문서 자동화 엔진 |
| AI | 강병민 | STT 모델, 요약 모델 파이프라인 |
| Designer | 황지원 | UI/UX 디자인 |

---

<div align="center">
<sub>Made by <a href="https://github.com/khwee2000">김민수 (@khwee2000)</a></sub>
</div>
