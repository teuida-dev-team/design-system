# Chip/Glass Category

묶음: 공통 · Chip

iOS 26 유리 카테고리 칩 (기본·선택). • 언제: 리스트 위 카테고리 필터 (커뮤니티·리뷰) • 쓰지 말 것: 상태 표시만 할 때 (→ Badge), iOS 26 이전 모양 화면 (→ Chip/Filter) • 함께: Template/List Screen

속성: style:community·review / state:default·selected

- 스펙 (px, 기준 `style=community, state=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 92x34, 가로 정렬, 여백 위아래 7 (토큰 없음) · 좌우 14 (토큰 없음), 모서리 full (Radius/full)
    - Fill + Shadow: 92x34, 모서리 full (Radius/full), 면 black (기본 색) 25% + button-second-primary 25% + #444444 (토큰 없음) 60% + #F8F8F8 (토큰 없음) 20%
    - Glass Effect: 92x34, 모서리 full (Radius/full)
    - Category: 64x20, 글자색 text-primary, 글자 Subtitle 2/B
  - 배리언트 `style=community, state=default`: 92x34, 글자 text-primary
  - 배리언트 `style=community, state=selected`: 92x34, 글자 text-on-color
  - 배리언트 `style=review, state=default`: 96x36, 글자 text-secondary
  - 배리언트 `style=review, state=selected`: 96x36, 글자 text-on-color
  - 배리언트 `style=community, state=selected` 자세히 (기준과 다른 부분):
      - Fill + Shadow: 92x34, 모서리 full (Radius/full), 면 button-primary
      - Category: 64x20, 글자색 text-on-color, 글자 Subtitle 2/B
  - 배리언트 `style=review, state=default` 자세히 (기준과 다른 부분):
    - 전체: 96x36, 가로 정렬, 여백 위아래 8 (Spacing/8) · 좌우 16 (Spacing/16), 모서리 full (Radius/full)
      - Fill + Shadow: 96x36, 모서리 full (Radius/full), 면 black (기본 색) 25% + button-second-primary 25% + #444444 (토큰 없음) 60% + #F8F8F8 (토큰 없음) 20%
      - Glass Effect: 96x36, 모서리 full (Radius/full)
      - Category: 64x20, 글자색 text-secondary, 글자 Subtitle 2/B
  - 배리언트 `style=review, state=selected` 자세히 (기준과 다른 부분):
    - 전체: 96x36, 가로 정렬, 여백 위아래 8 (Spacing/8) · 좌우 16 (Spacing/16), 모서리 full (Radius/full)
      - Fill + Shadow: 96x36, 모서리 full (Radius/full), 면 button-primary
      - Glass Effect: 96x36, 모서리 full (Radius/full)
      - Category: 64x20, 글자색 text-on-color, 글자 Subtitle 2/B
