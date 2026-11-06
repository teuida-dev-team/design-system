# Streak/Status Icon

묶음: 여러 기능 패턴 · Streak

스트릭 상태 아이콘 (해야 함·진행 중·긴급·완료·없음).

속성: state:doing-emergency·doing-morning·doing-morning-n·done·none·todo

- 스펙 (px, 기준 `state=doing-emergency`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 52x40
    - Rectangle 22: 52x40
    - 13: 22x8
      - Vector: 13x6, 면 #595656 (토큰 없음)
      - Vector: 5x4, 면 #565656 (토큰 없음)
      - Vector: 5x4, 면 #565656 (토큰 없음)
  - 배리언트 `state=doing-emergency`: 52x40
  - 배리언트 `state=doing-morning`: 52x40
  - 배리언트 `state=doing-morning-n`: 52x40
  - 배리언트 `state=done`: 52x40
  - 배리언트 `state=none`: 52x40
  - 배리언트 `state=todo`: 52x40
  - 배리언트 `state=doing-afternoon`: 52x40
  - 배리언트 `state=doing-evening`: 52x40
