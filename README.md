# Nudge Bible Data (넛지성경 무선 데이터 배포소)

이 저장소는 **[넛지성경 (Nudge Bible)]** 모바일 앱의 OTA(Over-The-Air) 무선 업데이트 데이터를 관리하고 배포하는 공식 데이터 패키지 저장소입니다.

---

## 📂 디렉터리 패키지 구조

```text
nudge-bible-data/
├── bible/                  # 📖 성경 번역본 OTA 패키지
│   ├── version.json        # 최신 번역본 버전 및 다운로드 URL
│   └── nudge_ai_v*.enc     # AES-256 암호화된 최신 넛지 AI 번역본 바이너리
│
├── nudges/                 # 🌱 매일 말씀 & 위로 알림 OTA 패키지
│   ├── version.json        # 알림 데이터셋 버전 및 메타데이터
│   └── daily_nudges.json   # 1년 365일 날짜별 큐레이션 말씀 및 코멘트
│
├── themes/                 # 💭 (예정) 상황별/감정별 맞춤 말씀 패키지
│   └── situational.json    # 불안, 위로, 감사 등 테마별 말씀 모음
│
└── assets/                 # 🎨 (예정) 감성 말씀 카드 템플릿/배경 에셋
```

---

## 🌐 엔드포인트 URL 안내 (GitHub Pages)

### 1. 성경 번역본 (`/bible`)
* **버전 확인:** `https://hmkim829.github.io/nudge-bible-data/bible/version.json`
* **최신 번역본 다운로드:** `https://hmkim829.github.io/nudge-bible-data/bible/nudge_ai_v1.0.49.enc`

### 2. 매일 넛지 알림 (`/nudges`)
* **버전 확인:** `https://hmkim829.github.io/nudge-bible-data/nudges/version.json`
* **알림 데이터 다운로드:** `https://hmkim829.github.io/nudge-bible-data/nudges/daily_nudges.json`
