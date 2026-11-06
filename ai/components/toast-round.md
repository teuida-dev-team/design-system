# Toast/Round

묶음: 공통 · Toast

정답·오답 결과 토스트. • 언제: 퀴즈 결과 알림 • 쓰지 말 것: 일반 안내 (→ Toast/Basic) • 함께: Button/Choice, Word Card • 쓰는 곳(실제 앱): 리뷰 · 보캡.

속성: type:failed·success·success2

- 스펙 (px, 기준 `type=success`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 117x50, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 green-400 (기본 색)
    - Frame 2038: 85x26, 가로 정렬, 간격 6 (Spacing/6)
      - Good job!: 85x26, 글자색 white (기본 색), 글자 Head 4/B
  - 배리언트 `type=success`: 117x50, 면 green-400 (기본 색), 글자 white (기본 색)
  - 배리언트 `type=success2`: 114x50, 면 green-400 (기본 색), 글자 white (기본 색)
  - 배리언트 `type=failed`: 116x50, 면 red-400 (기본 색), 글자 white (기본 색)
  - 배리언트 `type=success2` 자세히 (기준과 다른 부분):
    - 전체: 114x50, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 green-400 (기본 색)
      - Frame 2038: 82x26, 가로 정렬, 간격 6 (Spacing/6)
        - Icon/Checkboxes 28: 24x24, 부품 Icon/Checkboxes 28
        - Good!: 52x26, 글자색 white (기본 색), 글자 Head 4/B
  - 배리언트 `type=failed` 자세히 (기준과 다른 부분):
    - 전체: 116x50, 가로 정렬, 여백 위아래 12 (Spacing/12) · 좌우 16 (Spacing/16), 간격 10 (Spacing/10), 모서리 14 (토큰 없음), 면 red-400 (기본 색)
      - Frame 2038: 84x26, 가로 정렬, 간격 6 (Spacing/6)
        - Try again: 84x26, 글자색 white (기본 색), 글자 Head 4/B
  - ⚠ 토큰에 없는 모서리 · 전체: 모서리 14 → 가까운 값 Radius/12
  - ⚠ 기본 색 사용 · 전체: green-400 → button-highlight · button-tag · border-success 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · Good job!: white → text-on-color · text-inactive · button-text-tertiary 중 용도에 맞는 것
  - ⚠ 기본 색 사용 · 배리언트 type=success: 면 green-400 → button-highlight · button-tag · border-success
  - ⚠ 기본 색 사용 · 배리언트 type=success: 글자 white → text-on-color · text-inactive · button-text-tertiary
  - ⚠ 기본 색 사용 · 배리언트 type=success2: 면 green-400 → button-highlight · button-tag · border-success
  - ⚠ 기본 색 사용 · 배리언트 type=success2: 글자 white → text-on-color · text-inactive · button-text-tertiary
  - ⚠ 기본 색 사용 · 배리언트 type=failed: 면 red-400 → icon-highlight-red · text-failed · border-error
  - ⚠ 기본 색 사용 · 배리언트 type=failed: 글자 white → text-on-color · text-inactive · button-text-tertiary
