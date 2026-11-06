# Progress/Linear

묶음: 공통 · Progress

얇은 진행 막대 (높이 4). • 언제: 영상·오디오 재생 위치 • 쓰지 말 것: 단계 진행 (→ Progress/Step Bar) • 함께: Video·Story 화면 • 쓰는 곳(실제 앱): 레슨 · 스토리.

속성: state:in-progress·start

- 스펙 (px, 기준 `state=in-progress`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 360x4
    - progress/bg: 360x4, 면 black (기본 색) 20%
    - progress/gagebar: 117x4, 면 green-500 (기본 색)
  - 배리언트 `state=in-progress`: 360x4
  - 배리언트 `state=start`: 360x4
  - 배리언트 `state=start` 자세히 (기준과 다른 부분):
      - progress/gagebar: 6x4, 면 icon-highlight
  - ⚠ 기본 색 사용 · progress/bg: black → 맞는 용도 토큰 없음 (빈칸)
  - ⚠ 기본 색 사용 · progress/gagebar: green-500 → button-primary · icon-highlight · text-highlight 중 용도에 맞는 것
