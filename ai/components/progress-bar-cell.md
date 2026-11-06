# Progress/Bar Cell

묶음: 공통 · Progress

단계 표시 한 칸 (현재·다음·완료, 점 10dp·8dp). 쓰는 곳(실제 앱): 스트릭.

속성: progress:dot_10dp_now·next·completed / dot_8dp_now·next·completed

- 스펙 (px, 기준 `progress=dot_10dp_now`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 10x10
    - Ellipse 278: 10x10, 면 icon-highlight
  - 배리언트 `progress=dot_10dp_now`: 10x10
  - 배리언트 `progress=dot_10dp_next`: 10x10
  - 배리언트 `progress=dot_10dp_completed`: 10x10
  - 배리언트 `progress=dot_8dp_now`: 8x8
  - 배리언트 `progress=dot_8dp_next`: 8x8
  - 배리언트 `progress=dot_8dp_completed`: 8x8
  - 배리언트 `progress=dot_10dp_next` 자세히 (기준과 다른 부분):
      - Ellipse 278: 10x10, 면 gradient-unfilled
  - 배리언트 `progress=dot_10dp_completed` 자세히: 기준과 같음
  - 배리언트 `progress=dot_8dp_now` 자세히 (기준과 다른 부분):
    - 전체: 8x8
      - Ellipse 278: 8x8, 면 icon-highlight
  - 배리언트 `progress=dot_8dp_next` 자세히 (기준과 다른 부분):
    - 전체: 8x8
      - Ellipse 278: 8x8, 면 gradient-unfilled
  - 배리언트 `progress=dot_8dp_completed` 자세히 (기준과 다른 부분):
    - 전체: 8x8
      - Ellipse 278: 8x8, 면 icon-highlight
