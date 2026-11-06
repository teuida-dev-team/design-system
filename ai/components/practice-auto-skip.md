# Practice/Auto Skip

묶음: 기능 전용 · Practice

프랙티스 자동 넘김 피드백. 정답률 70%를 기준으로 격려/위로 문구가 갈리며, 문구는 랜덤 로테이션.

속성: fail:false·true / pause:true·false

- 스펙 (px, 기준 `fail=false, pause=false`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 360x145
    - Rectangle 965: 360x129, 면 green-100 (기본 색)
    - Frame 1787: 319x63, 세로 정렬, 간격 5 (토큰 없음)
      - Group 950: 30x30
        - Ellipse 259 (Stroke): 30x30, 면 green-400 (기본 색)
        - Vector 240 (Stroke): 10x15, 면 green-50 (기본 색)
      - Frame 1786: 319x28, 세로 정렬, 간격 8 (Spacing/8)
        - You’re getting a hang of: 288x28, 글자색 text-correct, 글자 Head 3/B
    - Practice/Auto Skip Cell: 360x24, 가로 정렬, 부품 Practice/Auto Skip Cell
  - 배리언트 `fail=false, pause=false`: 360x145, 글자 text-correct
  - 배리언트 `fail=false, pause=true`: 360x145, 글자 text-correct
  - 배리언트 `fail=true, pause=false`: 360x145, 글자 text-alert
  - 배리언트 `fail=true, pause=true`: 360x145, 글자 text-alert
  - 배리언트 `fail=false, pause=true` 자세히: 기준과 같음
  - 배리언트 `fail=true, pause=false` 자세히 (기준과 다른 부분):
      - Rectangle 965: 360x129, 면 red-100 (기본 색)
        - Group 951: 30x30
          - Group 928: 30x30
          - Group 929: 11x11
          - You can do better next t: 283x28, 글자색 text-alert, 글자 Head 3/B
  - 배리언트 `fail=true, pause=true` 자세히 (기준과 다른 부분):
      - Rectangle 965: 360x129, 면 red-100 (기본 색)
        - Group 951: 30x30
          - Group 928: 30x30
          - Group 929: 11x11
          - You can do better next t: 283x28, 글자색 text-alert, 글자 Head 3/B
