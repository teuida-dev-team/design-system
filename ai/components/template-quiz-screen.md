# Template/Quiz Screen

묶음: 화면 뼈대 · Template

화면 뼈대: 퀴즈 화면. • 언제: 레슨·보캡·리뷰 퀴즈 화면을 시작할 때. 한 화면에 다 들어가야 함(스크롤 금지) • 쓰지 말 것: 리스트 화면 (→ Template/List Screen) • 함께: Top Nav, Word Card, Button/Choice, Button/Full Width

- 스펙 (px; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 375x812, 세로 정렬, 면 background-primary
    - System/Status Bar iOS: 375x44, 면 background-secondary, 부품 System/Status Bar iOS
    - Navigation/Top Nav: 375x50, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 16 (Spacing/16), 간격 20 (Spacing/20), 면 background-secondary, 선 border-secondary, 부품 Navigation/Top Nav
    - Content: 375x618, 세로 정렬, 여백 위 24 (토큰 없음) · 오른 20 (screen-horizontal) · 아래 0 · 왼 20 (screen-horizontal), 간격 24 (section-gap)
      - 문제 안내 문구: 121x28, 글자색 text-primary, 글자 Head 3/B
      - slot · 문제 카드 (Word Card/: 335x220, 세로 정렬, 여백 위아래 0 · 좌우 12 (토큰 없음), 모서리 8 (토큰 없음), 면 #8A5CF5 (토큰 없음) 8%, 선 #8A5CF5 (토큰 없음) 1
        - 문제 카드 (Word Card/Basic ·: 309x32, 글자색 #734DD9 (토큰 없음), 글자 Medium 13 (스타일 없음)
      - slot · 보기 (Button/Choice: 335x240, 세로 정렬, 여백 위아래 0 · 좌우 12 (토큰 없음), 모서리 8 (토큰 없음), 면 #8A5CF5 (토큰 없음) 8%, 선 #8A5CF5 (토큰 없음) 1
        - 보기 (Button/Choice 2~4개, : 309x16, 글자색 #734DD9 (토큰 없음), 글자 Medium 13 (스타일 없음)
    - Bottom CTA: 375x100, 세로 정렬, 여백 위 12 (토큰 없음) · 오른 20 (screen-horizontal) · 아래 34 (토큰 없음) · 왼 20 (screen-horizontal)
      - Button/Full Width: 335x54, 세로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 18 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 green-500 (기본 색), 선 border-primary 1, 부품 Button/Full Width
  - ⚠ 간격 토큰 안 걸림 · Content: 여백 24 → Spacing/24 연결
  - ⚠ 텍스트 스타일 없음 · 문제 카드 (Word Card/Basic ·: Medium 13 → Subtitle 2/M (크기 13→14)
  - ⚠ 색 직접 입력 · 문제 카드 (Word Card/Basic ·: #734DD9 → 맞는 토큰 없음 (빈칸)
  - ⚠ 텍스트 스타일 없음 · 보기 (Button/Choice 2~4개, : Medium 13 → Subtitle 2/M (크기 13→14)
  - ⚠ 색 직접 입력 · 보기 (Button/Choice 2~4개, : #734DD9 → 맞는 토큰 없음 (빈칸)
  - ⚠ 간격 토큰 안 걸림 · Bottom CTA: 여백 12 → Spacing/12 연결
  - ⚠ 토큰에 없는 간격 · Bottom CTA: 여백 34 → 가까운 값 Spacing/24
