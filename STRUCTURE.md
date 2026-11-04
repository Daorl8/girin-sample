# STRUCTURE · girin-sample (v0.2 정물집)

```
girin-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인, lang="en" + 한글 보조 lang="ko")
├─ wrangler.toml              name = girin-sample → girin-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ gh-caslon.woff2            영문 제목 (Libre Caslon Display, 라틴만)
├─ gh-hanken.woff2            영문 본문 (Hanken Grotesk 400–600, 라틴만)
├─ gh-pretendard.woff2        한글 보조 (Pretendard, 쓰는 글자만)
├─ gh-word.webp               손글씨 워드마크 (헤더 · 표지)
├─ gh-mark.webp               와인잔 마크 (모임 · 푸터)
├─ gh-cover.webp              표지 정물 (img 46)
├─ gh-coupe / matcha / day / dessert / focaccia .webp   Chapter I Coffee (Plate 01~05)
├─ gh-lamp / window .webp                               Chapter II Natural Wine (Plate 06~07)
├─ gh-lounge / chair / corner .webp                     Chapter III The Haus (Plate 08~10)
├─ favicon.png · og-girin.jpg
├─ _old/                      v0.1(낮/밤) 파일 보관, 배포 제외
├─ img/                       다올 제공 원본 58장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 표지 → 소개 → `#coffee` → `#wine` → 모임(.gather) → `#haus` → `#visit` → 푸터 + 모바일 `.quick`.

## 플레이트 배치
`.plate`(왼쪽) · `.plate.r`(오른쪽) · `.plate.c`(가운데) · `.wide`(4:3). 데스크톱 12칸 그리드.

## 폰트 재생성
한글 문구 바꾸면 Pretendard 서브셋 재생성(LESSONS §26). Caslon · Hanken은 라틴 전용.
