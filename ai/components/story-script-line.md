# Story/Script Line

묶음: 기능 전용 · Story

레슨 문장 한 줄 280x67(원문과 번역). 스토리 상세 view all 목록에 씀.

속성: type:default·focused(white back)·completed

- 스펙 (px, 기준 `type=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 280x65, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 15 (토큰 없음), 간격 12 (Spacing/12), Corner Radius 12 (Radius/12), 면 background-primary
    - Frame 1540: 214x39, 가로 정렬, 간격 12 (Spacing/12)
      - Frame 1540: 214x39, 세로 정렬, 간격 양 끝 정렬
        - Frame 1550: 214x39, 세로 정렬, 간격 3 (토큰 없음)
    - Icon/Lesson Play 24: 24x24, 부품 Icon/Lesson Play 24
  - 배리언트 `type=default`: 280x65, 면 background-primary, 글자 text-primary
  - 배리언트 `type=focused(white back)`: 280x65, 면 background-secondary, 글자 text-primary
  - 배리언트 `type=completed`: 280x65, 면 background-primary, 글자 text-primary
  - 배리언트 `type=focused(white back)` 자세히 (기준과 다른 부분):
    - 전체: 280x65, 가로 정렬, 여백 위아래 13 (토큰 없음) · 좌우 15 (토큰 없음), 간격 12 (Spacing/12), Corner Radius 12 (Radius/12), 면 background-secondary
  - 배리언트 `type=completed` 자세히 (기준과 다른 부분):
      - Score/Grade 24: 24x24, 부품 Score/Grade 24
