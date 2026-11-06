# Weekly Progress/Day Labels

묶음: 기능 전용 · Weekly Progress

위클리 프로그레스 요일별 상태 (매일·마일스톤, 완료·포션).

속성: state:milestone-completed·milestone-default·daily-completed·daily-default·daily-potion

- 스펙 (px, 기준 `state=daily-completed`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 40x62, 세로 정렬, 간격 2 (Spacing/2)
    - day of the week: 17x20, 부품 Weekly Progress/Day Of The Week
    - day-state: 40x40, 부품 Weekly Progress/Day State
  - 배리언트 `state=daily-completed`: 40x62, 글자 text-highlight
  - 배리언트 `state=milestone-completed`: 40x62
  - 배리언트 `state=daily-default`: 40x62
  - 배리언트 `state=daily-potion`: 40x62
  - 배리언트 `state=milestone-default`: 40x62
  - 배리언트 `state=milestone-completed` 자세히: 기준과 같음
  - 배리언트 `state=daily-default` 자세히: 기준과 같음
  - 배리언트 `state=daily-potion` 자세히: 기준과 같음
  - 배리언트 `state=milestone-default` 자세히: 기준과 같음
