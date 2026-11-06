# Button/Circle Icon

묶음: 공통 · Button

원형 아이콘 버튼 (소리·마이크·체크). • 언제: 글자 없이 아이콘 하나로 끝나는 작은 행동 (소리 듣기 등) • 쓰지 말 것: 글자가 필요한 행동 • 함께: Review/List Item, Word Card

속성: state:mic·ic_check·audio_off·audio_m_off·audio_on·audio_m_on

- 스펙 (px, 기준 `state=ic_check`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 36x36, 가로 정렬, 여백 10 (Spacing/10), 간격 6.7 (토큰 없음), 모서리 24 (Radius/24), 면 blue-100 (기본 색)
    - ic_checkboxes: 25x25
      - Icon (Stroke): 18x13, 면 blue-400 (기본 색)
  - 배리언트 `state=mic`: 36x36, 면 button-secondary
  - 배리언트 `state=audio_ off`: 28x28, 면 button-secondary
  - 배리언트 `state=audio_m_off`: 40x40, 면 button-secondary
  - 배리언트 `state=audio_on`: 28x28, 면 button-primary
  - 배리언트 `state=audio_m_on`: 40x40, 면 button-primary
  - 배리언트 `state=ic_check`: 36x36, 면 blue-100 (기본 색)
  - 배리언트 `state=mic` 자세히 (기준과 다른 부분):
    - 전체: 36x36, 가로 정렬, 여백 10 (Spacing/10), 간격 6.7 (토큰 없음), 모서리 full (Radius/full), 면 button-secondary
      - Icon/Mic On 28: 17x17, 부품 Icon/Mic On 28
  - 배리언트 `state=audio_ off` 자세히 (기준과 다른 부분):
    - 전체: 28x28, 가로 정렬, 여백 10 (Spacing/10), 간격 6.7 (토큰 없음), 모서리 12 (Radius/12), 면 button-secondary
      - Lesson/Volume: 18x18, 부품 Audio/Volume
  - 배리언트 `state=audio_m_off` 자세히 (기준과 다른 부분):
    - 전체: 40x40, 가로 정렬, 여백 14.3 (토큰 없음), 간격 9.5 (토큰 없음), 모서리 17.1 (토큰 없음), 면 button-secondary
      - Lesson/Volume: 24x24, 부품 Audio/Volume
  - 배리언트 `state=audio_on` 자세히 (기준과 다른 부분):
    - 전체: 28x28, 가로 정렬, 여백 10 (Spacing/10), 간격 6.7 (토큰 없음), 모서리 12 (Radius/12), 면 button-primary
      - Lesson/Volume: 18x18, 부품 Audio/Volume
  - 배리언트 `state=audio_m_on` 자세히 (기준과 다른 부분):
    - 전체: 40x40, 가로 정렬, 여백 14.3 (토큰 없음), 간격 9.5 (토큰 없음), 모서리 17.1 (토큰 없음), 면 button-primary
      - Lesson/Volume: 24x24, 부품 Audio/Volume
