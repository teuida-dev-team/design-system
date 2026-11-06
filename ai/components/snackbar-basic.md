# Snackbar/Basic

묶음: 공통 · Snackbar

화면 아래 안내 + 행동 버튼. • 언제: 되돌리기처럼 바로 할 행동이 붙는 안내 • 쓰지 말 것: 행동 없는 짧은 안내 (→ Toast/Basic) • 쓰는 곳: 실제 앱 화면에서는 아직 확인 안 됨.

- 스펙 (px; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 168x66, 세로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 20 (Spacing/20), 간격 10 (Spacing/10), 모서리 6 (토큰 없음), 면 tooltip-bg-toast 2
    - Frame 1956: 128x38, 가로 정렬, 간격 128 (토큰 없음)
      - Frame 1957: 128x38, 세로 정렬
        - Text / titlebar: 115x20, 글자색 tooltip-text-toast-primary, 글자 Subtitle 2/M
        - Text / titlebar: 128x18, 글자색 tooltip-text-toast-secondary, 글자 Caption/M
  - ⚠ 토큰에 없는 간격 · 전체: 여백 14 ×2 → 가까운 값 Spacing/12
  - ⚠ 토큰에 없는 모서리 · 전체: 모서리 6 → 가까운 값 Radius/4
  - ⚠ 토큰에 없는 간격 · Frame 1956: 간격 128 → 가까운 값 Spacing/24
