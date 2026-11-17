# Claude용 안내

팀원이 쓰는 Claude가 이 사이트를 읽고 피그마에서 작업하는 방법이에요. 사람이 읽어도 돼요.

## 읽는 순서

1. [`llms.txt`](llms.txt)를 먼저 읽어요. 사이트 전체 목차와 꼭 지킬 것이 있어요.
2. 작업에 필요한 문서만 골라 읽어요. 모든 문서는 Markdown으로도 있어요 (`ai/` 폴더).
3. 부품을 고를 때는 [`data/components.json`](data/components.json)에서 이름으로 찾아요. **여기 있는 부품만 써요.**
4. 고른 부품의 스펙 파일을 읽어요: `ai/components/{이름}.md` (사람용 글) 또는 `data/specs/{이름}.json` (데이터). 부분별 크기·여백·간격·Corner Radius·토큰, 배리언트별 차이가 있어요. 이것만 보고 앱 코드나 화면을 만들 수 있어요. 피그마를 읽지 않아요.
5. 토큰 값은 [`tokens/tokens.json`](tokens/tokens.json). 앱 코드에서는 앱에 이미 있는 상수를 써요.

## 왜 이렇게 하나

피그마 검색(`search_design_system`) 결과에는 부품 이름과 설명만 나오고, 라이브러리의 어느 페이지·섹션에 있는지는 안 나와요. 그래서 검색만으로는 지금 써도 되는 부품인지 알기 어려워요. 이 사이트의 부품 목록이 그 기준표예요.

## 판단 규칙

| components.json | 판단 |
|---|---|
| 있음, `status: use` | 써도 돼요 |
| 있음, `status: check` | 쓰기 전에 사용자에게 확인 |
| 없음 | 쓰지 않아요. 목록에서 같은 종류를 찾고, 꼭 필요하면 사용자에게 알려요 |

- 검색 결과의 `libraryName`이 `Design Library`인 것만 써요. `Product Design` 결과는 작업 파일의 로컬 부품이에요.

## 데이터 형식

`data/components.json`의 항목 하나:

```json
{"name": "Button/Full Width", "group": "공통", "category": "Button",
 "status": "use", "description": "…", "variants": "size:48·54 / …", "image": "img/693-7850.png",
 "spec": "data/specs/button-full-width.json", "spec_md": "ai/components/button-full-width.md"}
```

- 스펙 줄의 값: `10(10)` = 토큰(Spacing/10), 숫자만 = 토큰 없음, `❌#hex` = 색 직접 입력. 토큰이 없는 값은 적힌 숫자·색 그대로 만들어요. 토큰으로 바꿀지는 디자이너가 정해요.
- 피그마 파일 위치·노드 번호는 공개 사이트에 넣지 않았어요.
