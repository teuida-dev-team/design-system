# Progress/Pagination Dot

묶음: 공통 · Progress

페이지 점 한 개 (default·focused). 쓰는 곳(실제 앱): 커뮤니티.

속성: state:default·focused

- 스펙 (px, 기준 `state=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 6x6
    - Navigation_dot_default: 6x6, 면 gray-600 (기본 색)
  - 배리언트 `state=default`: 6x6
  - 배리언트 `state=focused`: 6x6
  - 배리언트 `state=focused` 자세히 (기준과 다른 부분):
      - Navigation_dot_focused: 6x6, 면 green-500 (기본 색)
  - ⚠ 기본 색 사용 · Navigation_dot_default: gray-600 → icon-secondary · border-active 중 용도에 맞는 것
