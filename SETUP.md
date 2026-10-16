# seo-gali 프로필 적용

1. 압축파일의 `README.md`와 `assets/cards/` 폴더를 `seo-gali/seo-gali` 저장소 루트에 업로드합니다.
2. GitHub 프로필 화면에서 카드 이미지, 기술 배지, 클릭 링크 및 모바일 표시를 확인합니다.
3. 배포 시 `assets/source/` 폴더는 선택 사항입니다. SVG는 카드 이미지 편집용 원본입니다.

## 콘텐츠 구분

- `Current Projects`: 현재 프로젝트 4개를 개별 GitHub 저장소로 연결
- `Featured Projects`: 전달받은 Notion 문서 12개로 연결
- `Portfolio Archive`: 이전 README의 PDF 링크·표·문구를 **변경 없이 유지**
- `Tech Stack`: 전달받은 9개 분류, 50개 기술 배지를 원래 순서대로 반영
- `SNS`: 기존 Instagram/Tistory/Notion 링크 유지

## 외부 확인 필요

- Notion 주소 가운데 `358dbfd1e0fb80aab606f809f831feb9`는 주소에 제목이 없습니다. 카드에 'Notion Project · 제목 미확인'으로 표기했습니다. 해당 페이지의 실제 제목 확인 후 이미지/README alt를 수정하십시오.
- Notion 공개 여부와 GitHub 저장소/Archive PDF 링크의 HTTP 접근 가능 여부는 이 환경에서 확인하지 못했습니다. 원본 URL은 사용자가 제공한 대로 적용했습니다.
- PDF Archive는 직전 README를 정확히 유지했습니다. 링크에 포함된 계정명은 이미 `seo-gali`입니다.
- '현재 진행 중'은 사용자가 제공한 분류를 따릅니다. 카드 설명은 확인 가능한 프로젝트 맥락의 범위만 사용했습니다.

## 수정 안내

- 카드 이미지는 `assets/cards/current-*.png` 및 `assets/cards/featured-*.png`입니다.
- 편집 가능한 SVG는 `assets/source/`에 있습니다.
- 링크 URL은 `README.md`의 `<a href="...">`에서 변경합니다.
- 기술 배지는 README의 `img.shields.io` URL 목록을 수정합니다.
- Notion 페이지 제목 확인 후 `featured-unknown.svg`를 편집해 PNG로 다시 저장하십시오.
