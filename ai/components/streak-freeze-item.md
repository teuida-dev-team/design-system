# Streak/Freeze Item

묶음: 기능 전용 · Streak

스트릭 프리즈 아이템 (있음·빈 칸).

속성: type:streakfreeze·streakfreeze_empty

- 스펙 (px, 기준 `type=streakfreeze`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 56x56, 가로 정렬, 간격 -10 (토큰 없음)
    - StreakItem_Slot: 56x56
      - Rectangle 1252: 56x56, 모서리 14 (토큰 없음), 면 icon-bubble-background
      - Vector: 29x34, 면 icon-bubble
  - 배리언트 `type=streakfreeze`: 56x56
  - 배리언트 `type=streakfreeze_empty`: 56x56
  - 배리언트 `type=streakfreeze_empty` 자세히 (기준과 다른 부분):
        - Rectangle 1252: 56x56, 모서리 14 (토큰 없음), 면 icon-inactive
        - Vector: 29x34, 면 icon-unselected
  - ⚠ 토큰에 없는 모서리 · Rectangle 1252: 모서리 14 → 가까운 값 Radius/12
