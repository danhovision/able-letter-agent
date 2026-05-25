# Able Letter — 삶의 여정과 길목에서 묻는다

에이블(김정태 MYSC 대표)의 AI 커리어 편지 에이전트

## 기능
- 고민 입력 → AI 편지 생성 (Claude Sonnet 기반)
- 에이블이 검토 후 발송/수정/삭제
- 공개 편지함(라이브러리) 게재
- 6개 국어 번역 (🇰🇷🇺🇸🇯🇵🇨🇳🇪🇸🇫🇷)
- 글자 크기 조절, 키워드 검색, 좋아요, 읽음 표시

## 기술 스택
- React (Babel standalone)
- Supabase (편지 저장/불러오기)
- Claude API (편지 생성, 번역)
- 철학문장 풀 383개 (하드코딩)

## 배포
Vercel 정적 배포 — `able-letter-final.jsx` 단일 파일

## 환경변수 (Vercel)
- `SUPABASE_KEY`: Supabase Publishable Key
- `ANTHROPIC_KEY`: Claude API Key (서버 사이드 이전 시)
