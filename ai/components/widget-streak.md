# Widget/Streak

묶음: 기능 전용 · Widget

iOS 홈화면 스트릭 위젯 본체.

속성: state:none·todo·doing·doing/emergency·done

- 스펙 (px, 기준 `state=none`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 158x158, 모서리 22 (토큰 없음), 면 그라디언트
    - Streak_ic: 90x90, 부품 Streak/Calendar Icon
    - Log in to get started st: 133x32, 글자색 text-on-color, 글자 Display SemiBold 14 (스타일 없음)
  - 배리언트 `state=todo`: 158x158, 면 그라디언트, 글자 text-on-color
  - 배리언트 `state=none`: 158x158, 면 그라디언트, 글자 text-on-color
  - 배리언트 `state=doing/emergency`: 158x158, 면 그라디언트, 글자 text-on-color
  - 배리언트 `state=done`: 158x158, 면 그라디언트, 글자 text-on-color
  - 배리언트 `state=doing`: 158x158, 면 그라디언트, 글자 white (기본 색)
  - ⚠ 토큰에 없는 모서리 · 전체: 모서리 22 → 가까운 값 Radius/24
  - ⚠ 텍스트 스타일 없음 · Log in to get started st: Display SemiBold 14 → Subtitle 2/B
