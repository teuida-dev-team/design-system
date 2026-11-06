# Curriculum/Day Order

묶음: 기능 전용 · Curriculum

홈 커리큘럼의 Day 원 45x45. type으로 점수(완료), 현재(Active), 잠김(Inactive)을 고름.

속성: type:active·inactive·score

- 스펙 (px, 기준 `type=active`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 45x45
    - Group 1052: 45x45
      - Ellipse 249: 45x45, 면 background-secondary, 선 background-secondary 3
      - Day 01: 25x34, 글자색 text-highlight, 글자 Bold 11 (스타일 없음)
  - 배리언트 `type=active`: 45x45, 글자 text-highlight
  - 배리언트 `type=inactive`: 45x45, 글자 icon-on-color
  - 배리언트 `type=score`: 45x45
  - 배리언트 `type=inactive` 자세히 (기준과 다른 부분):
        - Ellipse 249: 45x45, 면 icon-inactive, 선 icon-inactive 3
        - Day 01: 25x34, 글자색 icon-on-color, 글자 Bold 11 (스타일 없음)
  - 배리언트 `type=score` 자세히 (기준과 다른 부분):
      - Score/Grade 30: 29x29, 부품 Score/Grade 30
  - ⚠ 텍스트 스타일 없음 · Day 01: Bold 11 → Caption 2/B (크기 11→12)
