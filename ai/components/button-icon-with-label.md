# Button/Icon With Label

묶음: 공통 · Button

아래 회색 원형 아이콘 버튼 (answer 정답 보기 · skip 건너뛰기). • 언제: 퀴즈·레슨 하단 보조 행동 • 쓰지 말 것: 화면 주요 행동 (→ Button/Full Width) • 함께: Template/Quiz Screen • 쓰는 곳(실제 앱): 레슨.

속성: type:answer·skip

- 스펙 (px, 기준 `type=answer`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 60x54, 세로 정렬, 간격 2 (Spacing/2)
    - Frame 2073: 54x54, 가로 정렬, 여백 위 3.6 (토큰 없음) · 오른 0 · 아래 2.7 (토큰 없음) · 왼 0, 간격 9 (토큰 없음), 모서리 full (Radius/full), 면 black-30 (기본 색) 30%
      - Frame 2421: 30x30, 세로 정렬
        - Group 1822: 30x30
  - 배리언트 `type=answer`: 60x54
  - 배리언트 `type=skip`: 60x54
  - 배리언트 `type=skip` 자세히 (기준과 다른 부분):
      - Frame 2073: 54x54, 가로 정렬, 간격 9 (토큰 없음), 모서리 full (Radius/full), 면 black-30 (기본 색) 30%
        - Group 1823: 19x19
          - Rectangle 41558: 24x3, 모서리 full (Radius/full), 면 button-second-primary
          - Rectangle 41558: 24x3, 모서리 full (Radius/full), 면 button-second-primary
  - ⚠ 토큰에 없는 간격 · Frame 2073: 여백 3.6 → 가까운 값 Spacing/4
  - ⚠ 토큰에 없는 간격 · Frame 2073: 여백 2.7 → 가까운 값 Spacing/2
  - ⚠ 토큰에 없는 간격 · Frame 2073: 간격 9 → 가까운 값 Spacing/8
  - ⚠ 기본 색 사용 · Frame 2073: black-30 → 맞는 용도 토큰 없음 (빈칸)
