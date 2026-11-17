# Navigation/Glass Bar Button

묶음: 공통 · Navigation

iOS 26 유리 원 버튼 44 (뒤로·닫기·더보기·알림·글자). • 언제: 내비게이션 바와 시트 위쪽 버튼 • 쓰지 말 것: 화면 안 일반 버튼 • 함께: Navigation/Nav Bar iOS 26, System/Sheet Top iOS 26

속성: type:back·close·bell·text·more

- 스펙 (px, 기준 `type=back`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 44x44, 가로 정렬, Corner Radius full (Radius/full)
    - Fill + Shadow: 44x44, Corner Radius full (Radius/full), 면 black (기본 색) 25% + background-secondary 25% + #444444 (토큰 없음) 60% + #F8F8F8 (토큰 없음) 20%
    - Glass Effect: 44x44, Corner Radius full (Radius/full)
    - Icon/Chevron Left 24: 24x24, 부품 Icon/Chevron Left 24
  - 배리언트 `type=back`: 44x44
  - 배리언트 `type=close`: 44x44
  - 배리언트 `type=bell`: 44x44
  - 배리언트 `type=text`: 80x44, 글자 text-secondary
  - 배리언트 `type=more`: 44x44
  - 배리언트 `type=close` 자세히 (기준과 다른 부분):
      - Icon/Close 24: 24x24, 부품 Icon/Close 24
  - 배리언트 `type=bell` 자세히 (기준과 다른 부분):
      - Icon/Alarm 24: 24x24, 부품 Icon/Alarm 24
  - 배리언트 `type=text` 자세히 (기준과 다른 부분):
    - 전체: 80x44, 가로 정렬, 여백 위아래 0 · 좌우 16 (Spacing/16), Corner Radius full (Radius/full)
      - Fill + Shadow: 80x44, Corner Radius full (Radius/full), 면 black (기본 색) 25% + background-secondary 25% + #444444 (토큰 없음) 60% + #F8F8F8 (토큰 없음) 20%
      - Glass Effect: 80x44, Corner Radius full (Radius/full)
      - Retry: 41x22, 글자색 text-secondary, 글자 Button 1/M
  - 배리언트 `type=more` 자세히 (기준과 다른 부분):
      - Fill + Shadow: 44x44, Corner Radius full (Radius/full), 면 black (기본 색) + background-secondary + #444444 (토큰 없음) 60% + #F8F8F8 (토큰 없음) 20%
      - Icon/Menu 24: 24x24, 부품 Icon/Menu 24
