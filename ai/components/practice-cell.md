# Practice/Cell

묶음: 기능 전용 · Practice

프랙티스 단어 셀. Position × Blank(빈칸 여부) 9종.

속성: position:default·answer_one·answer_end·answer_middle·answer_front·blank_one / blank:false·true

- 스펙 (px, 기준 `position=default, blank=false`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 20x44, 세로 정렬, 여백 위아래 2 (Spacing/2) · 좌우 0, 간격 -4 (토큰 없음)
    - えき: 20x16, 글자색 gray-400 (기본 색), 글자 Overline/R
    - 駅: 20x28, 글자색 gray-400 (기본 색), 글자 Head 3/B
  - 배리언트 `position=default, blank=false`: 20x44, 글자 gray-400 (기본 색)
  - 배리언트 `position=answer_one, blank=false`: 30x44, 글자 text-correct
  - 배리언트 `position=answer_end, blank=false`: 28x44, 글자 text-correct
  - 배리언트 `position=answer_middle, blank=false`: 26x44, 글자 text-correct
  - 배리언트 `position=answer_front, blank=false`: 28x44, 글자 text-correct
  - 배리언트 `position=blank_one, blank=true`: 30x44, 글자 gray-100 (기본 색)
  - 배리언트 `position=blank_end, blank=true`: 28x44, 글자 gray-100 (기본 색)
  - 배리언트 `position=blank_front, blank=true`: 28x44, 글자 gray-100 (기본 색)
  - 배리언트 `position=blank_middle, blank=true`: 26x44, 글자 gray-100 (기본 색)
  - 배리언트 `position=answer_one, blank=false` 자세히 (기준과 다른 부분):
    - 전체: 30x44, 가로 정렬, 여백 2 (Spacing/2), 간격 10 (Spacing/10)
      - PT_JP_Cell/Answer/Small: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 모서리 6 (토큰 없음), 면 background-primary
        - えき: 20x16, 글자색 text-correct, 글자 Overline/R
        - 駅: 18x26, 글자색 text-correct, 글자 Head 4/B
  - 배리언트 `position=answer_end, blank=false` 자세히 (기준과 다른 부분):
    - 전체: 28x44, 가로 정렬, 여백 위 2 (Spacing/2) · 오른 2 (Spacing/2) · 아래 2 (Spacing/2) · 왼 0, 간격 10 (Spacing/10)
      - PT_JP_Cell/Answer/Small: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 모서리 0 6 (토큰 없음) 6 (토큰 없음) 0, 면 background-primary
        - えき: 20x16, 글자색 text-correct, 글자 Overline/R
        - 駅: 18x26, 글자색 text-correct, 글자 Head 4/B
  - 배리언트 `position=answer_middle, blank=false` 자세히 (기준과 다른 부분):
    - 전체: 26x44, 가로 정렬, 여백 위아래 2 (Spacing/2) · 좌우 0, 간격 10 (Spacing/10)
      - PT_JP_Cell/Answer/Small: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 면 background-primary
        - えき: 20x16, 글자색 text-correct, 글자 Overline/R
        - 駅: 18x26, 글자색 text-correct, 글자 Head 4/B
  - 배리언트 `position=answer_front, blank=false` 자세히 (기준과 다른 부분):
    - 전체: 28x44, 가로 정렬, 여백 위 2 (Spacing/2) · 오른 0 · 아래 2 (Spacing/2) · 왼 2 (Spacing/2), 간격 10 (Spacing/10)
      - PT_JP_Cell/Answer/Small: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 모서리 6 (토큰 없음) 0 0 6 (토큰 없음), 면 background-primary
        - えき: 20x16, 글자색 text-correct, 글자 Overline/R
        - 駅: 18x26, 글자색 text-correct, 글자 Head 4/B
  - 배리언트 `position=blank_one, blank=true` 자세히 (기준과 다른 부분):
    - 전체: 30x44, 가로 정렬, 여백 2 (Spacing/2)
      - PT_JP_Cell/Blank_One/Sma: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 모서리 6 (토큰 없음), 면 background-primary
        - えき: 20x16, 글자색 gray-100 (기본 색), 글자 Overline/R
        - 駅: 18x26, 글자색 gray-100 (기본 색), 글자 Head 4/B
  - 배리언트 `position=blank_end, blank=true` 자세히 (기준과 다른 부분):
    - 전체: 28x44, 가로 정렬, 여백 위 2 (Spacing/2) · 오른 2 (Spacing/2) · 아래 2 (Spacing/2) · 왼 0
      - PT_JP_Cell/Blank_End/Sma: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 모서리 0 6 (토큰 없음) 6 (토큰 없음) 0, 면 background-primary
        - えき: 20x16, 글자색 gray-100 (기본 색), 글자 Overline/R
        - 駅: 18x26, 글자색 gray-100 (기본 색), 글자 Head 4/B
  - 배리언트 `position=blank_front, blank=true` 자세히 (기준과 다른 부분):
    - 전체: 28x44, 가로 정렬, 여백 위 2 (Spacing/2) · 오른 0 · 아래 2 (Spacing/2) · 왼 2 (Spacing/2), 간격 10 (Spacing/10)
      - PT_JP_Cell/Blank_Front/S: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 모서리 6 (토큰 없음) 0 0 6 (토큰 없음), 면 background-primary
        - えき: 20x16, 글자색 gray-100 (기본 색), 글자 Overline/R
        - 駅: 18x26, 글자색 gray-100 (기본 색), 글자 Head 4/B
  - 배리언트 `position=blank_middle, blank=true` 자세히 (기준과 다른 부분):
    - 전체: 26x44, 가로 정렬, 여백 위아래 2 (Spacing/2) · 좌우 0, 간격 10 (Spacing/10)
      - PT_JP_Cell/Blank_Front/S: 26x40, 세로 정렬, 여백 위아래 1 (토큰 없음) · 좌우 3 (토큰 없음), 간격 -4 (토큰 없음), 면 background-primary
        - えき: 20x16, 글자색 gray-100 (기본 색), 글자 Overline/R
        - 駅: 18x26, 글자색 gray-100 (기본 색), 글자 Head 4/B
  - ⚠ 기본 색 사용 · えき: gray-400 → icon-unselected · button-outline-secondary 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · 駅: gray-400 → icon-unselected · button-outline-secondary 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · 배리언트 position=default, blank=false: 글자 gray-400 → icon-unselected · button-outline-secondary
  - ⚠ 기본 색 사용 · 배리언트 position=blank_one, blank=true: 글자 gray-100 → background-primary · button-tertiary
  - ⚠ 기본 색 사용 · 배리언트 position=blank_end, blank=true: 글자 gray-100 → background-primary · button-tertiary
  - ⚠ 기본 색 사용 · 배리언트 position=blank_front, blank=true: 글자 gray-100 → background-primary · button-tertiary
  - ⚠ 기본 색 사용 · 배리언트 position=blank_middle, blank=true: 글자 gray-100 → background-primary · button-tertiary
