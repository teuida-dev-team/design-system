# Input/Text Field

묶음: 공통 · Input

한 줄 입력창 (default·focused·typing·completed·error). • 언제: 이름·이메일 등 글자 입력 • 쓰지 말 것: 검색 (→ Input/Glass Search Field) • 함께: Input/Text Field Form 1 • 쓰는 곳(실제 앱): 설정 · 온보딩.

속성: state:error·default·typing·completed·focused

- 스펙 (px, 기준 `state=error`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 선 text-alert 1
    - Frame 1954: 298x22, 가로 정렬, 간격 양 끝 정렬
      - Text / titlebar: 270x22, 글자색 text-primary, 글자 Subtitle 1/M
      - Icon/X Circle 20: 20x20, 부품 Icon/X Circle 20
  - 배리언트 `state=error`: 327x48, 면 background-secondary, 선 text-alert, 글자 text-primary
  - 배리언트 `state=typing`: 327x48, 면 background-secondary, 선 border-highlight, 글자 text-primary
  - 배리언트 `state=completed`: 327x48, 면 background-secondary, 글자 text-primary
  - 배리언트 `state=focused`: 327x48, 면 background-secondary, 선 border-highlight, 글자 text-tertiary
  - 배리언트 `state=default`: 327x48, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `state=typing` 자세히 (기준과 다른 부분):
    - 전체: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 선 border-highlight 1
      - Frame 1955: 299x22, 가로 정렬, 간격 양 끝 정렬
        - Frame 1914: 46x22, 가로 정렬, 간격 2 (Spacing/2)
          - Text / titlebar: 42x22, 글자색 text-primary, 글자 Subtitle 1/M
          - Rectangle 41440: 2x20, 모서리 full (Radius/full), 면 gray-300 (기본 색)
        - Icon/X Circle 20: 20x20, 부품 Icon/X Circle 20
  - 배리언트 `state=completed` 자세히 (기준과 다른 부분):
    - 전체: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary
      - Text / titlebar: 196x22, 글자색 text-primary, 글자 Subtitle 1/M
  - 배리언트 `state=focused` 자세히 (기준과 다른 부분):
    - 전체: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary, 선 border-highlight 1
      - Frame 1914: 265x22, 가로 정렬, 간격 2 (Spacing/2)
        - Rectangle 41440: 2x20, 모서리 full (Radius/full), 면 gray-300 (기본 색)
        - Text / titlebar: 261x22, 글자색 text-tertiary, 글자 Subtitle 1/M
  - 배리언트 `state=default` 자세히 (기준과 다른 부분):
    - 전체: 327x48, 가로 정렬, 여백 위 13 (토큰 없음) · 오른 0 · 아래 13 (토큰 없음) · 왼 14 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 background-secondary
      - Text / titlebar: 261x22, 글자색 text-tertiary, 글자 Subtitle 1/M
