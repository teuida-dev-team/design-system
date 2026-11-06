# Premium/Badge

묶음: 기능 전용 · Premium

프리미엄 배지 (기본·완료).

속성: state:default·done

- 스펙 (px, 기준 `state=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 45x45, 가로 정렬, 여백 10 (Spacing/10), 간격 10 (Spacing/10), 모서리 10 (토큰 없음), 면 icon-on-color
    - ic_premium-only: 25x25
      - Group 1720: 23x25
        - Star 8: 23x25, 선 gray-300 (기본 색) 10% 4.09743595123291
        - Star 9: 23x25, 선 gray-300 (기본 색) 15% 2.048717975616455
        - Exclude: 23x25, 면 icon-inactive
  - 배리언트 `state=default`: 45x45, 면 icon-on-color
  - 배리언트 `state=done`: 45x45, 면 icon-bubble-background
  - 배리언트 `state=done` 자세히 (기준과 다른 부분):
    - 전체: 45x45, 가로 정렬, 여백 10 (Spacing/10), 간격 10 (Spacing/10), 모서리 10 (토큰 없음), 면 icon-bubble-background
          - Star 8: 23x25, 선 blue-300 (기본 색) 10% 4.09743595123291
          - Star 9: 23x25, 선 blue-300 (기본 색) 15% 2.048717975616455
          - Exclude: 23x25, 면 icon-bubble
  - ⚠ 토큰에 없는 모서리 · 전체: 모서리 10 → 가까운 값 Radius/8
  - ⚠ 기본 색 사용 · Star 8: gray-300 → icon-inactive · button-inactive · gradient-unfilled 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · Star 9: gray-300 → icon-inactive · button-inactive · gradient-unfilled 중 용도에 맞는 것
