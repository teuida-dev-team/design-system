# Onboarding/Interest Item

묶음: 기능 전용 · Onboarding

커뮤니티 온보딩 선택지 한 줄 327x74. 예: 가입 경로 Instagram, TikTok.

속성: state:default·selected

- 스펙 (px, 기준 `state=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 327x74, 세로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 18 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 8 (Radius/8), 면 background-secondary
    - Frame 1905: 291x32, 가로 정렬, 간격 14 (토큰 없음)
      - Icon/Travel 32: 32x32, 부품 Icon/Travel 32
      - Frame 1904: 245x22, 세로 정렬
        - Text / titlebar: 245x22, 글자색 button-text-secondary, 글자 Subtitle 1/B
  - 배리언트 `state=default`: 327x74, 면 background-secondary, 글자 button-text-secondary
  - 배리언트 `state=selected`: 327x74, 면 button-primary, 글자 button-text-tertiary
  - 배리언트 `state=selected` 자세히 (기준과 다른 부분):
    - 전체: 327x74, 세로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 18 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 8 (Radius/8), 면 button-primary
          - Text / titlebar: 245x22, 글자색 button-text-tertiary, 글자 Subtitle 1/B
