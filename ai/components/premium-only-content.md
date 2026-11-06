# Premium/Only Content

묶음: 기능 전용 · Premium

프리미엄 전용 콘텐츠 안내 카드.

속성: state:default·highlight

- 스펙 (px, 기준 `state=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 372x175, 세로 정렬, 여백 위 0 · 오른 20 (Spacing/20) · 아래 0 · 왼 17 (토큰 없음), 간격 13 (토큰 없음)
    - Frame 2252: 207x50, 가로 정렬, 여백 위 30 (토큰 없음) · 오른 0 · 아래 0 · 왼 58 (토큰 없음)
      - Frame 2253: 149x20, 가로 정렬, 간격 4 (Spacing/4)
        - Premium Content: 125x20, 글자색 text-secondary, 글자 Subtitle 2 -B
        - Icon/Premium 20: 20x20, 부품 Icon/Premium 20
    - Frame 2251: 335x112, 가로 정렬, 간격 13 (토큰 없음)
      - Frame 2252: 335x112, 가로 정렬, 간격 양 끝 정렬
        - Premium Badge: 45x45, 가로 정렬, 여백 10 (Spacing/10), 간격 10 (Spacing/10), 모서리 10 (토큰 없음), 면 icon-bubble-background, 부품 Premium/Badge
        - Premium Only-content: 277x112, 세로 정렬, 여백 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 background-secondary + icon-bubble-background
  - 배리언트 `state=default`: 372x175, 글자 text-secondary
  - 배리언트 `state=highlight`: 372x175, 글자 text-secondary
  - 배리언트 `state=highlight` 자세히: 기준과 같음
  - ⚠ 토큰에 없는 간격 · 전체: 여백 17 → 가까운 값 Spacing/16
  - ⚠ 토큰에 없는 간격 · 전체: 간격 13 → 가까운 값 Spacing/12
  - ⚠ 토큰에 없는 간격 · Frame 2252: 여백 30 → 가까운 값 Spacing/24
  - ⚠ 토큰에 없는 간격 · Frame 2252: 여백 58 → 가까운 값 Spacing/24
  - ⚠ 옛 텍스트 스타일 · Premium Content: Subtitle 2 -B → Subtitle 2/B
  - ⚠ 토큰에 없는 간격 · Frame 2251: 간격 13 → 가까운 값 Spacing/12
  - ⚠ 토큰에 없는 모서리 · Premium Only-content: 모서리 14 → 가까운 값 Radius/12
