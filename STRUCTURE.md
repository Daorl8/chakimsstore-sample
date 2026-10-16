# STRUCTURE · chakimsstore-sample

```
chakimsstore-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = chakimsstore-sample → chakimsstore-sample.lgt3232.workers.dev
├─ .assetsignore           img/·문서·index_*.html·미사용 webp 3장 배포 제외
├─ ck-hand.woff2           영문 손글씨 (Shantell Sans 고정 인스턴스)
├─ ck-pretendard.woff2     한글 (사용 글자만 → 글자 추가 시 재생성)
├─ ck-logo-ink.png         고양이 로고 먹색
├─ ck-logo-white.png       고양이 로고 흰색 (푸터)
├─ ck-*.webp               사진 20장
├─ favicon.png / og-chakims.jpg
├─ img/                    다올 제공 원본 29장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#day`(흰 · 윗선) → `#night`(검정 · 네온 `#neon`) → `#plates` → `#room` → `#visit`(윗선) → 검정 푸터.

## 손그림 요소
- 삐뚤한 네모 = `border-radius:var(--wobble)` / `var(--wobble2)` + 2~2.5px 검정 테두리.
- (v0.1.1) 돌 타일 마퀴 띠는 삭제됨.
- 더 차분하게 바꾸고 싶으면(C안): 사진 회전(transform:rotate) 제거.

## 색
라일락 `--lilac`은 밤 섹션 네온 · 호버에만. 흰 바탕 글자색으로는 쓰지 않음.
