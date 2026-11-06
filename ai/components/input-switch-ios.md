# Input/Switch iOS

묶음: 공통 · Input

iOS 스위치 (on·off). • 언제: 설정 켜기·끄기 • 쓰지 말 것: 여러 개 중 하나 고르기 (→ List/Option Item) • 쓰는 곳(실제 앱): 권한 · 리뷰 · 설정.

속성: state:off·on

- 스펙 (px, 기준 `state=off`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 50x32
    - Group 1589: 46x28
      - Rectangle 1116: 46x28, 모서리 full (Radius/full), 면 gray-350 (기본 색)
      - Ellipse 348: 22x22, 면 background-secondary
  - 배리언트 `state=off`: 50x32
  - 배리언트 `state=on`: 50x32
  - 배리언트 `state=on` 자세히 (기준과 다른 부분):
      - Group 1588: 46x28
        - Rectangle 1116: 46x28, 모서리 full (Radius/full), 면 button-primary
  - ⚠ 기본 색 사용 · Rectangle 1116: gray-350 → border-tertiary 중 용도에 맞는 것
