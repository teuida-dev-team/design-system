# Streak/Calendar Date Cell

묶음: 기능 전용 · Streak

캘린더 날짜 숫자 칸 44x28. 기본, 선택, 연속 구간(시작·중간·끝) 모양을 고름.

속성: type:freezemiddle·active·today·default·milestone·start

- 스펙 (px, 기준 `type=active`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 42x28
    - Ellipse 333: 28x28, 면 button-primary
    - 1: 8x20, 글자색 text-on-color, 글자 Bold 13 (스타일 없음)
  - 배리언트 `type=freezemiddle`: 42x28, 글자 text-on-color
  - 배리언트 `type=active`: 42x28, 글자 text-on-color
  - 배리언트 `type=today`: 42x28, 글자 text-on-color
  - 배리언트 `type=default`: 42x28, 글자 text-tertiary
  - 배리언트 `type=milestone`: 42x28, 글자 text-tertiary
  - 배리언트 `type=start`: 42x28, 글자 text-on-color
  - 배리언트 `type=middle`: 42x28, 글자 text-on-color
  - 배리언트 `type=end`: 42x28, 글자 text-on-color
  - 배리언트 `type=freezeend`: 42x28, 글자 text-on-color
  - 배리언트 `type=freezestart`: 42x28, 글자 text-on-color
  - 배리언트 `type=freezemiddle` 자세히 (기준과 다른 부분):
      - Rectangle 1111: 42x28, 면 button-primary
      - Vector: 24x28, 면 icon-bubble
      - 1: 8x20, 글자색 text-on-color, 글자 Bold 13 (스타일 없음)
  - 배리언트 `type=today` 자세히 (기준과 다른 부분):
      - Ellipse 333: 28x28, 면 icon-unselected
  - 배리언트 `type=default` 자세히 (기준과 다른 부분):
      - 1: 8x20, 글자색 text-tertiary, 글자 Bold 13 (스타일 없음)
  - 배리언트 `type=milestone` 자세히 (기준과 다른 부분):
      - Union: 28x28, 면 button-highlight-soft
        - Ellipse 333: 15x15, 면 #D9D9D9 (토큰 없음)
        - Ellipse 335: 15x15, 면 #D9D9D9 (토큰 없음)
        - Ellipse 334: 15x15, 면 #D9D9D9 (토큰 없음)
        - Ellipse 336: 15x15, 면 #D9D9D9 (토큰 없음)
        - Ellipse 337: 15x15, 면 #D9D9D9 (토큰 없음)
      - 1: 8x20, 글자색 text-tertiary, 글자 Bold 13 (스타일 없음)
  - 배리언트 `type=start` 자세히 (기준과 다른 부분):
      - Rectangle 1111: 21x28, 면 button-primary
      - Ellipse 333: 28x28, 면 button-primary
      - 1: 8x20, 글자색 text-on-color, 글자 Bold 13 (스타일 없음)
  - 배리언트 `type=middle` 자세히 (기준과 다른 부분):
      - Rectangle 1111: 42x28, 면 button-primary
  - 배리언트 `type=end` 자세히 (기준과 다른 부분):
      - Rectangle 1111: 21x28, 면 button-primary
      - Ellipse 333: 28x28, 면 button-primary
      - 1: 8x20, 글자색 text-on-color, 글자 Bold 13 (스타일 없음)
  - 배리언트 `type=freezeend` 자세히 (기준과 다른 부분):
      - Rectangle 1111: 21x28, 면 button-primary
      - Vector: 24x28, 면 icon-bubble
      - 1: 8x20, 글자색 text-on-color, 글자 Bold 13 (스타일 없음)
  - 배리언트 `type=freezestart` 자세히 (기준과 다른 부분):
      - Rectangle 1111: 21x28, 면 button-primary
      - Vector: 24x28, 면 icon-bubble
      - 1: 8x20, 글자색 text-on-color, 글자 Bold 13 (스타일 없음)
  - ⚠ 텍스트 스타일 없음 · 1: Bold 13 → Subtitle 2/B (크기 13→14)
