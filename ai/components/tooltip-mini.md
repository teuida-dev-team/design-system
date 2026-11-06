# Tooltip/Mini

묶음: 공통 · Tooltip

작은 말풍선 툴팁. • 언제: 처음 보는 기능 안내 (꼬리 방향 선택) • 쓰지 말 것: 긴 설명 (→ Bottom Sheet) • 쓰는 곳(실제 앱): 커뮤니티.

속성: type:bottom·left·right·top·bottom / left

- 스펙 (px, 기준 `type=bottom`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 121x48, 세로 정렬
    - box: 121x40, 가로 정렬, 여백 12 (Spacing/12), 간격 10 (Spacing/10), 모서리 6 (토큰 없음), 면 tooltip-bg-small
      - Tooltip minimum: 97x16, 글자색 text-primary, 글자 Caption - R
    - Frame 659: 14x8, 세로 정렬, 간격 10 (Spacing/10)
      - tale: 14x8, 면 yellow-50 (기본 색)
  - 배리언트 `type=bottom`: 121x48, 글자 text-primary
  - 배리언트 `type=top`: 121x48, 글자 text-primary
  - 배리언트 `type=right`: 129x40, 글자 text-primary
  - 배리언트 `type=left`: 129x40, 글자 text-primary
  - 배리언트 `type=bottom / left`: 121x48, 글자 text-primary
  - 배리언트 `type=top` 자세히 (기준과 다른 부분):
      - Frame 659: 14x8, 세로 정렬, 간격 10 (Spacing/10)
        - tale: 14x8, 면 yellow-50 (기본 색)
      - box: 121x40, 가로 정렬, 여백 12 (Spacing/12), 간격 10 (Spacing/10), 모서리 6 (토큰 없음), 면 tooltip-bg-small
        - Tooltip minimum: 97x16, 글자색 text-primary, 글자 Caption - R
  - 배리언트 `type=right` 자세히 (기준과 다른 부분):
    - 전체: 129x40, 가로 정렬
  - 배리언트 `type=left` 자세히 (기준과 다른 부분):
    - 전체: 129x40, 가로 정렬
      - Frame 659: 14x8, 세로 정렬, 간격 10 (Spacing/10)
        - tale: 14x8, 면 yellow-50 (기본 색)
      - box: 121x40, 가로 정렬, 여백 12 (Spacing/12), 간격 10 (Spacing/10), 모서리 6 (토큰 없음), 면 tooltip-bg-small
        - Tooltip minimum: 97x16, 글자색 text-primary, 글자 Caption - R
  - 배리언트 `type=bottom / left` 자세히 (기준과 다른 부분):
      - Frame 659: 54x8, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 10 (Spacing/10)
