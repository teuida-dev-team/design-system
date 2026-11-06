# Streak/Calendar Icon

묶음: 여러 기능 패턴 · Streak

스트릭 캘린더 아이콘. state × day 조합 107배리언트. 시각화가 중요한 화면이라 day를 배리언트로 유지.

속성: state:doing_evening·none·todo·doing_morning·doing_afternoon·doing_emergency / day:default·day1·day2…

- 스펙 (px, 기준 `state=none, day=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 90x90
    - Group 52: 73x63
      - Group 49: 73x63
        - 레이어 5: 10x16
        - 레이어 4: 10x22
        - Pot: 73x45
    - Group 50: 40x31
      - Widget/Status Icon: 40x31, 부품 Streak/Status Icon
  - 배리언트 `state=doing_morning, day=day1`: 90x90
  - 배리언트 `state=doing_afternoon, day=day1`: 90x90
  - 배리언트 `state=doing_evening, day=day1`: 90x90
  - 배리언트 `state=doing_emergency, day=day1`: 90x90
  - 배리언트 `state=done, day=day1`: 90x90
  - 배리언트 `state=none, day=default`: 90x90
  - 배리언트 `state=todo, day=default`: 90x90
  - 배리언트 `state=doing_morning, day=day2`: 90x90
  - 배리언트 `state=doing_afternoon, day=day2`: 90x90
  - 배리언트 `state=doing_evening, day=day2`: 90x90
