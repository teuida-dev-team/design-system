# Bottom Sheet/Top

묶음: 공통 · Bottom Sheet

바텀시트 맨 위 줄 (닫기 X 있음/없음). 쓰는 곳(실제 앱): 스트릭.

속성: type:close·empty

- 스펙 (px, 기준 `type=close`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 335x20, 가로 정렬, 간격 10 (Spacing/10), 면 background-secondary
    - Icon/Close 20: 20x20, 부품 Icon/Close 20
  - 배리언트 `type=close`: 335x20, 면 background-secondary
  - 배리언트 `type=empty`: 335x20, 면 background-secondary
  - 배리언트 `type=empty` 자세히 (기준과 다른 부분):
      - Icon/Empty 20: 20x20, 부품 Icon/Empty 20
