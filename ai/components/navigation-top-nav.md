# Navigation/Top Nav

묶음: 공통 · Navigation

학습 화면 상단 줄 (진행 점·진행 막대, 설정·닫기). • 언제: 레슨·퀴즈처럼 진행이 보이는 화면 맨 위 • 쓰지 말 것: 일반 하위 화면 (→ Nav Bar iOS 26) • 함께: Template/Quiz Screen, Progress/Step Bar

속성: style:title-button·title-settings·progress-dots·progress-bar

- 스펙 (px, 기준 `style=title-button`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 면 background-secondary, 선 border-secondary
    - Frame 1693: 100x24, 가로 정렬
      - Icon/Chevron Left 24: 24x24, 부품 Icon/Chevron Left 24
      - Button: 53x22, 글자색 text-secondary, 글자 BUTTON 1 - M
    - Group 1629: 128x24
      - Icon/Empty 24: 12x24, 부품 Icon/Empty 24
      - Text: 90x22, 글자색 text-primary, 글자 Head 5 - B
      - Icon/Empty 24: 12x24, 부품 Icon/Empty 24
    - Frame 1693: 100x24, 가로 정렬, 간격 8 (Spacing/8)
      - Button: 53x22, 글자색 text-secondary, 글자 BUTTON 1 - M
      - Icon/Close 24: 24x24, 부품 Icon/Close 24
  - 배리언트 `style=title-button`: 360x50, 면 background-secondary, 선 border-secondary, 글자 text-secondary
  - 배리언트 `style=title-settings`: 360x50, 면 background-secondary, 선 border-secondary, 글자 text-primary
  - 배리언트 `style=progress-dots`: 360x50, 면 background-secondary, 선 border-secondary
  - 배리언트 `style=progress-bar`: 360x50, 면 background-secondary, 선 border-secondary
  - 배리언트 `style=title-settings` 자세히 (기준과 다른 부분):
    - 전체: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 간격 20 (Spacing/20), 면 background-secondary, 선 border-secondary
      - Icon/Chevron Left 24: 24x24, 부품 Icon/Chevron Left 24
      - Group 1629: 240x24
        - Icon/Empty 24: 23x24, 부품 Icon/Empty 24
        - Text: 169x22, 글자색 text-primary, 글자 Head 5 - B
        - Icon/Tab Setting 24: 23x24, 부품 Icon/Tab Setting 24
      - Icon/Close 24: 24x24, 부품 Icon/Close 24
  - 배리언트 `style=progress-dots` 자세히 (기준과 다른 부분):
    - 전체: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 간격 양 끝 정렬, 면 background-secondary, 선 border-secondary
      - Icon/Settings 24: 24x24, 부품 Icon/Settings 24
      - Progress/Bar: 181x10, 가로 정렬, 간격 9 (토큰 없음), 부품 Progress/Step Dots
      - Icon/Close 24: 24x24, 부품 Icon/Close 24
  - 배리언트 `style=progress-bar` 자세히 (기준과 다른 부분):
    - 전체: 360x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 간격 20 (Spacing/20), 면 background-secondary, 선 border-secondary
      - Icon/Settings 24: 24x24, 부품 Icon/Settings 24
      - Progress/Bar 2: 240x6, 가로 정렬, 간격 8 (Spacing/8), 부품 Progress/Step Bar
      - Icon/Close 24: 24x24, 부품 Icon/Close 24
  - ⚠ 토큰에 없는 간격 · 전체: 여백 13 ×2 → 가까운 값 Spacing/12
  - ⚠ 옛 텍스트 스타일 · Button: BUTTON 1 - M ×2 → Button 1/M
  - ⚠ 옛 텍스트 스타일 · Text: Head 5 - B → Head 5/B
