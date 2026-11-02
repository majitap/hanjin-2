# 한진개발 홈페이지 v2

운영 주소: https://majitap.github.io/hanjin-2/
원본 사이트: https://majitap.github.io/hanjin/

대구 및 인근 건설 현장의 인력 공급을 안내하는 반응형 정적 사이트입니다.
GitHub Pages에서 `main` 브랜치의 저장소 루트(`/`)를 배포합니다. 빌드 과정은 없습니다.

## 디자인 기준

- 8px 그리드: 모든 여백·간격과 줄 높이(line-height)가 8의 배수입니다. `styles.css`의 `--s1`(8px) ~ `--s20`(160px) 토큰만 사용합니다.
- 서체: SUIT Variable 한 가지 (jsDelivr CDN)
- 색: 아스팔트 `#1b1f23`, 콘크리트 `#eceeec`, 한진 그린 `#1f4a3d`, 안전모 옐로 `#f5c400`, 그래파이트 `#5d656c`
- 그라데이션 없이 단색 면과 반투명 블러만 사용합니다.

## 파일

- `index.html`: 배경 영상 첫 화면, 회사소개·인력공급·진행절차·문의 섹션, 문의 창
- `styles.css`: 8px 그리드 토큰, PC·태블릿·모바일 화면
- `script.js`: 상단 메뉴, 배경 영상 정지/재생, 현재 섹션 표시, 문의 창, 입력 검증, 문의 전송과 내용 복사
- `email.js`: Web3Forms 전송, 응답 확인과 오류 안내
- `assets/`: 로고, 배경 영상(`hero.mp4`, Pexels 무료 라이선스, Sururi Ballıdağ), 포스터, 현장 사진

## 문의 메일

문의 접수는 원본 사이트와 같은 Web3Forms 폼(`data-access-key`)을 사용합니다.
수신 주소는 Web3Forms 관리 화면의 Settings → Recipient Emails에서 설정합니다.

CSS 또는 JavaScript 수정 후에는 HTML의 파일 버전 쿼리(`?v=`)도 갱신합니다.
