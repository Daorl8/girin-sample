# STRUCTURE · girin-sample

```
girin-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인)
├─ wrangler.toml              name = girin-sample → girin-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · 문서 · index_*.html · _deploy 배포 제외
├─ gh-plex-r.woff2 / gh-plex-sb.woff2   한글 (IBM Plex Sans KR 400 · 600, 쓰는 글자만)
├─ gh-mono.woff2              시간 · 영문 라벨 (DM Mono 400, 라틴만)
├─ gh-word.webp / gh-word-w.webp   손글씨 워드마크 먹 · 흰색 (헤더 · 푸터)
├─ gh-mark-w.webp             와인잔 마크 흰색 (밤 섹션)
├─ gh-day / gh-night .webp    히어로 한 쌍
├─ gh-coupe / matcha / focaccia / dessert .webp   Day
├─ gh-window / wine / red / bar .webp             Night
├─ gh-lounge / chair / lamp / corner .webp        Space
├─ favicon.png · og-girin.jpg
├─ img/                       다올 제공 원본 58장 (배포 제외 · 얼굴 · 타 가게 로고 포함, 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#day` → `#night`(먹색) → `#space` → `#visit` → 푸터(먹색) + 모바일 `.quick`.

## 링크
- 네이버 길찾기 `map.naver.com/p/entry/place/2089571955` (헤더 · 히어로 · 오시는 길 · 하단 바)
- 전화 `0507-1353-1766` · 인스타 `@girin_haus`

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). DM Mono는 라틴 전용 → `.mono`에 한글 넣지 말 것.
