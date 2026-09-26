# 올바른방수

`puzzlestore.kr`을 대표 URL로 설정한 한국어 Astro 정적 사이트입니다.

## 출처

[ProCleaning](https://github.com/anastasiiaxfr/ProCleaning)의 MIT 라이선스 Astro 구조를 바탕으로 재구성했습니다. 라이선스 전문은 `LICENSE`에 보존했습니다. 원본의 이미지나 업체 정보는 사용하지 않았습니다.

## 실행과 배포

```bash
npm ci
npm run build
```

대표 주소 기본값은 `https://puzzlestore.kr`입니다. 배포 환경의 `SITE_URL` 값이 있으면 그 값을 우선 사용합니다. 네이버 소유 확인 메타 태그는 공통 헤드에 적용되어 있습니다. 확인 값을 바꿀 때는 `src/layouts/Base.astro`의 태그를 수정하고 다시 배포하세요.

사업자 연락처, 실제 서비스 지역, 시공 사례, 자격 및 보증 조건은 제공되지 않아 임의로 적지 않았습니다. 게시 전에 확인된 정보로 보강하세요. 기존 도메인에 남은 게임 콘텐츠 URL은 새 사이트 배포 후 검색 결과와 HTTP 상태를 확인해야 합니다.
