# Badge/Key Count

묶음: 공통 · Badge

가진 열쇠 개수 배지. • 언제: 상단 바의 열쇠 개수 • 함께: Navigation/Nav Bar Cell • 쓰는 곳(실제 앱): 리뷰.

속성: type:premium·storykey·lessonkey

- 스펙 (px, 기준 `type=storykey`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 41x30, 가로 정렬, 간격 10 (Spacing/10)
    - Frame 1565: 41x30, 가로 정렬, 여백 위 3 (토큰 없음) · 오른 5 (토큰 없음) · 아래 3 (토큰 없음) · 왼 2 (Spacing/2), 간격 1 (토큰 없음), Corner Radius full (Radius/full)
      - Icon/Story Key 24: 24x24, 부품 Icon/Story Key 24
      - 0: 9x20, 글자색 icon-primary, 글자 Subtitle 2 -B
  - 배리언트 `type=storykey`: 41x30, 글자 icon-primary
  - 배리언트 `type=premium`: 47x30
  - 배리언트 `type=lessonkey`: 41x30, 글자 icon-primary
  - 배리언트 `type=premium` 자세히 (기준과 다른 부분):
    - 전체: 47x30, 가로 정렬, 간격 10 (Spacing/10)
      - Frame 1565: 47x30, 가로 정렬, 여백 위 3 (토큰 없음) · 오른 5 (토큰 없음) · 아래 3 (토큰 없음) · 왼 2 (Spacing/2), Corner Radius full (Radius/full)
        - Frame 2920: 16x20
          - Subtract: 14x8, 면 icon-primary
  - 배리언트 `type=lessonkey` 자세히 (기준과 다른 부분):
    - 전체: 41x30, 세로 정렬, 간격 10 (Spacing/10)
        - Icon/Lesson Key 24: 24x24, 부품 Icon/Lesson Key 24
