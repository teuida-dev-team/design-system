# Navigation/Nav Bar

묶음: 공통 · Navigation

화면 맨 위 묶음(상태바 + 헤더) 360x97. type으로 홈, 기타 화면 헤더를 고름. Home(old)는 예전 홈.

속성: type:home·other01·other02·other03·home(old)·top-nav / style:title-button·title-settings·progress-dot

- 스펙 (px, 기준 `type=home, style=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 360x97, 세로 정렬
    - Navigation/Status Bar: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
    - Navigation/Nav Bar Cell: 360x52, 가로 정렬, 여백 위아래 7 (토큰 없음) · 좌우 16 (Spacing/16), 간격 6 (Spacing/6), 면 background-secondary, 선 border-secondary, 부품 Navigation/Nav Bar Cell
  - 배리언트 `type=home, style=default`: 360x97, 글자 background-secondary
  - 배리언트 `type=other01, style=default`: 360x97
  - 배리언트 `type=other02, style=default`: 360x97
  - 배리언트 `type=other03, style=default`: 360x97
  - 배리언트 `type=home(old), style=default`: 360x97
  - 배리언트 `type=top-nav, style=title-button`: 360x95
  - 배리언트 `type=top-nav, style=title-settings`: 360x95
  - 배리언트 `type=top-nav, style=progress-dots`: 360x95
  - 배리언트 `type=top-nav, style=progress-bar`: 360x95
  - 배리언트 `type=other01, style=default` 자세히: 기준과 같음
  - 배리언트 `type=other02, style=default` 자세히 (기준과 다른 부분):
      - System/Status Bar iOS: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
  - 배리언트 `type=other03, style=default` 자세히 (기준과 다른 부분):
      - System/Status Bar iOS: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
  - 배리언트 `type=home(old), style=default` 자세히 (기준과 다른 부분):
      - System/Status Bar iOS: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
  - 배리언트 `type=top-nav, style=title-button` 자세히 (기준과 다른 부분):
    - 전체: 360x95, 세로 정렬
      - System/Status Bar iOS: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
      - Navigation/Top Nav: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 면 background-secondary, 선 border-secondary, 부품 Navigation/Top Nav
  - 배리언트 `type=top-nav, style=title-settings` 자세히 (기준과 다른 부분):
    - 전체: 360x95, 세로 정렬
      - System/Status Bar iOS: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
      - Navigation/Top Nav: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 간격 20 (Spacing/20), 면 background-secondary, 선 border-secondary, 부품 Navigation/Top Nav
  - 배리언트 `type=top-nav, style=progress-dots` 자세히 (기준과 다른 부분):
    - 전체: 360x95, 세로 정렬
      - System/Status Bar iOS: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
      - Navigation/Top Nav: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 간격 양 끝 정렬, 면 background-secondary, 선 border-secondary, 부품 Navigation/Top Nav
  - 배리언트 `type=top-nav, style=progress-bar` 자세히 (기준과 다른 부분):
    - 전체: 360x95, 세로 정렬
      - System/Status Bar iOS: 360x45, 면 background-secondary, 부품 System/Status Bar iOS
      - Navigation/Top Nav: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 간격 20 (Spacing/20), 면 background-secondary, 선 border-secondary, 부품 Navigation/Top Nav
