# Curriculum/Review Quiz Item

묶음: 기능 전용 · Curriculum

레슨 탭 커리큘럼의 리뷰 퀴즈 줄 (기본·포커스·잠김).

속성: type:default·focused·lock

- 스펙 (px, 기준 `type=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 277x77, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 26 (토큰 없음), 간격 22 (토큰 없음), 모서리 14 (토큰 없음), 면 background-secondary
    - Curriculum/Review Quiz T: 45x45, 부품 Curriculum/Review Quiz Thumbnail
    - Frame 1059: 164x22, 세로 정렬, 간격 13 (토큰 없음)
      - Group 1059: 164x22
        - Review Quiz: 164x22, 글자색 text-primary, 글자 Head 5 - B
  - 배리언트 `type=default`: 277x77, 면 background-secondary, 글자 text-primary
  - 배리언트 `type=focused`: 277x77, 면 background-secondary, 선 border-highlight, 글자 text-primary
  - 배리언트 `type=lock`: 277x77, 면 background-secondary, 글자 text-unselected
  - 배리언트 `type=focused` 자세히 (기준과 다른 부분):
    - 전체: 277x77, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 26 (토큰 없음), 간격 22 (토큰 없음), 모서리 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
  - 배리언트 `type=lock` 자세히 (기준과 다른 부분):
          - Review Quiz: 164x22, 글자색 text-unselected, 글자 Head 5 - B
