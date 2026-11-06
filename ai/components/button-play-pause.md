# Button/Play Pause

묶음: 공통 · Button

재생·일시정지 버튼. • 언제: 영상·오디오 재생 제어 • 함께: Video·Story 화면

속성: type:controller / style:pause·play

- 스펙 (px, 기준 `type=controller, style=pause`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 72x72
    - Union: 72x72, 면 button-second-primary
      - Ellipse 89: 72x72, 선 border-primary 3
      - Rectangle 122: 5x22, 면 button-second-primary
      - Rectangle 123: 5x22, 면 button-second-primary
    - button / controller / pa: 72x72
  - 배리언트 `type=controller, style=pause`: 72x72
  - 배리언트 `type=controller, style=play`: 72x72
  - 배리언트 `type=controller, style=play` 자세히 (기준과 다른 부분):
      - Group 467: 72x72
        - Union: 72x72, 면 button-second-primary
          - Ellipse 89: 72x72, 선 border-primary 3
        - Rectangle 187: 22x26, 면 icon-on-color
      - button / controller / pl: 72x72
