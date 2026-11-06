# Input/Switch AOS

묶음: 공통 · Input

안드로이드 스위치 (on·off). • 언제: 설정 켜기·끄기 • 쓰는 곳(실제 앱): 레슨 · 설정.

속성: state:off·on

- 스펙 (px, 기준 `state=off`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 50x32
    - status: 44x32
    - Group 1587: 38x20
      - switch/bar: 38x12, 면 icon-unselected
      - switch/handle: 20x20, 면 icon-unselected
  - 배리언트 `state=off`: 50x32
  - 배리언트 `state=on`: 50x32
  - 배리언트 `state=on` 자세히 (기준과 다른 부분):
      - Group 1586: 38x20
        - Rectangle 248: 38x12, 면 green-200 (기본 색)
        - Rectangle 251: 20x20, 면 icon-highlight
      - status: 44x32
