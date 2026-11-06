# Badge/Unit Badge

묶음: 여러 기능 패턴 · Badge

유닛 배지 (활성·비활성). • 언제: 커리큘럼과 레슨 완료에서 유닛 표시 • 함께: Curriculum/Unit Title • 쓰는 곳(실제 앱): 레슨 · 홈.

속성: type:inactive·active

- 스펙 (px, 기준 `type=inactive`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 160x130, 세로 정렬, 간격 -22 (토큰 없음)
    - UnitBadgeSet/Default: 130x130, 부품 UnitBadgeSet/Default
    - Frame 1702: 160x20, 가로 정렬, 여백 위 0 · 오른 0 · 아래 0 · 왼 130 (토큰 없음)
      - 0/10: 30x20, 글자 Button 2/B
  - 배리언트 `type=inactive`: 160x130
  - 배리언트 `type=active`: 168x130
  - 배리언트 `type=active` 자세히 (기준과 다른 부분):
    - 전체: 168x130, 세로 정렬, 간격 -22 (토큰 없음)
      - Frame 1702: 168x20, 가로 정렬, 여백 위 0 · 오른 0 · 아래 0 · 왼 130 (토큰 없음)
        - 10/10: 38x20, 글자 Button 2/B
  - ⚠ 목록에 없는 부품 사용 · UnitBadgeSet/Default: UnitBadgeSet/Default → 같은 종류의 현행 부품으로 교체
  - ⚠ 토큰에 없는 간격 · Frame 1702: 여백 130 → 가까운 값 Spacing/24
