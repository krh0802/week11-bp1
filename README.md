# MUTE.

MUTE.는 성수동의 커피 바를 위한 에디토리얼 스타일 홈페이지입니다. 생화이트 바탕, 딥 블랙 타이포그래피, 넉넉한 글자 크기와 직각 그리드로 브랜드와 12종 메뉴를 소개합니다.

## 주요 기능

- **에디토리얼 퓨어 화이트 디자인** — `#FFFFFF` 배경, `#111111` 타이포그래피, 1px 구분선과 직각 모서리를 활용한 반응형 레이아웃
- **모노톤 SVG 메뉴 비주얼** — HTML 안에 직접 그린 정사각형 SVG 그래픽 12종
- **12종 메뉴 필터** — 커피, 논커피, 디저트를 카테고리별로 보기
- **흑백 무드 사진** — 히어로와 브랜드 소개에 grayscale/contrast 필터가 적용된 Unsplash 카페 사진과 로딩 실패 대체 배경 사용
- **인터랙션** — IntersectionObserver 페이드인, 메뉴 SVG 미세 확대, 반투명 블러 내비게이션
- **미니멀 오프닝 프리로더** — MUTE. 로고와 가는 진행 바가 짧게 표시된 뒤 화면이 위로 걷히며 본문 표시

## 기술 스택

- HTML5
- CSS3 (반응형 레이아웃, 애니메이션, 글래스모피즘)
- Vanilla JavaScript
- Inline SVG
- Git / GitHub
- Google Fonts: Plus Jakarta Sans, Instrument Serif; Pretendard 폰트 스택 포함

## 실행 방법

별도의 설치나 빌드 없이 `index.html`을 브라우저에서 열면 됩니다.

로컬 서버를 사용하려면 저장소 폴더에서 아래 명령을 실행하고 `http://localhost:8000`에 접속하세요.

```bash
python -m http.server 8000
```

Google Fonts와 Unsplash 사진은 네트워크 연결이 있을 때 로드됩니다. 메뉴 카드의 12개 모노톤 SVG 비주얼은 페이지 안에 포함되어 있습니다.

## 운영자

운영자: 김이현, krh0802@gmail.com
