# Progress/Step Dots

묶음: 공통 · Progress

점으로 된 단계 진행 표시(현재까지 민트). 팝업 안 여러 장 넘기기 등.

속성: shape:dot_10dp_1of10·dot_10dp_2of10·…·dot_8dp

- 스펙 (px, 기준 `shape=dot_10dp_1of10`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 181x10, 가로 정렬, 간격 9 (토큰 없음)
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
    - Progress/Bar Cell: 10x10, 부품 Progress/Bar Cell
  - 배리언트 `shape=dot_10dp_1of10`: 181x10
  - 배리언트 `shape=dot_10dp_2of10`: 181x10
  - 배리언트 `shape=dot_10dp_3of10`: 181x10
  - 배리언트 `shape=dot_10dp_10of10`: 181x10
  - 배리언트 `shape=dot_8dp`: 152x8
  - 배리언트 `shape=dot_10dp_2of10` 자세히: 기준과 같음
  - 배리언트 `shape=dot_10dp_3of10` 자세히: 기준과 같음
  - 배리언트 `shape=dot_10dp_10of10` 자세히: 기준과 같음
  - 배리언트 `shape=dot_8dp` 자세히 (기준과 다른 부분):
    - 전체: 152x8, 가로 정렬, 간격 8 (Spacing/8)
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
      - Progress/Bar Cell: 8x8, 부품 Progress/Bar Cell
  - ⚠ 토큰에 없는 간격 · 전체: 간격 9 → 가까운 값 Spacing/8
