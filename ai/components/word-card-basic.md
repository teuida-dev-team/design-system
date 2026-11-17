# Word Card/Basic

묶음: 여러 기능 패턴 · Word Card

단어 카드 기본형. • 언제: 보캡·퀵리뷰의 단어 문제 카드 • 함께: Button/Choice, Toast/Round • 쓰는 곳: 보캡, 퀵리뷰.

속성: state:default_volume-on·default_volume-off·done_toast·done·failed

- 스펙 (px, 기준 `state=default_volume-on`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 327x479
    - 앞: 277x397, 세로 정렬, 여백 위 39.8 (토큰 없음) · 오른 88.1 (토큰 없음) · 아래 0 · 왼 88.1 (토큰 없음), 간격 8.5 (토큰 없음), Corner Radius 20.3 (토큰 없음), 면 background-secondary, 선 gray-200 (기본 색) 1.6941895484924316
      - Frame 2032: 226x243, 세로 정렬, 간격 25.4 (토큰 없음)
        - Frame 2031: 136x171, 세로 정렬, 간격 8.5 (토큰 없음)
        - Frame 2034: 226x46, 세로 정렬
    - vocap_card: 327x461, 가로 정렬, 여백 위 40 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 24 (Radius/24), 면 background-secondary, 선 gray-200 (기본 색) 2
      - Frame 2032: 267x278, 세로 정렬, 간격 20 (Spacing/20)
        - Frame 2031: 160x202, 세로 정렬, 간격 10 (Spacing/10)
        - Frame 2034: 267x56, 세로 정렬
  - 배리언트 `state=default_volume-on`: 327x479, 글자 text-primary
  - 배리언트 `state=done_toast`: 327x479, 글자 text-primary
  - 배리언트 `state=done`: 327x479, 글자 text-primary
  - 배리언트 `state=default_volume-off`: 327x479, 글자 text-primary
  - 배리언트 `state=failed`: 327x479, 글자 text-primary
  - 배리언트 `state=done_toast` 자세히 (기준과 다른 부분):
      - 앞: 277x398, 세로 정렬, 여백 위 39.8 (토큰 없음) · 오른 88.1 (토큰 없음) · 아래 0 · 왼 88.1 (토큰 없음), 간격 8.5 (토큰 없음), Corner Radius 20.3 (토큰 없음), 면 background-secondary, 선 gray-200 (기본 색) 1.6941895484924316
      - vocap_card: 327x462, 가로 정렬, 여백 위 40 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 24 (Radius/24), 면 background-secondary, 선 green-200 (기본 색) 2
        - Frame 2047: 325x424, 세로 정렬, 간격 40 (토큰 없음)
          - Frame 2032: 267x278, 세로 정렬, 간격 20 (Spacing/20)
          - Frame 2033: 325x106, 가로 정렬, 여백 위아래 9 (토큰 없음) · 좌우 85 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 0 0 24 (토큰 없음) 24 (토큰 없음), 면 green-50 (기본 색)
  - 배리언트 `state=done` 자세히 (기준과 다른 부분):
      - 앞: 277x398, 세로 정렬, 여백 위 39.8 (토큰 없음) · 오른 88.1 (토큰 없음) · 아래 0 · 왼 88.1 (토큰 없음), 간격 8.5 (토큰 없음), Corner Radius 20.3 (토큰 없음), 면 background-secondary, 선 gray-200 (기본 색) 1.6941895484924316
      - vocap_card: 327x462, 가로 정렬, 여백 위 40 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 24 (Radius/24), 면 background-secondary, 선 green-200 (기본 색) 2
        - Frame 2047: 325x424, 세로 정렬, 간격 40 (토큰 없음)
          - Frame 2032: 267x278, 세로 정렬, 간격 20 (Spacing/20)
          - Frame 2033: 325x106, 가로 정렬, 여백 위아래 9 (토큰 없음) · 좌우 85 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 0 0 24 (토큰 없음) 24 (토큰 없음), 면 green-50 (기본 색)
  - 배리언트 `state=default_volume-off` 자세히 (기준과 다른 부분):
      - 앞: 277x398, 세로 정렬, 여백 위 39.8 (토큰 없음) · 오른 88.1 (토큰 없음) · 아래 0 · 왼 88.1 (토큰 없음), 간격 8.5 (토큰 없음), Corner Radius 20.3 (토큰 없음), 면 background-secondary, 선 gray-200 (기본 색) 1.6941895484924316
      - vocap_card: 327x462, 가로 정렬, 여백 위 40 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 24 (Radius/24), 면 background-secondary, 선 gray-200 (기본 색) 2
  - 배리언트 `state=failed` 자세히 (기준과 다른 부분):
      - 앞: 277x398, 세로 정렬, 여백 위 39.8 (토큰 없음) · 오른 88.1 (토큰 없음) · 아래 0 · 왼 88.1 (토큰 없음), 간격 8.5 (토큰 없음), Corner Radius 20.3 (토큰 없음), 면 background-secondary, 선 gray-200 (기본 색) 1.6941895484924316
      - vocap_card: 327x462, 가로 정렬, 여백 위 40 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), Corner Radius 24 (Radius/24), 면 background-secondary, 선 red-200 (기본 색) 2
      - Toast/Round: 116x50, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), Corner Radius 14 (토큰 없음), 면 red-400 (기본 색), 부품 Toast/Round
