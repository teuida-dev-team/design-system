# Dialog/Basic

묶음: 공통 · Dialog

화면 가운데 확인 창 (제목·본문·버튼 1~2개). • 언제: 로그아웃·삭제·나가기처럼 한 번 더 묻는 확인 • 쓰지 말 것: 선택지가 3개 이상이거나 내용이 길 때 (→ Bottom Sheet/Basic). ※ 안 버튼은 게시 후 Button/Full Width로 교체 예정 • 함께: Button/Full Width

속성: buttons:two·one / image:false·true

- 스펙 (px, 기준 `buttons=two, image=false`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 298x200, 세로 정렬, 여백 위 28 (토큰 없음) · 오른 24 (Spacing/24) · 아래 24 (Spacing/24) · 왼 24 (Spacing/24), 간격 24 (Spacing/24), 모서리 20 (토큰 없음), 면 background-secondary
    - Text: 250x80, 세로 정렬, 간격 12 (Spacing/12)
      - Title: 250x28, 글자색 text-primary, 글자 Head 3/EB
      - Body: 250x40, 글자색 text-secondary, 글자 Body 2/R
    - Buttons: 250x44, 가로 정렬, 간격 8 (Spacing/8)
      - Secondary Button: 121x44, 가로 정렬, 여백 12 (토큰 없음), 간격 10 (토큰 없음), 모서리 50 (토큰 없음), 면 button-secondary, 부품 Button/2
      - Primary Button: 121x44, 가로 정렬, 여백 12 (토큰 없음), 간격 10 (토큰 없음), 모서리 50 (토큰 없음), 면 button-primary, 부품 Button/2
  - 배리언트 `buttons=two, image=false`: 298x200, 면 background-secondary, 글자 text-primary
  - 배리언트 `buttons=one, image=false`: 298x200, 면 background-secondary, 글자 text-primary
  - 배리언트 `buttons=two, image=true`: 298x364, 면 background-secondary, 글자 text-primary
  - 배리언트 `buttons=one, image=true`: 298x364, 면 background-secondary, 글자 text-primary
  - 배리언트 `buttons=one, image=false` 자세히 (기준과 다른 부분):
        - Primary Button: 250x44, 가로 정렬, 여백 12 (토큰 없음), 간격 10 (토큰 없음), 모서리 50 (토큰 없음), 면 button-primary, 부품 Button/2
  - 배리언트 `buttons=two, image=true` 자세히 (기준과 다른 부분):
    - 전체: 298x364, 세로 정렬, 여백 위 28 (토큰 없음) · 오른 24 (Spacing/24) · 아래 24 (Spacing/24) · 왼 24 (Spacing/24), 간격 24 (Spacing/24), 모서리 20 (토큰 없음), 면 background-secondary
      - Image: 250x140, 모서리 12 (토큰 없음), 면 background-tertiary
      - Text: 250x80, 세로 정렬, 간격 12 (Spacing/12)
        - Title: 250x28, 글자색 text-primary, 글자 Head 3/EB
        - Body: 250x40, 글자색 text-secondary, 글자 Body 2/R
      - Buttons: 250x44, 가로 정렬, 간격 8 (Spacing/8)
        - Secondary Button: 121x44, 가로 정렬, 여백 12 (토큰 없음), 간격 10 (토큰 없음), 모서리 50 (토큰 없음), 면 button-secondary, 부품 Button/2
        - Primary Button: 121x44, 가로 정렬, 여백 12 (토큰 없음), 간격 10 (토큰 없음), 모서리 50 (토큰 없음), 면 button-primary, 부품 Button/2
  - 배리언트 `buttons=one, image=true` 자세히 (기준과 다른 부분):
    - 전체: 298x364, 세로 정렬, 여백 위 28 (토큰 없음) · 오른 24 (Spacing/24) · 아래 24 (Spacing/24) · 왼 24 (Spacing/24), 간격 24 (Spacing/24), 모서리 20 (토큰 없음), 면 background-secondary
      - Image: 250x140, 모서리 12 (토큰 없음), 면 background-tertiary
      - Text: 250x80, 세로 정렬, 간격 12 (Spacing/12)
        - Title: 250x28, 글자색 text-primary, 글자 Head 3/EB
        - Body: 250x40, 글자색 text-secondary, 글자 Body 2/R
      - Buttons: 250x44, 가로 정렬, 간격 8 (Spacing/8)
        - Primary Button: 250x44, 가로 정렬, 여백 12 (토큰 없음), 간격 10 (토큰 없음), 모서리 50 (토큰 없음), 면 button-primary, 부품 Button/2
