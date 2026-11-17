# System/Status Bar iOS

묶음: 공통 · System

iOS 상태바 (시스템 UI, 폭 375·360). • 언제: 모든 iOS 화면 맨 위 • 쓰지 말 것: 안드로이드 화면 (→ System/Status Bar Android) • 함께: Navigation/Nav Bar iOS 26

속성: width:375·360

- 스펙 (px, 기준 `width=375`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 375x44, 면 background-secondary
    - Left Side: 50x19
      - _StatusBar-time: 50x19, Corner Radius 24 (Radius/24)
        - ✏️ Time: 27x11, 면 icon-primary
    - Right Side: 64x11
      - Battery: 24x11
        - Outline (Stroke): 22x11, 면 icon-primary
        - Battery End: 1x4, 면 icon-primary
        - Fill: 18x8, 면 icon-primary
      - Wifi: 14x10, 면 icon-primary
        - Wifi-path: 14x4, 면 #DADADA (토큰 없음)
        - Wifi-path: 9x3, 면 #DADADA (토큰 없음)
        - Wifi-path: 4x3, 면 #DADADA (토큰 없음)
      - Icon / Mobile Signal: 15x10, 면 icon-primary
  - 배리언트 `width=375`: 375x44, 면 background-secondary
  - 배리언트 `width=360`: 360x45, 면 background-secondary
