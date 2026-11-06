# Button/Full Width

묶음: 공통 · Button

화면 폭 꽉 찬 글자 버튼 (모서리 8). • 언제: 화면 아래 주요 행동(계속·확인·구매), 폼 제출. size 48·54, style fill·outline·white • 쓰지 말 것: 한 화면에 fill 버튼 2개 이상, 알약(둥근) 모양으로 바꾸기, 카드 안 작은 행동(→ Button/Sub 38) • 함께: Template/Quiz Screen 아래, Dialog/Basic • 쓰는 곳(실제 앱): 온보딩 · 설정.

속성: size:48·54 / style:fill·outline·white / state:disabled·enabled

- 스펙 (px, 기준 `size=48, style=fill, state=enabled`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 327x48, 가로 정렬, 여백 위아래 10 (Spacing/10) · 좌우 105 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 button-primary
    - Text / titlebar: 59x22, 글자색 button-text-tertiary, 글자 Subtitle 1/B
  - 배리언트 `size=48, style=fill, state=enabled`: 327x48, 면 button-primary, 글자 button-text-tertiary
  - 배리언트 `size=48, style=fill, state=disabled`: 327x48, 면 button-inactive, 글자 button-text-inactive
  - 배리언트 `size=48, style=outline, state=disabled`: 327x48, 선 button-outline-secondary, 글자 button-text-inactive
  - 배리언트 `size=48, style=outline, state=enabled`: 327x48, 선 button-outline-secondary, 글자 button-text-secondary
  - 배리언트 `size=54, style=white, state=enabled`: 327x54, 면 white (기본 색), 글자 text-highlight
  - 배리언트 `size=54, style=fill, state=enabled`: 327x54, 면 green-500 (기본 색), 선 border-primary, 글자 button-text-tertiary
  - 배리언트 `size=48, style=fill, state=disabled` 자세히 (기준과 다른 부분):
    - 전체: 327x48, 가로 정렬, 여백 위아래 10 (Spacing/10) · 좌우 105 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 button-inactive
      - Text / titlebar: 59x22, 글자색 button-text-inactive, 글자 Subtitle 1/B
  - 배리언트 `size=48, style=outline, state=disabled` 자세히 (기준과 다른 부분):
    - 전체: 327x48, 가로 정렬, 여백 위아래 10 (Spacing/10) · 좌우 105 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 선 button-outline-secondary 1
      - Text / titlebar: 59x22, 글자색 button-text-inactive, 글자 Subtitle 1/B
  - 배리언트 `size=48, style=outline, state=enabled` 자세히 (기준과 다른 부분):
    - 전체: 327x48, 가로 정렬, 여백 위아래 10 (Spacing/10) · 좌우 105 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 선 button-outline-secondary 1
      - Text / titlebar: 59x22, 글자색 button-text-secondary, 글자 Subtitle 1/B
  - 배리언트 `size=54, style=white, state=enabled` 자세히 (기준과 다른 부분):
    - 전체: 327x54, 세로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 18 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 white (기본 색)
      - Frame 1905: 60x22, 가로 정렬, 간격 14 (토큰 없음)
        - Frame 1904: 60x22, 세로 정렬
          - Text / titlebar: 60x22, 글자색 text-highlight, 글자 Subtitle 1/B
  - 배리언트 `size=54, style=fill, state=enabled` 자세히 (기준과 다른 부분):
    - 전체: 327x54, 세로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 18 (토큰 없음), 간격 10 (Spacing/10), 모서리 8 (Radius/8), 면 green-500 (기본 색), 선 border-primary 1
      - Frame 1905: 54x22, 가로 정렬, 간격 14 (토큰 없음)
        - Frame 1904: 54x22, 세로 정렬
          - Text / titlebar: 54x22, 글자색 button-text-tertiary, 글자 Subtitle 1/B
  - ⚠ 토큰에 없는 간격 · 전체: 여백 105 ×2 → 가까운 값 Spacing/24
  - ⚠ 기본 색 사용 · 배리언트 size=54, style=white, state=enabled: 면 white → background-secondary · button-second-primary · button-text-tertiary
  - ⚠ 기본 색 사용 · 배리언트 size=54, style=fill, state=enabled: 면 green-500 → button-primary · icon-highlight · text-highlight
  - ⚠ 글자 스타일이 Subtitle 1/B예요. 버튼 전용 Button 1/B가 맞는지 확인이 필요해요
  - ⚠ 좌우 여백 105는 글자를 가운데 두려고 넣은 값이에요. 가운데 정렬 + 폭 채움으로 바꾸면 숫자가 필요 없어요
