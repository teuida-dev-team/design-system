# Dialog/Middle Preset

묶음: 공통 · Dialog

예전 가운데 팝업 모음(280px). 새 화면은 Dialog/Basic을 씀.

속성: type:text·text+img 1·text+img 1+close+progressbar·text+img 2·text+img 2+close+progressbar

- 스펙 (px, 기준 `type=text`; 괄호 = 토큰 이름, "토큰 없음" = 숫자·색 직접):
  - 전체: 280x156, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 12 (Spacing/12), 면 background-secondary
    - Ipsum Lorem is simply du: 240x56, 글자색 text-primary, 글자 Head 3 - EB
    - Lorem Ipsum is simply du: 240x40, 글자색 text-primary, 글자 Body 2 - R
    - Lorem Ipsum is simply du: 240x36, 글자색 text-secondary, 글자 Caption - R
  - 배리언트 `type=text`: 280x156, 면 background-secondary, 글자 text-primary
  - 배리언트 `type=text+img 1`: 280x478, 면 background-secondary
  - 배리언트 `type=text+img 1+close+progressbar`: 280x558, 면 background-secondary
  - 배리언트 `type=text+img 2`: 280x478, 면 background-secondary
  - 배리언트 `type=text+img 2+close+progressbar`: 280x480, 면 background-secondary
  - 배리언트 `type=text+img 1` 자세히 (기준과 다른 부분):
    - 전체: 280x478, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 16 (Spacing/16), 면 background-secondary
      - Image/Illust Times Spoke: 240x240, 부품 Image/Illust Times Spoken2
      - Dialog/Middle Preset: 240x222, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 12 (Spacing/12), 면 background-secondary, 부품 Dialog/Middle Preset
  - 배리언트 `type=text+img 1+close+progressbar` 자세히 (기준과 다른 부분):
    - 전체: 280x558, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 16 (Spacing/16), 면 background-secondary
      - Bottom Sheet/Top: 240x20, 가로 정렬, 간격 10 (Spacing/10), 면 background-secondary, 부품 Bottom Sheet/Top
      - Image/Illust Times Spoke: 240x240, 부품 Image/Illust Times Spoken2
      - Dialog/Middle Preset: 240x222, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 12 (Spacing/12), 면 background-secondary, 부품 Dialog/Middle Preset
      - Progress/Bar: 240x28, 가로 정렬, 여백 위 20 (토큰 없음) · 오른 0 · 아래 0 · 왼 0, 간격 8 (Spacing/8), 부품 Progress/Step Dots
  - 배리언트 `type=text+img 2` 자세히 (기준과 다른 부분):
    - 전체: 280x478, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 16 (Spacing/16), 면 background-secondary
      - Image/Illust Times Spoke: 240x240, 부품 Image/Illust Times Spoken2
      - Dialog/Middle Preset: 240x222, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 12 (Spacing/12), 면 background-secondary, 부품 Dialog/Middle Preset
  - 배리언트 `type=text+img 2+close+progressbar` 자세히 (기준과 다른 부분):
    - 전체: 280x480, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 양 끝 정렬, 면 background-secondary
      - Bottom Sheet/Top: 240x20, 가로 정렬, 간격 10 (Spacing/10), 면 background-secondary, 부품 Bottom Sheet/Top
      - Dialog/Middle Preset: 240x222, 세로 정렬, 여백 위아래 0 · 좌우 20 (Spacing/20), 간격 12 (Spacing/12), 면 background-secondary, 부품 Dialog/Middle Preset
      - Image/Illust Times Spoke: 240x240, 부품 Image/Illust Times Spoken2
      - Progress/Bar: 240x28, 가로 정렬, 여백 위 20 (토큰 없음) · 오른 0 · 아래 0 · 왼 0, 간격 8 (Spacing/8), 부품 Progress/Step Dots
  - ⚠ 옛 텍스트 스타일 · Ipsum Lorem is simply du: Head 3 - EB → Head 3/EB
  - ⚠ 옛 텍스트 스타일 · Lorem Ipsum is simply du: Body 2 - R → Body 2/R
  - ⚠ 옛 텍스트 스타일 · Lorem Ipsum is simply du: Caption - R → Caption/R
