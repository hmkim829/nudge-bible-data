# Nudge Bible Data (넛지성경 무선 데이터 배포소)

이 저장소는 **[넛지성경 (Nudge Bible)]** 모바일 앱의 OTA(Over-The-Air) 무선 업데이트 데이터를 제공하는 공식 배포소입니다.

## 제공 데이터 목록

1. **성경 번역본 OTA**
   - `version.json` : 최신 번역본 버전 및 릴리즈 메타데이터
   - `nudge_ai_v1.0.49.enc` : AES-256 암호화된 최신 넛지 AI 쉬운 성경 바이너리

2. **오늘의 말씀 & 알림 메시지 OTA**
   - `nudges.json` : 매일 아침 성도들에게 힘과 위로를 전하는 넛지 큐레이션 데이터셋

## 배포 경로 (GitHub Pages)
- Base URL: `https://hmkim829.github.io/nudge-bible-data/`
- 성경 버전 확인: `https://hmkim829.github.io/nudge-bible-data/version.json`
- 알림 데이터: `https://hmkim829.github.io/nudge-bible-data/nudges.json`
