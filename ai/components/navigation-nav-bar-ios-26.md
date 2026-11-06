# Navigation/Nav Bar iOS 26

묶음: 공통 · Navigation

iOS 26 내비게이션 바 (상태바 + 뒤로 · 제목 · 닫기). • 언제: 탭 아래로 들어간 하위 화면 맨 위 • 쓰지 말 것: 학습 진행 화면 (→ Navigation/Top Nav), 탭 루트 화면 (→ Nav Bar) • 함께: Navigation/Glass Bar Button, Template/List Screen

속성: style:opaque·transparent

- 스펙 (px, 기준 `style=opaque`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 375x101, 세로 정렬, 면 background-secondary, 선 border-secondary
    - System/Status Bar iOS: 375x44, 면 background-secondary, 부품 System/Status Bar iOS
    - bar: 375x56, 가로 정렬, 여백 위아래 6 (Spacing/6) · 좌우 16 (Spacing/16), 간격 양 끝 정렬
      - leading: 44x44, 가로 정렬, 모서리 full (Radius/full), 부품 Navigation/Glass Bar Button
      - title: 36x22, 글자색 text-primary, 글자 Head 5/B
      - trailing: 44x44, 가로 정렬, 모서리 full (Radius/full), 부품 Navigation/Glass Bar Button
  - 배리언트 `style=opaque`: 375x101, 면 background-secondary, 선 border-secondary, 글자 text-primary
  - 배리언트 `style=transparent`: 375x100, 글자 text-primary
  - 배리언트 `style=transparent` 자세히 (기준과 다른 부분):
    - 전체: 375x100, 세로 정렬
