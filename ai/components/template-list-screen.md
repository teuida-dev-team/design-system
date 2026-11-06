# Template/List Screen

묶음: 화면 뼈대 · Template

화면 뼈대: 리스트 화면. • 언제: 배운 표현·피드·설정처럼 리스트가 반복되는 화면을 시작할 때 • 쓰지 말 것: 학습(퀴즈) 화면 (→ Template/Quiz Screen) • 함께: Nav Bar iOS 26, Chip/Glass Category, Tab Bar Liquid Glass

- 스펙 (px; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 375x812, 세로 정렬, 면 background-primary
    - Navigation/Nav Bar iOS 2: 375x101, 세로 정렬, 면 background-secondary, 선 border-secondary, 부품 Navigation/Nav Bar iOS 26
    - Content: 375x623, 세로 정렬, 여백 위 16 (토큰 없음) · 오른 20 (screen-horizontal) · 아래 0 · 왼 20 (screen-horizontal), 간격 12 (item-gap)
      - slot · 필터·정렬 줄 (Chip/Gla: 335x36, 세로 정렬, 여백 위아래 0 · 좌우 12 (토큰 없음), 모서리 8 (토큰 없음), 면 #8A5CF5 (토큰 없음) 8%, 선 #8A5CF5 (토큰 없음) 1
        - 필터·정렬 줄 (Chip/Glass Cate: 309x16, 글자색 #734DD9 (토큰 없음), 글자 Medium 13 (스타일 없음)
      - slot · 리스트 (Review/List : 335x559, 세로 정렬, 여백 위아래 0 · 좌우 12 (토큰 없음), 모서리 8 (토큰 없음), 면 #8A5CF5 (토큰 없음) 8%, 선 #8A5CF5 (토큰 없음) 1
        - 리스트 (Review/List Item, L: 309x16, 글자색 #734DD9 (토큰 없음), 글자 Medium 13 (스타일 없음)
    - Tab Bar Area: 375x88, 세로 정렬, 여백 위 0 · 오른 0 · 아래 24 (토큰 없음) · 왼 0
      - Navigation/Tab Bar Liqui: 343x64, 가로 정렬, 여백 4 (Spacing/4), 모서리 full (Radius/full), 부품 Navigation/Tab Bar Liquid Glass
