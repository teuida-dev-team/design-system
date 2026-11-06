# Vocab/List Item

묶음: 기능 전용 · Vocab

보캡 문제의 보기 한 줄 (선택·정답·오답 상태).

속성: state:default·selected·failed·unselected·success·default_4-lines

- 스펙 (px, 기준 `state=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 327x80, 가로 정렬, 간격 10 (Spacing/10), 모서리 16 (Radius/16), 면 button-second-primary
    - Frame 2053: 223x46, 세로 정렬, 간격 6 (Spacing/6)
      - Frame 2039: 223x46, 세로 정렬
        - 선생님: 223x26, 글자색 text-secondary, 글자 Head 4/B
        - [sunsagnim]: 223x20, 글자색 gray-600 (기본 색), 글자 Subtitle 2/R
    - icon / heroicons / Solid: 24x24, 부품 icon / heroicons / Solid / volume-up
  - 배리언트 `state=default`: 327x80, 면 button-second-primary, 글자 text-secondary
  - 배리언트 `state=selected`: 327x80, 면 button-second-primary, 글자 text-highlight
  - 배리언트 `state=unselected`: 327x80, 면 gray-200 (기본 색), 글자 text-unselected
  - 배리언트 `state=success`: 327x80, 면 button-primary, 선 green-500 (기본 색), 글자 button-text-tertiary
  - 배리언트 `state=failed`: 327x80, 면 red-300 (기본 색), 선 red-400 (기본 색), 글자 button-tertiary
  - 배리언트 `state=default_4-lines`: 327x126, 면 button-second-primary, 글자 text-secondary
  - 배리언트 `state=default_3-lines`: 327x100, 면 button-second-primary, 글자 text-secondary
  - 배리언트 `state=selected` 자세히 (기준과 다른 부분):
    - 전체: 327x80, 가로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 0, 간격 10 (Spacing/10), 모서리 16 (Radius/16), 면 button-second-primary
          - 선생님: 223x26, 글자색 text-highlight, 글자 Head 4/B
  - 배리언트 `state=unselected` 자세히 (기준과 다른 부분):
    - 전체: 327x80, 가로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 0, 간격 10 (Spacing/10), 모서리 16 (Radius/16), 면 gray-200 (기본 색)
          - 선생님: 223x26, 글자색 text-unselected, 글자 Head 4/B
          - [sunsagnim]: 223x20, 글자색 text-unselected, 글자 Subtitle 2/R
  - 배리언트 `state=success` 자세히 (기준과 다른 부분):
    - 전체: 327x80, 가로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 0, 간격 10 (Spacing/10), 모서리 16 (Radius/16), 면 button-primary, 선 green-500 (기본 색) 2
          - 선생님: 223x26, 글자색 button-text-tertiary, 글자 Head 4/B
          - [sunsagnim]: 223x20, 글자색 button-text-tertiary, 글자 Subtitle 2/R
  - 배리언트 `state=failed` 자세히 (기준과 다른 부분):
    - 전체: 327x80, 가로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 0, 간격 10 (Spacing/10), 모서리 16 (Radius/16), 면 red-300 (기본 색), 선 red-400 (기본 색) 2
          - 선생님: 223x26, 글자색 button-tertiary, 글자 Head 4/B
          - [sunsagnim]: 223x20, 글자색 button-text-tertiary, 글자 Subtitle 2/R
  - 배리언트 `state=default_4-lines` 자세히 (기준과 다른 부분):
    - 전체: 327x126, 가로 정렬, 여백 위아래 17 (토큰 없음) · 좌우 0, 간격 10 (Spacing/10), 모서리 16 (Radius/16), 면 button-second-primary
      - Frame 2053: 223x92, 세로 정렬, 간격 6 (Spacing/6)
        - Frame 2039: 223x92, 세로 정렬
          - 선생님 두 줄 일 때: 223x52, 글자색 text-secondary, 글자 Head 4/B
          - [sunsagnim sunsagnim sun: 223x40, 글자색 gray-600 (기본 색), 글자 Subtitle 2/R
  - 배리언트 `state=default_3-lines` 자세히 (기준과 다른 부분):
    - 전체: 327x100, 가로 정렬, 여백 위아래 17 (토큰 없음) · 좌우 0, 간격 10 (Spacing/10), 모서리 16 (Radius/16), 면 button-second-primary
      - Frame 2053: 223x66, 세로 정렬, 간격 6 (Spacing/6)
        - Frame 2039: 223x66, 세로 정렬
          - [sunsagnim sunsagnim sun: 223x40, 글자색 gray-600 (기본 색), 글자 Subtitle 2/R
  - ⚠ 기본 색 사용 · [sunsagnim]: gray-600 → icon-secondary · border-active 중 용도에 맞는 것
  - ⚠ 목록에 없는 부품 사용 · icon / heroicons / Solid: icon / heroicons / Solid / volume-up → 같은 종류의 현행 부품으로 교체
  - ⚠ 기본 색 사용 · 배리언트 state=unselected: 면 gray-200 → button-secondary
  - ⚠ 기본 색 사용 · 배리언트 state=success: 선 green-500 → border-highlight · text-highlight · icon-highlight
  - ⚠ 기본 색 사용 · 배리언트 state=failed: 면 red-300 → 맞는 용도 토큰 없음
  - ⚠ 기본 색 사용 · 배리언트 state=failed: 선 red-400 → border-error · text-failed · icon-highlight-red
