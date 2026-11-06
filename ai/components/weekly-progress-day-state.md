# Weekly Progress/Day State

묶음: 기능 전용 · Weekly Progress

위클리 프로그레스 하루 칸 상태.

속성: state:completed·default·potion / day-type:milestone·daily

- 스펙 (px, 기준 `state=default, day-type=daily`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 40x40
    - Rectangle 41563: 40x40, 모서리 15 (토큰 없음), 면 gray-200 (기본 색)
    - Frame: 20x20
      - Vector: 11x11, 면 white (기본 색)
      - Vector: 11x11, 면 white (기본 색)
      - Vector: 0x10, 선 white (기본 색) 2.0833332538604736
  - 배리언트 `state=completed, day-type=daily`: 40x40
  - 배리언트 `state=potion, day-type=daily`: 40x40
  - 배리언트 `state=default, day-type=daily`: 40x40
  - 배리언트 `state=default, day-type=milestone`: 40x40
  - 배리언트 `state=completed, day-type=milestone`: 40x40
  - 배리언트 `state=potion, day-type=milestone`: 40x40
  - 배리언트 `state=completed, day-type=daily` 자세히 (기준과 다른 부분):
      - Rectangle 41563: 40x40, 모서리 15 (토큰 없음), 면 green-100 (기본 색)
        - Vector: 11x11, 면 green-500 (기본 색)
        - Vector: 11x11, 면 green-500 (기본 색)
        - Vector: 0x10, 선 green-500 (기본 색) 2.0833332538604736
  - 배리언트 `state=potion, day-type=daily` 자세히 (기준과 다른 부분):
      - Rectangle 41563: 40x40, 모서리 15 (토큰 없음), 면 icon-bubble-background
      - Vector: 20x23, 면 icon-bubble
  - 배리언트 `state=default, day-type=milestone` 자세히 (기준과 다른 부분):
      - Union: 40x40, 면 gray-200 (기본 색)
        - Ellipse 333: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 335: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 334: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 336: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 337: 16x16, 면 yellow-200 (기본 색)
      - Union: 15x18, 면 gray-350 (기본 색)
        - Rectangle 64: 15x11, 면 background-secondary
        - Rectangle 65 (Stroke): 10x7, 면 background-secondary
  - 배리언트 `state=completed, day-type=milestone` 자세히 (기준과 다른 부분):
      - Union: 40x40, 면 green-100 (기본 색)
        - Ellipse 333: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 335: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 334: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 336: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 337: 16x16, 면 yellow-200 (기본 색)
      - Frame: 20x20
        - Vector: 11x11, 면 green-500 (기본 색)
        - Vector: 11x11, 면 green-500 (기본 색)
        - Vector: 0x10, 선 green-500 (기본 색) 2.0833332538604736
  - 배리언트 `state=potion, day-type=milestone` 자세히 (기준과 다른 부분):
      - Union: 40x40, 면 gray-200 (기본 색)
        - Ellipse 333: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 335: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 334: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 336: 21x21, 면 #D9D9D9 (토큰 없음)
        - Ellipse 337: 16x16, 면 yellow-200 (기본 색)
      - Union: 15x18, 면 gray-350 (기본 색)
        - Rectangle 64: 15x11, 면 background-secondary
        - Rectangle 65 (Stroke): 10x7, 면 background-secondary
