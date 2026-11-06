# Practice/Romanization Cell

묶음: 기능 전용 · Practice

프랙티스 로마자 표기 셀. Default / Answer / Blank.

속성: type:default·answer·blank

- 스펙 (px, 기준 `type=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 134x26, 가로 정렬, 여백 위 2 (Spacing/2) · 오른 0 · 아래 4 (Spacing/4) · 왼 0, 간격 10 (Spacing/10), 모서리 4 (Radius/4)
    - loremipsum dolorsit: 134x20, 글자색 text-tertiary, 글자 Body 2/R
  - 배리언트 `type=default`: 134x26, 글자 text-tertiary
  - 배리언트 `type=answer`: 142x26, 글자 text-correct
  - 배리언트 `type=blank`: 142x26, 글자 gray-100 (기본 색)
  - 배리언트 `type=answer` 자세히 (기준과 다른 부분):
    - 전체: 142x26, 세로 정렬, 여백 위 0 · 오른 0 · 아래 2 (Spacing/2) · 왼 0
      - PT_Romani_Cell/Answer: 142x24, 가로 정렬, 여백 위아래 2 (Spacing/2) · 좌우 4 (Spacing/4), 간격 10 (Spacing/10), 모서리 4 (Radius/4), 면 background-primary
        - loremipsum dolorsit: 134x20, 글자색 text-correct, 글자 Body 2/R
  - 배리언트 `type=blank` 자세히 (기준과 다른 부분):
    - 전체: 142x26, 세로 정렬, 여백 위 0 · 오른 0 · 아래 2 (Spacing/2) · 왼 0
      - PT_Romani_Cell/Blank: 142x24, 가로 정렬, 여백 위아래 2 (Spacing/2) · 좌우 4 (Spacing/4), 간격 10 (Spacing/10), 모서리 4 (Radius/4), 면 background-primary
        - loremipsum dolorsit: 134x20, 글자색 gray-100 (기본 색), 글자 Body 2/R
