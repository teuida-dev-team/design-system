# Bottom Sheet/Basic

묶음: 공통 · Bottom Sheet

아래에서 올라오는 시트 (제목·본문·내용 칸·버튼). • 언제: 옵션 고르기, 정렬, 추가 설명 • 쓰지 말 것: 짧은 확인 (→ Dialog/Basic) • 함께: Bottom Sheet/Content Slot, System/Sheet Top iOS 26

속성: button:false·true

- 스펙 (px, 기준 `button=false`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 375x290, 세로 정렬, 여백 위 16 (Spacing/16) · 오른 20 (Spacing/20) · 아래 34 (토큰 없음) · 왼 20 (Spacing/20), 간격 20 (Spacing/20), 모서리 20 (토큰 없음) 20 (토큰 없음) 0 0, 면 background-secondary
    - Top: 335x24, 가로 정렬
      - Close: 24x24, 부품 Icon/Close 24
    - Text: 335x56, 세로 정렬, 간격 8 (Spacing/8)
      - Title: 335x28, 글자색 text-primary, 글자 Head 3/B
      - Body: 335x20, 글자색 text-secondary, 글자 Body 2/R
    - Content: 335x120, 세로 정렬, 모서리 12 (Radius/12), 선 border-tertiary 1, 부품 Bottom Sheet/Content Slot
  - 배리언트 `button=false`: 375x290, 면 background-secondary, 글자 text-primary
  - 배리언트 `button=true`: 375x360, 면 background-secondary, 글자 text-primary
  - 배리언트 `button=true` 자세히 (기준과 다른 부분):
    - 전체: 375x360, 세로 정렬, 여백 위 16 (Spacing/16) · 오른 20 (Spacing/20) · 아래 34 (토큰 없음) · 왼 20 (Spacing/20), 간격 20 (Spacing/20), 모서리 20 (토큰 없음) 20 (토큰 없음) 0 0, 면 background-secondary
      - Primary Button: 335x50, 가로 정렬, 여백 위아래 14 (토큰 없음) · 좌우 50 (토큰 없음), 간격 10 (토큰 없음), 모서리 50 (토큰 없음), 면 button-primary, 부품 Button/1
