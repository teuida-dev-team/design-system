# Speaking/VUI

묶음: 여러 기능 패턴 · Speaking

말하기 버튼과 인식 진행 원. • 언제: 말하기 문제에서 녹음·인식 중 • 함께: Button/Mic, Speaking/Listening Bar • 쓰는 곳(실제 앱): 레슨 · 리뷰 · 보캡.

속성: type:speak·progress·speak-pressed / size:default·big

- 스펙 (px, 기준 `type=speak, size=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 126x126
    - button_speak: 88x88
      - Oval: 88x88, 면 background-secondary
    - ic_mic: 26x42
      - Ellipse 245: 26x10, 면 button-inactive, 선 button-inactive 3.5
      - Rectangle 870: 14x27, 면 button-inactive, 선 button-inactive 1
      - Vector 433: 0x8, 면 button-inactive, 선 button-inactive 3.5
      - Vector 434: 10x0, 면 button-inactive, 선 button-inactive 3.5
  - 배리언트 `type=speak, size=default`: 126x126
  - 배리언트 `type=speak-pressed, size=default`: 126x126
  - 배리언트 `type=progress, size=default`: 126x126
  - 배리언트 `type=progress, size=big`: 126x126
  - 배리언트 `type=speak-pressed, size=default` 자세히 (기준과 다른 부분):
        - Oval: 88x88, 면 background-primary
  - 배리언트 `type=progress, size=default` 자세히 (기준과 다른 부분):
      - VUI/Big/progressbar_1: 110x110
        - VUI/border: 110x110, 면 그라디언트
        - Group 1717: 88x88
          - 1: 88x88
          - bg: 75x75, 면 black (기본 색)
          - bg: 75x75, 면 green-500 (기본 색)
        - Ellipse 177: 75x75
  - 배리언트 `type=progress, size=big` 자세히 (기준과 다른 부분):
      - VUI/border: 126x126, 면 그라디언트
      - Ellipse 177: 73x73
      - Group 1716: 88x88
        - 1: 88x88
          - Oval: 88x88, 면 background-secondary
          - Rectangle: 4x33, Corner Radius full (Radius/full), 면 green-500 (기본 색)
          - Rectangle: 4x21, Corner Radius full (Radius/full), 면 #0DD7C3 (토큰 없음)
          - Rectangle: 4x21, Corner Radius full (Radius/full), 면 #0DD7C3 (토큰 없음)
          - Rectangle: 4x11, Corner Radius full (Radius/full), 면 #21C6D2 (토큰 없음)
          - Rectangle: 4x11, Corner Radius full (Radius/full), 면 #21C6D2 (토큰 없음)
        - bg: 75x75, 면 black (기본 색)
        - bg: 75x75, 면 green-500 (기본 색)
