# Input/Search Field

묶음: 공통 · Input

검색 입력창 (iOS 26 이전 모양). typing = 입력 중. 쓰는 곳(실제 앱): 프로필.

속성: typing:true·false

- 스펙 (px, 기준 `typing=false`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 335x45, 가로 정렬, 여백 위아래 15 (토큰 없음) · 좌우 12 (Spacing/12), 간격 7 (토큰 없음), 모서리 12 (Radius/12), 면 background-primary
    - Frame 1792: 218x20, 가로 정렬, 간격 7 (토큰 없음)
      - Icon/Search 16: 16x16, 부품 Icon/Search 16
      - Frame 1506: 195x20, 가로 정렬, 간격 10 (Spacing/10), 선 border-success
        - Search by username or em: 195x20, 글자색 gray-350 (기본 색), 글자 BUTTON 2 - M
  - 배리언트 `typing=false`: 335x45, 면 background-primary, 글자 gray-350 (기본 색)
  - 배리언트 `typing=true`: 335x45, 면 background-primary, 글자 text-primary
  - 배리언트 `typing=true` 자세히 (기준과 다른 부분):
    - 전체: 335x45, 가로 정렬, 여백 위아래 15 (토큰 없음) · 좌우 12 (Spacing/12), 간격 양 끝 정렬, 모서리 12 (Radius/12), 면 background-primary
      - Frame 1506: 73x20, 가로 정렬, 간격 7 (토큰 없음)
        - Frame 1506: 50x20, 가로 정렬, 간격 10 (Spacing/10), 선 border-success
          - Sample: 50x20, 글자색 text-primary, 글자 BUTTON 2 - M
      - Icon/Cancel 24: 24x24, 부품 Icon/Cancel 24
  - ⚠ 토큰에 없는 간격 · 전체: 여백 15 ×2 → 가까운 값 Spacing/16
  - ⚠ 토큰에 없는 간격 · 전체: 간격 7 → 가까운 값 Spacing/6
  - ⚠ 토큰에 없는 간격 · Frame 1792: 간격 7 → 가까운 값 Spacing/6
  - ⚠ 옛 텍스트 스타일 · Search by username or em: BUTTON 2 - M → Button 2/M
  - ⚠ 기본 색 사용 · Search by username or em: gray-350 → border-tertiary 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · 배리언트 typing=false: 글자 gray-350 → border-tertiary
