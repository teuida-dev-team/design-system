# Button/Mic

묶음: 공통 · Button

말하기 마이크 버튼 (on·success·failed·mute). • 언제: 말하기 문제에서 녹음 시작·결과 표시 • 쓰지 말 것: 소리 듣기 (→ Button/Circle Icon) • 함께: Speaking/VUI, Speaking/Listening Bar

속성: state:on·success·failed·mute·off·failed_1

- 스펙 (px, 기준 `state=mute`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 72x72, 가로 정렬, 여백 20 (Spacing/20), 간격 13.3 (토큰 없음), 모서리 full (Radius/full), 면 button-primary
    - Icon/Mic Mute 28: 34x34, 부품 Icon/Mic Mute 28
  - 배리언트 `state=on`: 72x72, 면 button-primary
  - 배리언트 `state=success`: 72x72, 면 button-primary
  - 배리언트 `state=success_1`: 126x126
  - 배리언트 `state=failed_1`: 126x126
  - 배리언트 `state=failed`: 72x72, 면 red-400 (기본 색)
  - 배리언트 `state=off`: 72x72, 면 button-second-primary
  - 배리언트 `state=mute`: 72x72, 면 button-primary
  - 배리언트 `state=on` 자세히 (기준과 다른 부분):
      - Icon/Mic On 28: 34x34, 부품 Icon/Mic On 28
  - 배리언트 `state=success` 자세히 (기준과 다른 부분):
      - Icon/Checkboxes 28: 34x34, 부품 Icon/Checkboxes 28
  - 배리언트 `state=success_1` 자세히 (기준과 다른 부분):
    - 전체: 126x126, 가로 정렬, 여백 24.4 (토큰 없음), 간격 16.3 (토큰 없음)
      - Group 1707: 75x75
        - Ellipse 406: 75x75, 면 button-primary
        - Icon/Checkboxes 28: 41x41, 부품 Icon/Checkboxes 28
  - 배리언트 `state=failed_1` 자세히 (기준과 다른 부분):
    - 전체: 126x126, 가로 정렬, 여백 24.4 (토큰 없음), 간격 16.3 (토큰 없음)
      - Group 1707: 75x75
        - Ellipse 406: 75x75, 면 red-400 (기본 색)
        - Icon/X 28: 41x41, 부품 Icon/X 28
  - 배리언트 `state=failed` 자세히 (기준과 다른 부분):
    - 전체: 72x72, 가로 정렬, 여백 20 (Spacing/20), 간격 13.3 (토큰 없음), 모서리 full (Radius/full), 면 red-400 (기본 색)
      - Icon/X 28: 34x34, 부품 Icon/X 28
  - 배리언트 `state=off` 자세히 (기준과 다른 부분):
    - 전체: 72x72, 가로 정렬, 여백 20 (Spacing/20), 간격 13.3 (토큰 없음), 모서리 full (Radius/full), 면 button-second-primary
      - Icon/Mic On 28: 34x34, 부품 Icon/Mic On 28
  - ⚠ 토큰에 없는 간격 · 전체: 간격 13.3 → 가까운 값 Spacing/12
  - ⚠ 기본 색 사용 · 배리언트 state=failed: 면 red-400 → icon-highlight-red · text-failed · border-error
