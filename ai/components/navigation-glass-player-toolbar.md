# Navigation/Glass Player Toolbar

묶음: 공통 · Navigation

영상 재생 툴바 (iOS 27.1+, 아이폰 듀오 세로 바·넓은 화면만). 뒤로 감기·재생/일시정지·앞으로 감기·속도(1.0X, Bold 13). 오른쪽에 메뉴·닫기 버튼 묶음이 따로 붙음.

속성: state:playing·paused

- 스펙 (px, 기준 `state=playing`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 169x44, 가로 정렬, 여백 위아래 0 · 좌우 12 (Spacing/12), 간격 16 (Spacing/16), Corner Radius full (Radius/full)
    - Fill + Shadow: 169x44, Corner Radius full (Radius/full), 면 black (기본 색) 25% + background-secondary 25% + #444444 (토큰 없음) 60% + #F8F8F8 (토큰 없음) 20%
    - Glass Effect: 169x44, Corner Radius full (Radius/full)
    - Icon/Video Previous 24: 24x24, Corner Radius 1 (토큰 없음), 부품 Icon/Video Previous 24
    - Icon/Pause 24: 24x24, 부품 Icon/Pause 24
    - Icon/Video Next 24: 24x24, Corner Radius 1 (토큰 없음), 부품 Icon/Video Next 24
    - 1.0X: 25x18, 글자색 text-primary, 글자 Caption/M
  - 배리언트 `state=playing`: 169x44, 글자 text-primary
  - 배리언트 `state=paused`: 165x44, 글자 text-primary
  - 배리언트 `state=paused` 자세히 (기준과 다른 부분):
    - 전체: 165x44, 가로 정렬, 여백 위아래 0 · 좌우 12 (Spacing/12), 간격 16 (Spacing/16), Corner Radius full (Radius/full)
      - Fill + Shadow: 165x44, Corner Radius full (Radius/full), 면 black (기본 색) 25% + background-secondary 25% + #444444 (토큰 없음) 60% + #F8F8F8 (토큰 없음) 20%
      - Glass Effect: 165x44, Corner Radius full (Radius/full)
      - Icon/Play 20: 20x20, 부품 Icon/Play 20
