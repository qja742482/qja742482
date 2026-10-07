<div align="center">

# 🛡️ 프로젝트 이름

**한 줄로 프로젝트를 설명하세요.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/status-in%20progress-orange?style=for-the-badge)

</div>

---

## 📌 소개

이 프로젝트가 무엇이고, 왜 만들었는지 2~3줄로 적습니다.

> 💡 **핵심 아이디어:** 한 문장 요약

## ✨ 주요 기능

- 🔍 기능 1 설명
- ⚙️ 기능 2 설명
- 🚀 기능 3 설명

## 🧰 기술 스택

| 구분 | 사용 기술 |
|------|-----------|
| 언어 | Python |
| API | Gemini API |
| 도구 | Git, GitHub, Jupyter Notebook |

## 📁 폴더 구조

```text
프로젝트/
├── agent_core/
│   ├── llm_client.py     # LLM 호출
│   └── tool_router.py    # 도구 선택
├── docs/
├── .env.example          # 환경변수 예시
├── .gitignore
└── README.md
```

## 🚀 시작하기

```bash
# 1. 저장소 복제
git clone https://github.com/[아이디]/[저장소].git
cd [저장소]

# 2. 가상환경
python -m venv .venv
source .venv/Scripts/activate   # Git Bash (Windows)

# 3. 패키지 설치
pip install -r requirements.txt

# 4. 환경변수 설정
cp .env.example .env            # 안에 API 키 입력
```

> [!WARNING]
> `.env` 파일은 절대 깃허브에 올리지 마세요. API 키가 노출됩니다.

## 🔄 동작 흐름

```mermaid
flowchart LR
    A[사용자 입력] --> B[tool_router]
    B --> C[llm_client]
    C --> D[Gemini API]
    D --> E[결과 출력]
```

<details>
<summary>📖 자세히 보기 (클릭)</summary>

접어두고 싶은 긴 설명을 여기에 넣습니다.

</details>

## 🗺️ 진행 상황

- [x] 깃허브 저장소 연결
- [x] `.gitignore` 설정
- [ ] 기능 구현
- [ ] 문서화

## 👤 만든 사람

**[이름]** · [GitHub](https://github.com/[아이디])

## 📄 License

MIT License
