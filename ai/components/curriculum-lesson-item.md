# Curriculum/Lesson Item

묶음: 기능 전용 · Curriculum

커리큘럼 행 — 정식 컴포넌트. Default / Focused / Lock / Lock_Focused / Key / Key_Focused.

속성: type:default·focused·lock·lock_focused·key·key_focused

- 스펙 (px, 기준 `type=default`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 277x128, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary
    - Curriculum/Lesson Thumbn: 58x58, Corner Radius full (Radius/full), 면 icon-on-color, 부품 Curriculum/Lesson Thumbnail
    - Frame 1059: 164x96, 세로 정렬, 간격 13 (토큰 없음)
      - Expression: 63x16, 글자색 text-tertiary, 글자 Caption - M
      - Group 1059: 164x67
        - Hello/ Nice to meet you: 164x44, 글자색 text-primary, 글자 Head 5 - B
        - 안녕하세요/ 반가워요: 107x16, 글자색 text-secondary, 글자 Caption 2/R
  - 배리언트 `type=default`: 277x128, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `type=focused`: 277x128, 면 background-secondary, 선 border-highlight, 글자 text-tertiary
  - 배리언트 `type=lock`: 277x128, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `type=lock_focused`: 277x128, 면 background-secondary, 선 border-highlight, 글자 text-tertiary
  - 배리언트 `type=key`: 277x134, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `type=key_focused`: 277x134, 면 background-secondary, 선 border-highlight, 글자 text-tertiary
  - 배리언트 `type=focused` 자세히 (기준과 다른 부분):
    - 전체: 277x128, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
  - 배리언트 `type=lock` 자세히 (기준과 다른 부분):
          - Hello/ Nice to meet you: 164x44, 글자색 text-unselected, 글자 Head 5 - B
          - 안녕하세요/ 반가워요: 107x16, 글자색 text-unselected, 글자 Caption 2/R
  - 배리언트 `type=lock_focused` 자세히 (기준과 다른 부분):
    - 전체: 277x128, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
          - Hello/ Nice to meet you: 164x44, 글자색 text-unselected, 글자 Head 5 - B
          - 안녕하세요/ 반가워요: 107x16, 글자색 text-unselected, 글자 Caption 2/R
  - 배리언트 `type=key` 자세히 (기준과 다른 부분):
    - 전체: 277x134, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary
      - Frame 1059: 164x102, 세로 정렬, 간격 13 (토큰 없음)
        - Frame 1672: 164x22, 가로 정렬, 간격 양 끝 정렬
          - Expression: 63x16, 글자색 text-tertiary, 글자 Caption - M
          - Badge/Key: 34x22, 가로 정렬, 여백 위 1 (토큰 없음) · 오른 5 (토큰 없음) · 아래 1 (토큰 없음) · 왼 3 (토큰 없음), 간격 1 (토큰 없음), Corner Radius 7 (토큰 없음), 면 button-highlight-soft 70%, 선 border-highlight 1, 부품 Badge/Key
        - Group 1059: 164x67
          - Hello/ Nice to meet you: 164x44, 글자색 text-primary, 글자 Head 5 - B
          - 안녕하세요/ 반가워요: 107x16, 글자색 text-secondary, 글자 Caption 2/R
  - 배리언트 `type=key_focused` 자세히 (기준과 다른 부분):
    - 전체: 277x134, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
      - Frame 1059: 164x102, 세로 정렬, 간격 13 (토큰 없음)
        - Frame 1672: 164x22, 가로 정렬, 간격 양 끝 정렬
          - Expression: 63x16, 글자색 text-tertiary, 글자 Caption - M
          - Badge/Key: 34x22, 가로 정렬, 여백 위 1 (토큰 없음) · 오른 5 (토큰 없음) · 아래 1 (토큰 없음) · 왼 3 (토큰 없음), 간격 1 (토큰 없음), Corner Radius 7 (토큰 없음), 면 button-highlight-soft 70%, 선 border-highlight 1, 부품 Badge/Key
        - Group 1059: 164x67
          - Hello/ Nice to meet you: 164x44, 글자색 text-primary, 글자 Head 5 - B
          - 안녕하세요/ 반가워요: 107x16, 글자색 text-secondary, 글자 Caption 2/R
