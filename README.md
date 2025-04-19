# 🤖 Daily Auto Commit Bot

하루에 한 번 자동으로 커밋을 날려주는 **GitHub Actions 기반 자동 커밋 봇**입니다.  
잔디 심기, 잔디 유지 목적으로 사용하고 있습니다. 🌱

---

## 📌 주요 기능

- 매일 오전 9시**에 자동 커밋 실행
- `date.txt` 파일을 업데이트하여 커밋 트리거 유발
- GitHub Actions를 사용

---

## 🛠 프로젝트 구조

```bash
.
├── .github
│   └── workflows
│       └── auto-commit.yml  # GitHub Actions 워크플로우 설정
├── date.txt                 # 자동 커밋 트리거 파일 (매일 내용 갱신)
└── README.md                # 이 파일!
