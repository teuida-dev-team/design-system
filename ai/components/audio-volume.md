# Audio/Volume

묶음: 여러 기능 패턴 · Audio

소리 버튼. size=32(기본) · size=18(리스트·카드 안 작은 소리 버튼)

속성: state:off·on / size:32·18

- 스펙 (px, 기준 `state=on, size=32`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 32x32
    - Icon: 29x24, 면 icon-highlight
  - 배리언트 `state=on, size=32`: 32x32
  - 배리언트 `state=off, size=32`: 32x32
  - 배리언트 `state=on, size=18`: 18x18
  - 배리언트 `state=off, size=18`: 18x18
  - 배리언트 `state=off, size=32` 자세히 (기준과 다른 부분):
      - Icon: 29x24, 면 button-text-inactive
  - 배리언트 `state=on, size=18` 자세히 (기준과 다른 부분):
    - 전체: 18x18
      - Icon: 16x13, 면 icon-highlight
  - 배리언트 `state=off, size=18` 자세히 (기준과 다른 부분):
    - 전체: 18x18
      - Icon: 16x13, 면 button-text-inactive
