# 《흑야(黑夜)》 세계관 소개 사이트

Lored Studio — 한국형 여성향 느와르 인터랙티브 AI 챗 《흑야》 소개용 모바일 퍼스트 정적 사이트.

- 엔트리: `흑야 소개.dc.html` (단일 파일 + `_ds/` 스타일 번들, `image-slot.js`)
- 기준 문서: 세계관 설정집 v1.19 / 배경미술 설정집 v1.2 (두 문서 충돌 시 세계관 설정집 우선)
- 우선순위: 서사 > 인물 > 관계 > 당신 설정 > 공간

## 이미지 파일명 규칙 (전부 4:3)

사이트의 모든 이미지 자리는 드래그&드롭 플레이스홀더로 처리되어 있다. AI 생성 이미지가 준비되면
아래 경로로 파일을 두거나, 브라우저에서 각 자리에 직접 드롭하면 된다(드롭은 자동 저장됨).

### assets/characters/
`seo-taegun.png` 서태건 · `baek-siheon.png` 백시헌 · `kang-jaegyeong.png` 강재경(김준서) ·
`geum-ian.png` 금이안 · `baek-haram.png` 백하람 · `moon-ire.png` 문이레 · `park-jongsu.png` 박종수 ·
`sa-hyeok.png` 사혁 · `chu-yeonghae.png` 추영해 · `dokgo-sin.png` 독고신 · `sa-eunchae.png` 사은채 ·
`seol-yeonhwa.png` 설연화 · `yu-imin.png` 유이민 · `cha-iheon.png` 차이헌 · `oh-gapsu.png` 오갑수 ·
`won-myeongseok.png` 원명석

### assets/places/
흑영타워: `tower-exterior.png`, `tower-office-42f.png`, `tower-strategy-41f.png`, `tower-clinic-b3.png`, `tower-hideout-b6.png`
밤의 세계: `b1-bar.png`, `f1-bar.png`
인천항: `port-yard.png`, `port-warehouse.png`, `sageom-hq.png`, `sageom-office.png`
한남동 저택: `mansion-exterior.png`, `mansion-living.png`, `mansion-study.png`, `mansion-pool.png`, `mansion-guestroom.png`
서브: `sevenport-vip.png`, `gukbap.png`, `laundry.png`, `fishing.png`, `yeongdo.png`

### assets/logos/ (투입 완료)
`heukyoung-holdings.png` 흑영 홀딩스 · `heukyoung-capital.png` 흑영캐피탈 · `suradoga.png` 수라도가 ·
`heukyoung-palace.png` 흑영 팰리스 · `seven-pot.png` 세븐포트 · `maison-heukyoung.png` 메종 흑영 ·
`yayeon.png` 주식회사 야연 · `b1.png` B1 · `f1.png` F1
미투입: `heukya-title.png` 타이틀 로고(히어로 텍스트 로고 대체용)

## 미확정 (임의 캐논화 금지)
- 시작 설정 ②(사혁의 외조카)·④(토끼 수인): 카드 문구는 한 줄 컨셉까지만. 캐논 확정 후 갱신.
- 크랙/제타 플랫폼 링크 URL 미정 — 푸터 버튼은 비활성 상태.

## 배포
정적 파일 전부(`흑야 소개.dc.html`, `_ds/`, `image-slot.js`, `assets/`)를 그대로 정적 호스팅(GitHub Pages, Netlify 등)에 업로드.
