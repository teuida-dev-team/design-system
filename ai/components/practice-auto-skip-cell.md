# Practice/Auto Skip Cell

묶음: 기능 전용 · Practice

프랙티스 자동 넘김 카운트다운 바 400x64.

속성: type:default

- 스펙 (px, 기준 `type=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 360x24, 가로 정렬
    - Frame 1824: 146x24, 가로 정렬
      - Icon/Pause 24: 24x24, 부품 Icon/Pause 24
    - Frame 1820: 68x22, 가로 정렬, 간격 4 (Spacing/4)
      - next in: 40x18, 글자색 gray-770 (기본 색), 글자 Caption/M
      - 3: 10x22, 글자색 gray-770 (기본 색), 글자 Button 1/B
      - ...: 10x18, 글자색 gray-770 (기본 색), 글자 Caption/M
    - Frame 1823: 146x24, 가로 정렬
      - Icon/Skip 24: 24x24, 부품 Icon/Skip 24
  - 배리언트 `type=default`: 360x24, 글자 gray-770 (기본 색)
  - ⚠ 기본 색 사용 · next in: gray-770 → 맞는 용도 토큰 없음 (빈칸)
  - ⚠ 기본 색 사용 · 3: gray-770 → 맞는 용도 토큰 없음 (빈칸)
  - ⚠ 기본 색 사용 · ...: gray-770 → 맞는 용도 토큰 없음 (빈칸)
  - ⚠ 기본 색 사용 · 배리언트 type=default: 글자 gray-770 → 맞는 용도 토큰 없음
