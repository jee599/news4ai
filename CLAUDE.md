# News4AI

## 프로젝트 개요
AI 뉴스 자동 수집 → 이메일 뉴스레터 → 모바일 앱 플랫폼.
jidonglab.com의 AI 뉴스 파이프라인을 독립 서비스로 확장한다.

## 기획서
- `docs/SPEC.md` — 전체 기획서 (Phase 1~3)
- `docs/MEETING-NOTES.md` — 회의록 + 의사결정 기록

## 기술 스택
- Cloudflare Workers (크롤러, API, cron)
- Upstash Redis (구독자, 뉴스 저장)
- Resend (이메일 발송)
- Expo / React Native (모바일 앱)
- Claude Haiku (뉴스 중요도 판정)

## 코딩 컨벤션
- TypeScript 우선
- 함수형, hooks 패턴
- Conventional Commits
