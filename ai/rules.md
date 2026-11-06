# 작업 규칙

목표는 **일관된 규칙 + 예외 최소화**예요. 100% 시스템화보다 다시 손볼 일이 적은 화면이 먼저예요.

## 어디를 기준으로 보나

| 무엇 | 기준 |
|---|---|
| 현행 화면 | Product Design `🧩 기능별 최신 화면` 페이지. 카드 캡션의 원본 링크가 최신 원본. 빨간 글씨 카드는 피그마에 없는 화면이라 앱 캡처를 보고 새로 만들어요 |
| 부품 | Design Library의 `Components` 페이지 → 이 사이트 [컴포넌트](components.html) |
| 색 | 라이브러리 변수 `Tokens` 컬렉션 → [토큰](tokens.html). Primitives(`Color/Gray/gray-400` 등)와 옛 색 스타일은 직접 쓰지 않아요 |
| 글자 | 텍스트 스타일 27개. 글꼴은 Noto Sans (이벤트 화면만 예외, 시스템 UI는 SF Pro) |
| 간격·모서리·그림자 | `Spacing/*`, `Radius/*`, `Shadow/Soft 12·8` |

스프린트 페이지는 위쪽일수록 최신이에요. 같은 화면 사본이 여러 페이지에 있으면 가장 위 페이지 것을 써요.

## 색 고르는 순서

1. **용도가 맞는 `Tokens` 변수.** 같은 색이어도 용도가 다르면 그 토큰을 빌려 쓰지 않아요.
2. 맞는 토큰이 없거나 한 번만 쓰는 색이면 **기본 색(Primitives)** 을 써요. 이때 화면·레이어·색·이유를 기록해서 알려요.
3. hex 직접 입력, 옛 색 스타일 새로 쓰기는 하지 않아요. 다크 모드 값은 건드리지 않아요 (앱은 아직 라이트 모드만 써요).
4. 다시 쓰이지 않는 그래픽(일러스트 안쪽, 장식 원)과 화면에 안 들어가는 색(정리용 라벨)은 토큰에 연결하지 않아요.
5. 피그마와 앱 코드 색이 다르면 **피그마가 기준**이에요.

### 무엇을 칠하나 → 어떤 토큰

| 칠하는 것 | 토큰 |
|---|---|
| 화면 바탕 / 카드·시트·다이얼로그 면 / 입력창·구분 면 | `background-primary` / `background-secondary` / `background-tertiary` |
| 기본 글자 / 보조 설명 / 힌트·메타 ("Unit 1", "Tap to view") | `text-primary` / `text-secondary` / `text-tertiary` |
| 강조 글자 (브랜드 민트) | `text-highlight` |
| 민트·남색 같은 진한 면이나 영상 위의 흰 글자 | `text-on-color` (`text-inactive` 아님) |
| 진한 면·사진 위의 흰 아이콘 | `icon-on-color` |
| 경고·에러·위험한 동작 (입력 에러, 로그아웃·삭제) | `text-alert` |
| 학습 결과 오답 / 정답 | `text-failed` / `text-correct` |
| 기본 / 보조 / 약한 보조 / 선택 안 된 탭 / 강조 아이콘 | `icon-primary` / `icon-secondary` / `icon-tertiary` / `icon-unselected` / `icon-highlight` |
| 구분선·카드 테두리 / 선택·포커스 테두리 | `border-secondary` / `border-highlight` |
| 버튼 면·버튼 글자 | `button-*`는 **버튼 부품 안에서만**. 버튼이 아닌 민트 글자는 `text-highlight` |
| 연한 민트 알약 버튼 ("Try Premium for Free") | 면 `button-highlight-soft` + 글자 `button-text-highlight` |
| 일부러 밝게 쓰는 민트 (열쇠 칩 테두리, Coming Soon 스티커) | `button-highlight` (브랜드 민트로 바꾸지 않음) |
| 이미지가 들어갈 빈 회색 카드 | `button-unfilled` |
| 잠긴·비활성 회색 원·버튼 | `button-inactive` |
| 툴팁·유닛 배지·컬렉션 | `tooltip-*`, `unit-badge-*`, `collection/*`는 그 부품 안에서만 |

- 아이콘은 아이콘 토큰(`icon-*`)으로 칠해요. 글자와 같은 회색이 필요해도 `text-*`를 쓰지 않아요.
- 한 가지 색 아이콘은 색 배리언트가 없어요. 놓은 뒤 Icon 토큰으로 칠해요. 여러 색이 섞인 아이콘(국기, 로고 등)은 색을 바꾸지 않아요.
- 아이콘 크기는 크기 배리언트를 골라요. 인스턴스를 늘리거나 줄여 쓰지 않아요.
- 리퀴드 글래스 탭바에서 선택 안 된 탭은 검정(애플 고정), 예전 탭바는 회색이에요. 스토리 탭은 유료라서 왕관 육각형(`tabicon=premium-only`)을 써요.

## 글자

- 항상 텍스트 스타일을 걸어요. 크기·굵기를 직접 지정하지 않아요.
- 맞는 스타일이 없으면 (크기 13, SemiBold 등) 가장 가까운 스타일을 쓰고 알려요.
- 언어별 글자 토큰은 아직 없어요.

## 콘텐츠가 먼저

- 간격 토큰은 기본값이에요. 간격 때문에 콘텐츠가 다 안 들어가면 간격을 줄이거나 토큰을 쓰지 않아도 돼요.
- 레슨·보캡·퀴즈 같은 학습 화면은 대부분 스크롤하지 않아요.
- 리스트·설정처럼 스크롤 되는 화면은 간격 토큰을 지켜요.
- 조정했으면 "콘텐츠 확보로 간격 조정"이라고 한 줄 남겨요.

## 하지 말 것 → 대신

| 하지 말 것 | 대신 |
|---|---|
| 글자 들어간 알약 버튼 | `Button/Full Width` (모서리 8) |
| hex 직접 입력·옛 색 스타일 | 용도 토큰 (없으면 Primitives + 알리기) |
| 임의 간격·모서리 (7, 14…) | Spacing·Radius 토큰 (콘텐츠 확보가 필요하면 예외) |
| 인스턴스 detach·로컬 부품 | 라이브러리 인스턴스 |
| 섹션 밖 참고 화면을 원본으로 | `🧩 기능별 최신 화면`, 섹션 안 화면 |
| 색만 다른 아이콘 새로 만들기 | 기본 아이콘 + Icon 토큰 |
| 사이트 [컴포넌트](components.html)에 없는 부품 | 쓰지 않아요. 꼭 필요하면 담당자에게 알리기 |
| 피그마 검색 결과의 `Product Design` 부품 | `Design Library` 것만 |
| 화면 안에 작업 메모·노란 스티키 | 설명은 전부 디스크립션으로 |

## 상황별 기준 부품

| 상황 | 쓸 부품 | 쓰지 않는 것 |
|---|---|---|
| 상태바 iOS / 안드로이드 | `System/Status Bar iOS` / `System/Status Bar Android` | 예전 Material 상태바 |
| 화면 맨 아래 홈 바 (iOS) | `System/Home Indicator iOS` | |
| 하위 화면 맨 위 (iOS 26) | `Navigation/Nav Bar iOS 26` | |
| 학습 화면 맨 위 | `Navigation/Top Nav` | |
| 탭 루트 화면 맨 아래 | `Navigation/Tab Bar Liquid Glass` (iOS 26), `Navigation/Tab Bar` | `Navigation/Tab Bar AOS` (예전) |
| 가운데 확인 창 | `Dialog/Basic` | `Dialog/Middle Preset` (예전) |
| 아래에서 올라오는 시트 | `Bottom Sheet/Basic` + Content Slot | 예전 시트 프리셋 |
| 글자 탭 (밑줄) | `Navigation/Text Tab` | |
| 동그란 아이콘 버튼 | `Button/Circle Icon` | |
| 화면 아래 주요 행동 | `Button/Full Width` (fill은 한 화면에 하나) | 알약 버튼 |
| 페이지 점 / 단계 진행 | `Progress/Pagination Dots` / `Progress/Step Bar`·`Step Dots`·`Pagination Bar` | |

버튼은 종류가 많아서 2차에 정리해요. 그 전까지는 같은 화면 최신 원본에 쓰인 버튼을 그대로 써요.

## 이름 규칙

- **Product Design 페이지**: 기획서 이름 그대로, 한글 + 필요한 명사만 영어. 형식 `YY.MM - Sprint XX - 기능명`. 영문으로 번역하지 않아요.
- **부품**: 영어 `분류/이름` (예: `Button/Full Width`, `Icon/Close 24`). 기능 전용은 `기능/무엇` (예: `Curriculum/Unit Title`). 속성 이름·값은 소문자 (`state=enabled`).
- **레이어**: `Group 1673` 같은 기본 이름을 두지 않고 역할로 붙여요 (예: `Vocab Header`).
- **화면(프레임)**: 짧게 `{콘텐츠} {유형} {상태}` (예: `보캡 B 오답`, `퀵리뷰 문장 정답`). 설명 문장이나 기호 나열을 넣지 않아요.
- Curriculum = 레슨 탭 메인 (그 안에 레슨·보캡·프랙티스·리뷰퀴즈).

## 알려진 빈칸 (아직 라이브러리에 없음)

시안에 필요하면 가장 가까운 것을 쓰고 "디자인 시스템 빈칸"으로 알려요. 새 토큰·스타일·부품을 라이브러리에 마음대로 추가하지 않아요.

- **색**: 영상·다크 배경(#000000), 빈 별·꺼진 토글 회색(#C8C8C8), 팝업 뒤 막 30%, 프리미엄 남색(#293649)·그라디언트, 비활성·잠금 덮개, 어두운 배경 위 보조 글자(흰색 60%·30%), 오답 구분선(#FFDFDF), 입력창 안내 글자
- **부품**: 자막 말풍선, 학습 문장, Listening(마이크), 결과 바, 미션 카드
- **글자**: 10/14, 배지 라벨
