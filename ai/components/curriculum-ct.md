# Curriculum/CT

묶음: 기능 전용 · Curriculum

커리큘럼 카드 277x129(라벨, 제목, 설명). focused, lock, key로 현재·잠김·열쇠 상태를 고름.

속성: focused:false·true / lock:false·true / key:false·true

- 스펙 (px, 기준 `focused=false, lock=false, key=false`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 277x129, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary
    - Curriculum/Lesson Thumbn: 58x58, Corner Radius full (Radius/full), 면 icon-on-color, 부품 Curriculum/Lesson Thumbnail
    - Frame 1059: 164x97, 세로 정렬, 간격 12 (Spacing/12)
      - Label: 31x18, 글자색 text-tertiary, 글자 Caption - M
      - Group 1059: 164x67
        - Lorem Ipsum is simply du: 164x44, 글자색 text-primary, 글자 Head 5 - B
        - Description: 65x16, 글자색 text-secondary, 글자 Caption 2/R
  - 배리언트 `focused=false, lock=false, key=false`: 277x129, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `focused=true, lock=false, key=false`: 277x129, 면 background-secondary, 선 border-highlight, 글자 text-tertiary
  - 배리언트 `focused=false, lock=true, key=false`: 277x129, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `focused=true, lock=true, key=false`: 277x129, 면 background-secondary, 선 border-highlight, 글자 text-tertiary
  - 배리언트 `focused=false, lock=false, key=true`: 277x133, 면 background-secondary, 글자 text-tertiary
  - 배리언트 `focused=true, lock=false, key=true`: 277x133, 면 background-secondary, 선 border-highlight, 글자 text-tertiary
  - 배리언트 `focused=true, lock=false, key=false` 자세히 (기준과 다른 부분):
    - 전체: 277x129, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
  - 배리언트 `focused=false, lock=true, key=false` 자세히 (기준과 다른 부분):
          - Lorem Ipsum is simply du: 164x44, 글자색 text-unselected, 글자 Head 5 - B
          - Description: 65x16, 글자색 text-unselected, 글자 Caption 2/R
  - 배리언트 `focused=true, lock=true, key=false` 자세히 (기준과 다른 부분):
    - 전체: 277x129, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
          - Lorem Ipsum is simply du: 164x44, 글자색 text-unselected, 글자 Head 5 - B
          - Description: 65x16, 글자색 text-unselected, 글자 Caption 2/R
  - 배리언트 `focused=false, lock=false, key=true` 자세히 (기준과 다른 부분):
    - 전체: 277x133, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary
      - Frame 1059: 164x101, 세로 정렬, 간격 12 (Spacing/12)
        - Frame 1706: 164x22, 가로 정렬, 간격 양 끝 정렬
          - Label: 31x18, 글자색 text-tertiary, 글자 Caption - M
          - Badge/Key: 34x22, 가로 정렬, 여백 위 1 (토큰 없음) · 오른 5 (토큰 없음) · 아래 1 (토큰 없음) · 왼 3 (토큰 없음), 간격 1 (토큰 없음), Corner Radius 7 (토큰 없음), 면 button-highlight-soft, 선 border-highlight 1, 부품 Badge/Key
        - Group 1059: 164x67
          - Lorem Ipsum is simply du: 164x44, 글자색 text-primary, 글자 Head 5 - B
          - Description: 65x16, 글자색 text-secondary, 글자 Caption 2/R
  - 배리언트 `focused=true, lock=false, key=true` 자세히 (기준과 다른 부분):
    - 전체: 277x133, 가로 정렬, 여백 위 15 (토큰 없음) · 오른 20 (Spacing/20) · 아래 17 (토큰 없음) · 왼 20 (Spacing/20), 간격 15 (토큰 없음), Corner Radius 14 (토큰 없음), 면 background-secondary, 선 border-highlight 2
      - Frame 1059: 164x101, 세로 정렬, 간격 12 (Spacing/12)
        - Frame 1706: 164x22, 가로 정렬, 간격 양 끝 정렬
          - Label: 31x18, 글자색 text-tertiary, 글자 Caption - M
          - Badge/Key: 34x22, 가로 정렬, 여백 위 1 (토큰 없음) · 오른 5 (토큰 없음) · 아래 1 (토큰 없음) · 왼 3 (토큰 없음), 간격 1 (토큰 없음), Corner Radius 7 (토큰 없음), 면 button-highlight-soft, 선 border-highlight 1, 부품 Badge/Key
        - Group 1059: 164x67
          - Lorem Ipsum is simply du: 164x44, 글자색 icon-primary, 글자 Head 5 - B
          - Description: 65x16, 글자색 text-secondary, 글자 Caption 2/R
