# Navigation/Text Tab

묶음: 공통 · Navigation

리뷰 탭 위 All처럼 글자로 된 탭. 선택되면 아래에 밑줄이 생김.

속성: type:tabmenu_focused·tabmenu_default

- 스펙 (px, 기준 `type=tabmenu_focused`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 19x29, 세로 정렬, 간격 6 (Spacing/6)
    - All: 19x20, 글자색 gray-50 (기본 색), 글자 Subtitle 2 -B
    - Rectangle 858: 19x3, 모서리 full (Radius/full), 면 green-500 (기본 색)
  - 배리언트 `type=tabmenu_focused`: 19x29, 글자 gray-50 (기본 색)
  - 배리언트 `type=tabmenu_default`: 19x29, 글자 text-secondary
  - 배리언트 `type=tabmenu_default` 자세히 (기준과 다른 부분):
      - All: 19x20, 글자색 text-secondary, 글자 Subtitle 2 -B
