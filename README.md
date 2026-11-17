# TEUIDA 디자인 시스템 사이트 (초안)

- 열기: `index.html`을 브라우저로 열면 돼요.
- 원본 데이터: `build/` (components.json · tokens.json · archive.json · content/*.md · site.css)
- 다시 만들기: 이 폴더에서 `python3 build/build.py` (부품 그림은 `img/`)
- 공개 사이트라 넣지 않은 것: 피그마 파일 키·노드 번호·링크, 사람 이름, 앱 코드 이름, 내 컴퓨터 경로
- 사람 얼굴 가리기: `python3 build/blur_faces.py` (원본 `build/orig/`, 좌표 `build/face_regions.json`). 썸네일·아바타처럼 테두리가 닫히는 사진 자리는 **회색 박스**로 바꾸고, 전면 영상처럼 자리가 안 닫히는 곳은 얼굴만 흐리게 함. TEUIDA 일러스트를 얼굴로 잘못 잡은 파일은 `SKIP_FILES`에 적어 원본 그대로 둠. 화면 이미지를 새로 뽑으면 **원본을 build/orig에 다시 복사하고 좌표를 다시 잡은 뒤** 반드시 한 번 돌릴 것
- 아이콘 배경: `python3 build/icon_bg.py` (rsvg-convert 필요). SVG를 실제로 그려 잉크 휘도를 재고 어두운/밝은 배경 중 WCAG 대비가 높은 쪽을 골라 `build/icons_bg.json`에 적음. 아이콘을 새로 뽑으면 다시 돌릴 것
- 스트릭 "조건 넣고 보기" 칸: 배리언트 위치표 `build/streak_extract.py` → `build/streak_raw.json`, 칸 만드는 코드 `build/streak_section.py`. 좌표는 피그마 스트릭 컴포넌트 세트를 읽어 적은 값이라, 세트를 고치면 좌표를 다시 읽고 그림(`img/*.png`)도 다시 뽑을 것
- 흰 스트릭 아이콘 그림: `python3 build/streak_white_on_dark.py` (PIL 필요). 세트 바탕이 밝아서 안 보이는 `Streak/Icon 40 White`를 어두운 바탕에 올린 `img/1-3374-dark.png`를 만듦
- 검색 차단: 모든 html에 `noindex,nofollow` + `robots.txt`. 링크를 아는 사람은 볼 수 있음 (검색에만 안 걸림)
- Claude가 읽는 곳: `llms.txt` → `ai/*.md`, `data/*.json`
- `build/`, `README.md`는 올리지 않아도 돼요 (사이트 화면에 안 쓰임)
- 피그마에서 다시 뽑기: 부품 스펙 `build/spec_extract.js`, 배리언트 차이 `build/variant_extract.js` (`__IDS__` 치환, 읽기 전용). 결과는 `build/specs_raw.json`·`variants_raw.json`
- 현행 화면: `build/screens_raw.json` + `screens/` (커뮤니티·프로필은 사용자 정보 때문에 앱 캡처 뺌)
- 아이콘: `assets/icons/*.svg` (`build/icons_index.json`)
