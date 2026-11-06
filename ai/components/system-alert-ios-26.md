# System/Alert iOS 26

묶음: 공통 · System

iOS 26 시스템 알림창 (권한 요청). • 언제: OS가 띄우는 권한 요청 화면 그릴 때 • 쓰지 말 것: 우리 앱 확인 창 (→ Dialog/Basic)

속성: appearance:dark·light

- 스펙 (px, 기준 `appearance=dark`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 304x258, 세로 정렬, 여백 위 22 (토큰 없음) · 오른 22 (토큰 없음) · 아래 20 (토큰 없음) · 왼 22 (토큰 없음), 간격 12 (토큰 없음), 모서리 34 (토큰 없음)
    - Fill + Shadow: 304x258, 모서리 34 (토큰 없음), 면 #2B2B2E (토큰 없음) 88%
    - Glass Effect: 304x258, 모서리 34 (토큰 없음)
    - app icon: 60x60, 모서리 14 (토큰 없음), 면 #FA993D (토큰 없음)
    - text: 260x80, 세로 정렬, 간격 4 (토큰 없음)
      - title: 260x40, 글자색 #FFFFFF (토큰 없음), 글자 Semibold 17 (스타일 없음)
      - message: 260x36, 글자색 #FFFFFF (토큰 없음) 55%, 글자 Regular 15 (스타일 없음)
    - buttons: 260x52, 가로 정렬, 여백 위 6 (토큰 없음) · 오른 0 · 아래 0 · 왼 0, 간격 8 (토큰 없음)
      - button: 126x46, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 0, 모서리 full (토큰 없음), 면 #FFFFFF (토큰 없음) 12%
        - Don’t Allow: 96x20, 글자색 #FFFFFF (토큰 없음), 글자 Semibold 17 (스타일 없음)
      - button: 126x46, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 0, 모서리 full (토큰 없음), 면 #FFFFFF (토큰 없음) 12%
        - Allow: 46x20, 글자색 #FFFFFF (토큰 없음), 글자 Semibold 17 (스타일 없음)
  - 배리언트 `appearance=dark`: 304x258, 글자 #FFFFFF (토큰 없음)
  - 배리언트 `appearance=light`: 304x258, 글자 #000000 (토큰 없음)
  - ⚠ 토큰에 없는 간격 · 전체: 여백 22 ×3 → 가까운 값 Spacing/20
  - ⚠ 간격 토큰 안 걸림 · 전체: 여백 20 → Spacing/20 연결
  - ⚠ 간격 토큰 안 걸림 · 전체: 간격 12 → Spacing/12 연결
  - ⚠ 토큰에 없는 모서리 · 전체: 모서리 34 → 가까운 값 Radius/30
  - ⚠ 토큰에 없는 모서리 · app icon: 모서리 14 → 가까운 값 Radius/12
  - ⚠ 간격 토큰 안 걸림 · text: 간격 4 → Spacing/4 연결
  - ⚠ 텍스트 스타일 없음 · title: Semibold 17 → Head 4/B (크기 17→18)
  - ⚠ 텍스트 스타일 없음 · message: Regular 15 → Subtitle 1/R (크기 15→16)
  - ⚠ 간격 토큰 안 걸림 · buttons: 여백 6 → Spacing/6 연결
  - ⚠ 간격 토큰 안 걸림 · buttons: 간격 8 → Spacing/8 연결
  - ⚠ 토큰에 없는 간격 · button: 여백 13 ×4 → 가까운 값 Spacing/12
  - ⚠ 모서리 토큰 안 걸림 · button: 모서리 1000 ×2 → Radius/full 연결
  - ⚠ 텍스트 스타일 없음 · Don’t Allow: Semibold 17 → Head 4/B (크기 17→18)
  - ⚠ 텍스트 스타일 없음 · Allow: Semibold 17 → Head 4/B (크기 17→18)
