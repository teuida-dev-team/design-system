# Word Card/2 Line

묶음: 여러 기능 패턴 · Word Card

두 줄 단어 카드 (기본·정답·오답). Word Card 가족. 쓰는 곳: 보캡.

속성: type:failed·default·success

- 스펙 (px, 기준 `type=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 272x333
    - 앞: 222x305, 세로 정렬, 여백 위 39.8 (토큰 없음) · 오른 88.1 (토큰 없음) · 아래 0 · 왼 88.1 (토큰 없음), 간격 8.5 (토큰 없음), 모서리 20.3 (토큰 없음), 면 white (기본 색), 선 gray-200 (기본 색) 1.6941895484924316
      - Frame 2032: 226x243, 세로 정렬, 간격 25.4 (토큰 없음)
        - Frame 2031: 136x171, 세로 정렬, 간격 8.5 (토큰 없음)
        - Frame 2034: 226x46, 세로 정렬
    - vocap_card: 272x319, 가로 정렬, 여백 위 14 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), 모서리 24 (Radius/24), 면 white (기본 색), 선 gray-200 (기본 색) 2
      - Frame 2032: 267x208, 세로 정렬, 간격 8 (Spacing/8)
        - Frame 2031: 90x128, 세로 정렬, 간격 6 (Spacing/6)
        - Frame 2034: 267x72, 세로 정렬
  - 배리언트 `type=default`: 272x333, 글자 text-primary
  - 배리언트 `type=success`: 272x333, 글자 text-primary
  - 배리언트 `type=failed`: 272x333, 글자 text-primary
  - 배리언트 `type=success` 자세히 (기준과 다른 부분):
      - vocap_card: 272x319, 가로 정렬, 여백 위 14 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), 모서리 24 (Radius/24), 면 white (기본 색), 선 green-200 (기본 색) 2
        - Frame 2047: 267x304, 세로 정렬, 간격 14 (토큰 없음)
          - Frame 2034: 267x208, 세로 정렬, 간격 8 (Spacing/8)
          - Frame 2033: 267x82, 가로 정렬, 여백 위아래 9 (토큰 없음) · 좌우 85 (토큰 없음), 간격 10 (Spacing/10), 모서리 0 0 24 (토큰 없음) 24 (토큰 없음), 면 green-50 (기본 색)
  - 배리언트 `type=failed` 자세히 (기준과 다른 부분):
      - vocap_card: 272x319, 가로 정렬, 여백 위 14 (토큰 없음) · 오른 104 (토큰 없음) · 아래 0 · 왼 104 (토큰 없음), 간격 10 (Spacing/10), 모서리 24 (Radius/24), 면 white (기본 색), 선 red-200 (기본 색) 2
        - Frame 2047: 267x304, 세로 정렬, 간격 14 (토큰 없음)
          - Frame 2035: 267x208, 세로 정렬, 간격 8 (Spacing/8)
          - Frame 2033: 267x82, 가로 정렬, 여백 위아래 9 (토큰 없음) · 좌우 85 (토큰 없음), 간격 10 (Spacing/10), 모서리 0 0 24 (토큰 없음) 24 (토큰 없음), 면 red-50 (기본 색)
  - ⚠ 토큰에 없는 간격 · 앞: 여백 39.8 → 가까운 값 Spacing/24
  - ⚠ 토큰에 없는 간격 · 앞: 여백 88.1 ×2 → 가까운 값 Spacing/24
  - ⚠ 토큰에 없는 간격 · 앞: 간격 8.5 → 가까운 값 Spacing/8
  - ⚠ 토큰에 없는 모서리 · 앞: 모서리 20.3 → 가까운 값 Radius/24
  - ⚠ 기본 색 사용 · 앞: white → background-secondary · button-second-primary · button-text-tertiary 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · 앞: gray-200 → button-secondary 중 용도에 맞는 것
  - ⚠ 토큰에 없는 간격 · Frame 2032: 간격 25.4 → 가까운 값 Spacing/24
  - ⚠ 토큰에 없는 간격 · Frame 2031: 간격 8.5 → 가까운 값 Spacing/8
  - ⚠ 토큰에 없는 간격 · vocap_card: 여백 14 → 가까운 값 Spacing/12
  - ⚠ 토큰에 없는 간격 · vocap_card: 여백 104 ×2 → 가까운 값 Spacing/24
  - ⚠ 기본 색 사용 · vocap_card: white → background-secondary · button-second-primary · button-text-tertiary 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · vocap_card: gray-200 → button-secondary 중 용도에 맞는 것
