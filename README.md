# 눈도장 쾅! 🌻

산책하며 모으는 나만의 여름 스크랩북 PWA

## 기능
- 📷 사진 촬영 → AI 배경 제거 → 5s 감성 필터 → 스티커 변환
- 🗒️ 스크랩북에 자유롭게 배치 (드래그 · 크기조절)
- 🎯 오늘의 미션 3개
- 💾 로컬스토리지에 자동 저장

## 배포 방법 (Netlify)

### 1. 환경변수 설정
Netlify 대시보드 → Site settings → Environment variables
```
REMOVE_BG_API_KEY=your_api_key_here
```

### 2. 빌드 설정
- Publish directory: `public`
- Functions directory: `netlify/functions`

## 로컬 실행
```bash
npm install -g netlify-cli
netlify dev
```
