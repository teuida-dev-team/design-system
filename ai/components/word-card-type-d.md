# Word Card/Type D

묶음: 여러 기능 패턴 · Word Card

단어 카드 D형 (힌트 보기·소리 버튼). 쓰는 곳(실제 앱): 리뷰 · 보캡.

속성: hint:on·off / audio:off·on

- 스펙 (px, 기준 `hint=off, audio=on`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 307x420, 세로 정렬, 여백 위 20 (Spacing/20) · 오른 20 (Spacing/20) · 아래 24 (Spacing/24) · 왼 20 (Spacing/20), 간격 10 (Spacing/10), Corner Radius 24 (Radius/24), 면 background-secondary
    - Frame 2070: 227x227, 세로 정렬
      - VocabIllust: 227x227
        - Student_Female: 106x166
    - Lesson/Volume: 32x32, 부품 Audio/Volume
    - Frame 2072: 259x120, 세로 정렬, 여백 위아래 24 (Spacing/24) · 좌우 20 (Spacing/20), Corner Radius 24 (Radius/24), 면 background-primary
      - Frame 2421: 175x40, 가로 정렬, 여백 위아래 10 (Spacing/10) · 좌우 20 (Spacing/20), 간격 6 (Spacing/6), Corner Radius 12 (Radius/12), 면 gray-100 (기본 색)
        - Icon/Search 18: 18x18, 부품 Icon/Search 18
        - Tap to view hint: 111x20, 글자색 text-tertiary, 글자 Button 2/B
  - 배리언트 `hint=off, audio=on`: 307x420, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `hint=off, audio=off`: 307x420, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `hint=on, audio=on`: 307x420, 면 background-secondary, 글자 text-secondary
  - 배리언트 `hint=on, audio=off`: 307x420, 면 background-secondary, 글자 text-secondary
  - 배리언트 `hint=off, audio=off` 자세히 (기준과 다른 부분):
      - Frame 2070: 259x347, 세로 정렬
        - Frame 2072: 259x120, 세로 정렬, 여백 위아래 24 (Spacing/24) · 좌우 20 (Spacing/20), Corner Radius 24 (Radius/24), 면 background-primary
          - Frame 2421: 175x40, 가로 정렬, 여백 위아래 10 (Spacing/10) · 좌우 20 (Spacing/20), 간격 6 (Spacing/6), Corner Radius 12 (Radius/12), 면 gray-100 (기본 색)
      - Lesson/Volume: 32x32, 부품 Audio/Volume
  - 배리언트 `hint=on, audio=on` 자세히 (기준과 다른 부분):
      - Frame 2072: 227x227, 세로 정렬
      - Frame 2071: 259x120, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), Corner Radius 24 (Radius/24), 면 background-primary
        - Frame 2076: 211x78, 세로 정렬, 간격 8 (Spacing/8)
          - icon / heroicons / Solid: 24x24, 부품 icon / heroicons / Solid / volume-up
          - Frame 2075: 211x46, 세로 정렬
      - Lesson/Volume: 32x32, 부품 Audio/Volume
  - 배리언트 `hint=on, audio=off` 자세히 (기준과 다른 부분):
      - Frame 2072: 227x227, 세로 정렬
      - Frame 2071: 259x120, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), Corner Radius 24 (Radius/24), 면 background-primary
        - Frame 2076: 211x78, 세로 정렬, 간격 8 (Spacing/8)
          - icon / heroicons / Solid: 24x24, 부품 icon / heroicons / Solid / volume-up
          - Frame 2075: 211x46, 세로 정렬
      - Lesson/Volume: 32x32, 부품 Audio/Volume
