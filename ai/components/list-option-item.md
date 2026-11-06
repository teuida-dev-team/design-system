# List/Option Item

묶음: 공통 · List

고르는 목록 한 줄 (국기·라벨, 선택됨, 화살표). • 언제: 언어·코스·설정처럼 하나 고르기 • 쓰지 말 것: 퀴즈 보기 (→ Button/Choice) • 함께: List/Option • 쓰는 곳(실제 앱): 홈.

속성: dark mode:false·true / selected:false·true / chevron:false·true

- 스펙 (px, 기준 `dark mode=false, selected=false, chevron=false`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 335x72, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 background-secondary, 선 gray-100 (기본 색) 2
    - Frame: 303x48, 가로 정렬, 간격 양 끝 정렬
      - Frame: 98x44, 가로 정렬, 간격 12 (Spacing/12)
        - Icon/Flag: 44x44, 부품 Icon/Flag
        - Label: 42x22, 글자색 text-primary, 글자 Subtitle 1 - M
      - Icon/Empty 24: 20x20, 부품 Icon/Empty 24
  - 배리언트 `dark mode=false, selected=false, chevron=false`: 335x72, 면 background-secondary, 선 gray-100 (기본 색), 글자 text-primary
  - 배리언트 `dark mode=false, selected=true, chevron=false`: 335x72, 면 background-secondary, 선 border-highlight, 글자 text-primary
  - 배리언트 `dark mode=false, selected=false, chevron=true`: 335x72, 면 background-secondary, 선 gray-100 (기본 색), 글자 text-primary
  - 배리언트 `dark mode=true, selected=false, chevron=false`: 335x72, 면 gray-850 (기본 색), 선 gray-750 (기본 색), 글자 background-secondary
  - 배리언트 `dark mode=true, selected=true, chevron=false`: 335x72, 면 gray-850 (기본 색), 선 border-highlight, 글자 background-secondary
  - 배리언트 `dark mode=true, selected=false, chevron=true`: 335x72, 면 gray-850 (기본 색), 선 gray-750 (기본 색), 글자 background-secondary
  - 배리언트 `dark mode=false, selected=true, chevron=false` 자세히 (기준과 다른 부분):
    - 전체: 335x72, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
        - Frame: 100x44, 가로 정렬, 간격 12 (Spacing/12)
          - Label: 44x22, 글자색 text-primary, 글자 Head 5 - B
        - Icon/Check 24: 20x20, 부품 Icon/Check 24
  - 배리언트 `dark mode=false, selected=false, chevron=true` 자세히 (기준과 다른 부분):
        - Icon/Chevron Right 24: 20x20, 부품 Icon/Chevron Right 24
  - 배리언트 `dark mode=true, selected=false, chevron=false` 자세히 (기준과 다른 부분):
    - 전체: 335x72, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 gray-850 (기본 색), 선 gray-750 (기본 색) 2
          - Label: 42x22, 글자색 background-secondary, 글자 Subtitle 1 - M
  - 배리언트 `dark mode=true, selected=true, chevron=false` 자세히 (기준과 다른 부분):
    - 전체: 335x72, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 gray-850 (기본 색), 선 border-highlight 2
        - Frame: 100x44, 가로 정렬, 간격 12 (Spacing/12)
          - Label: 44x22, 글자색 background-secondary, 글자 Head 5 - B
        - Icon/Check 24: 20x20, 부품 Icon/Check 24
  - 배리언트 `dark mode=true, selected=false, chevron=true` 자세히 (기준과 다른 부분):
    - 전체: 335x72, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 gray-850 (기본 색), 선 gray-750 (기본 색) 2
          - Label: 42x22, 글자색 background-secondary, 글자 Subtitle 1 - M
        - Icon/Chevron Right 24: 20x20, 부품 Icon/Chevron Right 24
