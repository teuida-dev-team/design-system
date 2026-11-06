# Input/Text Field Form 1

묶음: 공통 · Input

제목·안내 문구가 붙은 입력창 묶음. 쓰는 곳(실제 앱): 설정 · 온보딩.

속성: state:default·typing·completed·focused·error

- 스펙 (px, 기준 `state=error`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 327x107, 세로 정렬, 간격 20 (Spacing/20)
    - Frame 1899: 327x107, 세로 정렬, 간격 12 (Spacing/12)
      - Text / titlebar: 82x22, 글자색 text-secondary, 글자 Subtitle 1/M
      - Frame 1911: 327x73, 세로 정렬, 간격 8 (Spacing/8)
        - text field: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 선 text-alert 1, 부품 Input/Text Field
        - Frame 1912: 120x17, 가로 정렬, 간격 6 (Spacing/6)
  - 배리언트 `state=default`: 327x82, 글자 text-primary
  - 배리언트 `state=typing`: 327x107, 글자 text-primary
  - 배리언트 `state=completed`: 327x82, 글자 text-primary
  - 배리언트 `state=focused`: 327x82, 글자 text-primary
  - 배리언트 `state=error`: 327x107, 글자 text-primary
  - 배리언트 `state=default` 자세히 (기준과 다른 부분):
    - 전체: 327x82, 세로 정렬, 간격 20 (Spacing/20)
      - Frame 1899: 327x82, 세로 정렬, 간격 12 (Spacing/12)
        - text field: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 부품 Input/Text Field
  - 배리언트 `state=typing` 자세히 (기준과 다른 부분):
          - text field: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 선 border-highlight 1, 부품 Input/Text Field
          - Frame 1912: 142x17, 가로 정렬, 간격 6 (Spacing/6)
  - 배리언트 `state=completed` 자세히 (기준과 다른 부분):
    - 전체: 327x82, 세로 정렬, 간격 20 (Spacing/20)
      - Frame 1899: 327x82, 세로 정렬, 간격 12 (Spacing/12)
        - text field: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 부품 Input/Text Field
  - 배리언트 `state=focused` 자세히 (기준과 다른 부분):
    - 전체: 327x82, 세로 정렬, 간격 20 (Spacing/20)
      - Frame 1899: 327x82, 세로 정렬, 간격 12 (Spacing/12)
        - text field: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 선 border-highlight 1, 부품 Input/Text Field
