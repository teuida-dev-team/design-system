# 토큰

값은 라이트 모드. 이름보다 용도로 고른다.

## Color

| 묶음 | 토큰 | 값 | 기본 색 | 언제 |
|---|---|---|---|---|
| Background | background-primary | #F5F5F5 | gray-100 | 앱 화면의 가장 기본 배경. 카드나 시트처럼 화면 위에 올라가는 면에는 background-secondary. |
| Background | background-secondary | #FFFFFF | white | 카드, 시트, 팝업처럼 기본 배경 위에 올라가는 면. |
| Background | background-tertiary | #E8E8E8 | gray-250 | 입력창, 비활성 영역처럼 면을 한 단계 더 구분할 때. |
| Background | background-dim-01 | #000000CC | black-80 | 팝업·시트 뒤를 진하게 가릴 때(80%). 콘텐츠를 완전히 멈추게 하는 화면. |
| Background | background-dim-02 | #00000099 | black-60 | 팝업·시트 뒤를 연하게 가릴 때(60%). 뒤 화면이 조금 보여도 되는 경우. |
| Background | background-highlight-soft | #E8FFF2 | green-50 | 선택되거나 강조된 영역의 연한 민트 배경. 버튼 면에는 button-highlight-soft. |
| Background | background-transparent | #F2F2F7 |  | 사용하지 않음. 개발 확인 후 정리 예정. (쓰지 않음) |
| Text | text-primary | #252525 | gray-800 | 제목, 본문 등 가장 기본이 되는 글자. |
| Text | text-secondary | #616161 | gray-650 | 보조 설명 글자. 제목 아래 설명, 리스트의 부가 정보. |
| Text | text-tertiary | #9E9E9E | gray-500 | 힌트, 메타 정보, 플레이스홀더처럼 가장 약한 글자. 아이콘은 icon-tertiary와 짝. |
| Text | text-unselected | #9E9E9E | gray-500 | 선택되지 않은 탭·옵션의 글자. 선택되면 text-primary 또는 text-highlight. |
| Text | text-highlight | #00E2B9 | green-500 | 브랜드 민트로 강조해야 하는 글자. 긴 문장에는 쓰지 않음. |
| Text | text-on-color | #FFFFFF | white | 민트 배지·버튼, 남색 프리미엄 배경, 영상 위처럼 진한 색 면 위의 흰 글자. |
| Text | text-inactive | #FFFFFF | white | 비활성 버튼 위의 흰 글자에만. 진한 색 면 위 흰 글자는 text-on-color. |
| Text | text-alert | #FF3F59 | red-500 | 경고, 입력 에러 문구, 로그아웃·삭제처럼 위험한 동작. 학습 오답은 text-failed. |
| Text | text-failed | #FF6F75 | red-400 | 학습 결과의 오답·실패 글자. 경고·위험한 동작은 text-alert. |
| Text | text-correct | #00A1A2 | green-700 | 학습 결과의 정답·성공 글자. |
| Icon | icon-primary | #252525 | gray-800 | 가장 기본이 되는 아이콘. 아이콘 컴포넌트의 기본 색. |
| Icon | icon-secondary | #757575 | gray-600 | 보조 아이콘. |
| Icon | icon-tertiary | #9E9E9E | gray-500 | 리스트 소리 버튼처럼 눈에 덜 띄어야 하는 보조 동작 아이콘. text-tertiary와 짝. |
| Icon | icon-highlight | #00E2B9 | green-500 | 활성화되었거나 브랜드 민트로 강조해야 하는 아이콘. |
| Icon | icon-on-color | #FFFFFF | white | 민트 버튼, 진한 배경, 사진 위처럼 진한 색 면 위의 흰 아이콘. |
| Icon | icon-unselected | #B7B7B7 | gray-400 | 선택되지 않은 탭의 아이콘. 선택되면 icon-primary 또는 icon-highlight. |
| Icon | icon-inactive | #DFDFDF | gray-300 | 누를 수 없는 비활성 아이콘. |
| Icon | icon-highlight-blue | #6995FF | blue-400 | 파랑으로 강조하는 아이콘. |
| Icon | icon-highlight-red | #FF6F75 | red-400 | 빨강으로 강조하는 아이콘. |
| Icon | icon-highlight-purple | #A240E8 | purple-500 | 보라로 강조하는 아이콘. |
| Icon | icon-transparent | #0000001A | black-10 | 배경에 은은하게 깔리는 반투명(10%) 아이콘. |
| Icon | icon-transparent-locked | #00000080 | black-50 | 잠긴 콘텐츠 위의 자물쇠 아이콘(50%). |
| Icon | icon-bubble | #87ADFF | blue-300 | 말풍선 아이콘. |
| Icon | icon-bubble-background | #D7E6FF | blue-100 | 말풍선 아이콘의 배경. |
| Border | border-secondary | #E8E8E8 | gray-250 | 기본 구분선과 카드 테두리. |
| Border | border-tertiary | #C8C8C8 | gray-350 | 더 진하게 나눠야 하는 구분선. |
| Border | border-primary | #FFFFFF | white | 진한 면 위에 두는 흰 테두리. |
| Border | border-highlight | #00E2B9 | green-500 | 선택되거나 포커스된 요소의 민트 테두리. |
| Border | border-inactive | #9E9E9E | gray-500 | 입력 전·비활성 입력창의 테두리. |
| Border | border-active | #757575 | gray-600 | 입력 중인 활성 입력창의 테두리. |
| Border | border-error | #FF6F75 | red-400 | 에러가 난 입력창의 테두리. 에러 문구는 text-alert. |
| Border | border-success | #3BEDBC | green-400 | 입력이 올바르게 끝난 입력창의 테두리. |
| Button | button-primary | #00E2B9 | green-500 | 메인 CTA 버튼 배경. 한 화면에 한두 개만. |
| Button | button-text-primary | #252525 | gray-800 | 메인 CTA 버튼 위의 글자. |
| Button | button-second-primary | #FFFFFF | white | 어두운 배경 위의 흰색 CTA 버튼 배경. |
| Button | button-secondary | #EFEFEF | gray-200 | 메인 CTA 옆에 두는 보조 버튼 배경. |
| Button | button-text-secondary | #3F3F3F | gray-750 | 보조 버튼 위의 글자. |
| Button | button-outline-secondary | #B7B7B7 | gray-400 | 보조 버튼의 테두리. |
| Button | button-tertiary | #F5F5F5 | gray-100 | 보조 버튼보다 약한 3단계 버튼 배경. |
| Button | button-text-tertiary | #FFFFFF | white | 3단계 버튼 위의 글자. |
| Button | button-inactive | #DFDFDF | gray-300 | 누를 수 없는 비활성 버튼 배경. 잠긴·비활성 회색 원에도 씀. |
| Button | button-text-inactive | #9E9E9E | gray-500 | 비활성 버튼 위의 글자. |
| Button | button-highlight | #3BEDBC | green-400 | 선택된 옵션 버튼, 열쇠 칩 테두리, Coming Soon 스티커처럼 브랜드 민트보다 밝게 써야 하는 곳. 브랜드 민트로 바꾸지 않음. |
| Button | button-highlight-soft | #E8FFF2 | green-50 | 선택된 옵션 버튼, 열쇠 칩, Try Premium 같은 연한 민트 버튼 면. 글자는 button-text-highlight. |
| Button | button-text-highlight | #00A1A2 | green-700 | 선택된 옵션 버튼 위의 글자. |
| Button | button-unfilled | #E8E8E8 | gray-250 | 아직 채워지지 않은 버튼·칩 배경, 이미지가 들어갈 빈 회색 카드. |
| Button | gradient-unfilled | #DFDFDF | gray-300 | 진행바·게이지에서 아직 채워지지 않은 부분. |
| Button | button-floating-background-inactive | #9E9E9E | gray-500 | 비활성 플로팅 버튼 배경. |
| Button | button-play-transparent | #00000066 | black-40 | 영상·이미지 위 재생 버튼의 반투명 배경. |
| Button | button-tag | #3BEDBC80 | green-400 50% | 태그 버튼의 반투명 민트(50%) 배경. |
| Button | button-primary-new | #00E2B9 |  | 사용하지 않음. button-primary를 씀. (쓰지 않음) |
| Tooltip | tooltip-* |  |  | 툴팁·토스트 안에서만 씀 (bg-small #FFFDE8, bg-toast #616161, bg-primary #00E2B9 등). |
| Status | status-badge | #FF7298 |  | 새 알림이 있음을 알리는 빨간 점 배지. |
| Content | unit-badge-01 ~ 15 |  |  | 유닛 배지 색. 유닛 배지 부품 안에서만 씀 (8~13은 2~7 색을 순환). |
| Collection | collection/* |  |  | 컬렉션 배지·화면 색. 컬렉션 부품 안에서만 씀. |

## Spacing

| 토큰 | 값 | 언제 |
|---|---|---|
| Spacing/screen-horizontal | 20 | 화면 좌우 바깥 여백 (콘텐츠 시작선). 리스트·카드 화면. 실제 화면 126곳 중 70곳. |
| Spacing/screen-horizontal-wide | 24 | 넓은 화면 좌우 여백. 온보딩·결과 화면 (34곳). |
| Spacing/section-gap | 24 | 큰 묶음과 묶음 사이. 제목 영역과 목록 사이. |
| Spacing/item-gap | 12 | 카드·리스트 줄 사이. |
| Spacing/card-padding | 12 | 카드·리스트 줄 안쪽 여백. 단어 칩, 듣는 중 표시 줄. |
| Spacing/card-padding-large | 16 | 큰 카드·시트 안쪽 여백. 바텀시트. |
| Spacing/inline-gap | 8 | 한 줄 안 요소 사이. 아이콘과 글자. |
| Spacing/inline-gap-small | 4 | 아주 가까운 요소 사이. 글자와 작은 화살표, 배지 안. |
| Spacing/chip-gap | 6 | 칩과 칩 사이. 리뷰 카테고리 칩. |

기본 값: Spacing/0·2·4·6·8·10·12·16·20·24

## Corner Radius

- Radius/4: 작은 칩
- Radius/8: 버튼·입력창
- Radius/12: 카드
- Radius/16: 큰 카드
- Radius/24: 시트 위
- Radius/30: 
- Radius/full: 원형·유리 칩 (글자 버튼에는 쓰지 않음)

## Shadow

- Shadow/Soft 12: 떠 있는 버튼
- Shadow/Soft 8: 작은 떠 있는 요소

## Text Style (Noto Sans)

| 스타일 | 굵기 | 크기/행간 | 메모 |
|---|---|---|---|
| Head 1/EB | 800 | 24/34 |  |
| Head 2/EB | 800 | 22/30 |  |
| Head 3/EB | 800 | 20/28 |  |
| Head 3/B | 700 | 20/28 |  |
| Head 3/M | 500 | 20/28 |  |
| Head 4/B | 700 | 18/26 |  |
| Head 4/M | 500 | 18/26 | 앱 코드에 아직 없음 |
| Head 5/B | 700 | 16/22 |  |
| Subtitle 1/B | 700 | 16/22 |  |
| Subtitle 1/M | 500 | 16/22 |  |
| Subtitle 1/R | 400 | 16/22 |  |
| Subtitle 2/B | 700 | 14/20 |  |
| Subtitle 2/M | 500 | 14/20 |  |
| Subtitle 2/R | 400 | 14/20 |  |
| Body 1/R | 400 | 16/22 |  |
| Body 2/R | 400 | 14/20 |  |
| Button 1/B | 700 | 16/22 |  |
| Button 1/M | 500 | 16/22 |  |
| Button 2/B | 700 | 14/20 |  |
| Button 2/M | 500 | 14/20 |  |
| Caption/M | 500 | 12/18 |  |
| Caption/R | 400 | 12/18 |  |
| Caption 2/B | 700 | 12/16 | 앱 코드에 아직 없음 |
| Caption 2/M | 500 | 12/16 | 앱 코드에 아직 없음 |
| Caption 2/R | 400 | 12/16 | 앱 코드에 아직 없음 |
| Overline/R | 400 | 10/16 |  |
| Number/EB | 800 | 32/40 | 큰 숫자 (스트릭·점수). 앱 코드에 아직 없음 |