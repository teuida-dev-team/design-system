# 스트릭 가이드라인

스트릭은 **식물이 자라는 모습**으로 연속 학습일을 보여줘요. 부품이 17개로 많은데, 대부분 서로를 품고 있어서 **어느 하나만 바꾸면 다른 데가 같이 바뀌어요.** 그래서 임의로 고치지 않는 게 가장 중요해요.

## 어느 부품을 언제 쓰나

| 어디에 | 부품 | 크기 |
|---|---|---|
| 스트릭 달력 칸 안의 식물 | `Streak/Calendar Icon` | 90×90 |
| 식물 얼굴 (표정만) | `Streak/Status Icon` | 52×40 |
| 레슨 화면 떠 있는 버튼 | `Streak/Floating Button Set` | 55×65 |
| 그 버튼의 원 부분만 | `Streak/Floating Button` | 55×55 |
| 민트 바탕 위 불꽃 | `Streak/Icon 20 Green` · `Icon 40 Green` | 20×20 · 40×40 |
| 흰 바탕·컬러 면 위 불꽃 | `Streak/Icon 40 White` | 40×40 |
| iOS 홈화면 위젯 | `Widget/Streak` | 158×158 |
| 달력 한 달 | `Streak/Calendar Month` | 300×306 |
| 달력 날짜 한 칸 | `Streak/Calendar Date Cell` | 42×28 |
| 프리즈 아이템 칸 | `Streak/Freeze Item` | 56×56 |

**불꽃 아이콘은 바탕색으로 골라요.** 민트·진한 면 위면 White, 흰 바탕이면 Green이에요. 반대로 쓰면 안 보여요.

어느 배리언트를 쓸지 헷갈리면 아래 **[조건 넣고 보기](#pick)** 에서 상태와 연속 일수를 넣어 보면 돼요.

---

## 조건 넣고 보기

사이트(streak.html)에는 상태·연속 일수를 고르면 어느 배리언트가 쓰이는지 보여 주는 칸이 있어요. 같은 내용을 표로 적으면 이래요.

### 상태별로 어느 배리언트를 쓰나

| 상태 | 식물 `Calendar Icon` | 얼굴 `Status Icon` | 위젯 `Widget/Streak` |
|---|---|---|---|
| 없음 (`none`) | `state=none` | `state=none` | `state=none` |
| 해야 함 (`todo`) | `state=todo` | `state=todo` | `state=todo` |
| 진행 중 · 아침 (`doing_morning`) | `state=doing_morning` | `state=doing-morning` | `state=doing` |
| 진행 중 · 낮 (`doing_afternoon`) | `state=doing_afternoon` | `state=doing-afternoon` | `state=doing` |
| 진행 중 · 저녁 (`doing_evening`) | `state=doing_evening` | `state=doing-evening` | `state=doing` |
| 진행 중 · 긴급 (`doing_emergency`) | `state=doing_emergency` | `state=doing-emergency` | `state=doing/emergency` |
| 완료 (`done`) | `state=done` | `state=done` | `state=done` |

- `none`·`todo`는 식물이 `day=default` 하나예요. 일수를 바꿔도 안 바뀌어요.
- 나머지 상태는 `day` 배리언트가 따로 있어요: day1 · day2 · day3 · day4 · day5 · day6 · day7 · day21 · day42 · day70 · day100 · day200 · day300 · day365 · day400 · day500 · day600 · day700 · day800 · day900 · day1000.
- 일수가 중간값이면 **그 이하에서 가장 큰 단계**로 봐요 (예: 50일 → `day42`). 앱 적용 기준은 확인 전이에요.
- `Status Icon`의 `doing-afternoon`·`doing-evening`은 세트 프레임 밖에 나가 있어요.

### 연속 일수별 불꽃·버튼 구간

| 부품 | 구간 |
|---|---|
| `Streak/Icon 20 Green` | `1-2days` · `3-4days` · `5-6days` · `7-69days` · `70-99days` |
| `Streak/Icon 40 Green` | `1-2days` · `3-4days` · `5-6days` · `7-69days` · `70-99days` |
| `Streak/Icon 40 White` | `0day` · `1-2days` · `3-4days` · `5-6days` · `7-69days` · `70-99days` |
| `Streak/Floating Button` | `1-2days` · `3-4days` · `5-6days` · `6-69days` · `70-99days` |
| `Streak/Floating Button Set` | `1-2days` · `3-4days` · `5-6days` · `6-69days` · `70-days` |

- **6일째가 어긋나요.** 불꽃은 `5-6days`, 플로팅 버튼은 `6-69days`라 모양이 서로 달라요.
- 100일 이상은 `Floating Button Set`(`70-days`)에만 있어요. 나머지는 `70-99days`에서 끝나요.
- 0일 그림은 `Icon 40 White`의 `0day`에만 있어요.


---

## 1. 식물 아이콘 그리기

기준 심볼은 `Streak/Calendar Icon` 의 `state=done, day=day1` (새싹)이에요. 나머지 단계도 같은 캔버스·같은 화분을 써요.

![day1 새싹 아이콘 컬러 가이드](img/streak-plant-guide.png)

### 캔버스

| 항목 | 값 |
|---|---|
| 캔버스 | 90 × 90, 배경 투명 |
| 일러스트 영역 | 72.8 × 63.3 |
| 여백 | 위 20 · 좌우 8~9 · 아래 6 |

**아래 여백이 좁은 건 일부러예요.** 바닥 그림자가 캔버스 아래쪽에 붙어 있어야 식물이 바닥에 선 것처럼 보여요.

### 구성과 컬러

| 파트 | 위치·크기 (x, y, w, h) | 컬러 |
|---|---|---|
| 왼쪽 잎 (앞) | 35.7, 20.3, 10.0 × 15.7 | `#00F4C1` |
| 줄기 | 44.6, 33.1, 길이 9.4 · 두께 1.93 | `#00F4C1` |
| 오른쪽 잎 (뒤) | 43.7, 20.7, 10.1 × 15.9 | `#86FFD1` |
| 화분 테두리(림) | 14.9, 38.2, 59.9 × 11.3 | `#EBD9C9` |
| 화분 몸통 | 20.1, 43.8, 49.5 × 37.3 | `#E3D0BE` |
| 바닥 그림자 | 8.4, 78.7, 72.8 × 5.0 | **아직 안 정함** |

- 잎은 **진한 민트가 앞, 연한 민트가 뒤**예요. 깊이감을 내려고 둘로 나눈 거라 같은 색으로 합치지 않아요.
- 화분은 **림이 몸통보다 밝고 넓은** 사다리꼴이에요.
- 선·외곽선 없고, 그라데이션 없는 **플랫 단색**이에요.

### 얼굴

얼굴은 `Streak/Status Icon` 인스턴스예요. 화분 몸통 위 `25.2, 49.4 / 39.8 × 30.6` 영역에 놓아요.

| 파트 | 크기 | 컬러 |
|---|---|---|
| 눈 | 원 3.8 × 3.8, 간격 약 13 | `#545454` |
| 볼터치 | 타원 4.7 × 3.4 (눈 바깥쪽 아래) | `#FEABBF` |
| 입 — done | 벌린 미소 7.4 × 5.8 | `#545454` |
| 입 안쪽 진한 부분 | 2.5 × 3.2 | `#3B3838` |
| 입 — doing | 일자선, 두께 2.29 | `#545454` |

**눈·입은 `#545454` 하나로 통일해요.** 라이브러리 원본에 `#555555`로 남아 있는 곳이 있는데 그건 고칠 거예요. 새로 그리거나 덮어쓸 때는 `#545454`를 써요.

### 하면 되는 것 · 하면 안 되는 것

| 하면 돼요 | 하면 안 돼요 |
|---|---|
| 라이브러리 인스턴스를 그대로 놓기 | 인스턴스를 떼어내서(Detach) 고치기 |
| 90×90 비율 그대로 키우고 줄이기 | 가로세로 비율 다르게 늘리기 |
| 단계가 없으면 가장 가까운 day 배리언트 쓰기 | 잎·화분을 직접 그려 넣어 새 단계 만들기 |
| 표정은 `Status Icon` 배리언트에서 고르기 | 눈·입을 직접 그리거나 위치 옮기기 |
| 색이 필요하면 위 표의 HEX 그대로 | 민트를 `Color/Button` 토큰으로 바꾸기 |

**일러스트 색은 토큰에 걸지 않아요.** 디자인 시스템 공통 규칙이에요 — 다시 쓰이지 않는 그래픽은 토큰에 연결하지 않아요. 화면에서 민트가 필요하면 토큰을 쓰지만, 식물의 잎 민트는 일러스트 색이라 HEX로 둬요.

---

## 2. 불꽃 아이콘

연속 일수에 따라 불꽃 모양이 달라져요. **같은 일수 구간이면 어느 크기를 써도 모양이 같아야 해요.**

| 부품 | 배리언트 |
|---|---|
| `Streak/Icon 20 Green` | 1-2 · 3-4 · 5-6 · 7-69 · 70-99 |
| `Streak/Icon 40 Green` | 1-2 · 3-4 · 5-6 · 7-69 · 70-99 |
| `Streak/Icon 40 White` | **0day** · 1-2 · 3-4 · 5-6 · 7-69 · 70-99 |

- `0day`는 White에만 있어요. 아직 시작 안 한 상태를 흰 바탕에서만 보여주기 때문이에요.
- `Streak/Ic Union`(17×17)은 불꽃 안의 조각이에요. 아이콘과 위젯이 같이 써요. **따로 꺼내 쓰지 않아요.**

| 하면 돼요 | 하면 안 돼요 |
|---|---|
| 바탕색 보고 Green·White 고르기 | 흰 아이콘에 색 덮어씌워 민트 만들기 |
| 20·40 중 자리에 맞는 크기 | 20을 40으로 키워 쓰기 (획 두께가 달라요) |

---

## 3. 플로팅 버튼

레슨 화면에 떠 있는 동그란 버튼이에요.

- `Streak/Floating Button` — 55×55 원, Corner Radius 1000, 면 `icon-highlight`. 안에 `Streak/Icon 40 White`가 들어가요.
- `Streak/Floating Button Set` — 위 버튼 + 아래 날짜 숫자. 55×65, 세로 오토레이아웃, 간격 **-10**(숫자가 원에 겹쳐 올라가요). 숫자 색은 `text-highlight`.

| 하면 돼요 | 하면 안 돼요 |
|---|---|
| 숫자까지 필요하면 Set을 쓰기 | 버튼과 숫자를 따로 놓고 직접 겹치기 |
| 원 면은 `icon-highlight` 그대로 | 간격 -10을 다른 값으로 바꾸기 |

---

## 4. 홈화면 위젯

`Widget/Streak` — 158×158, Corner Radius 22, 바탕은 그라데이션. 안에 `Streak/Calendar Icon`(90×90)이 그대로 들어가요. 그래서 **식물을 고치면 위젯도 같이 바뀌어요.**

상태는 `none` · `todo` · `doing` · `doing/emergency` · `done` 다섯이에요.

`Widget/State6` · `State7` · `State8`은 477×477 대형 위젯이에요. **어떤 조건에서 뜨는지 아직 확인 안 됐어요.** 쓰기 전에 물어봐 주세요.

---

## 5. 달력

- `Streak/Calendar Month` — 300×306, 안쪽 여백 13, 간격 14, Corner Radius 10, 면 `button-tertiary`, 테두리 `background-primary` 2
- `Streak/Calendar Date Cell` — 42×28. `default` · `today` · `active` · `start` · `freezemiddle` · `milestone`

연속 구간은 **시작 · 중간 · 끝** 모양이 따로 있어요. 가운데 날짜에 `start`를 쓰면 모서리가 끊겨 보여요.

| 하면 돼요 | 하면 안 돼요 |
|---|---|
| 구간 위치에 맞는 type 고르기 | 하나의 type으로 다 깔고 색만 바꾸기 |
| 글자색은 배리언트에 딸린 그대로 | 선택 안 된 날짜에 `text-on-color` 쓰기 |

---

## 6. 프리즈

`Streak/Freeze Item` — 56×56. `streakfreeze`(있음)와 `streakfreeze_empty`(빈 칸) 둘이에요.

빈 칸은 면 `icon-inactive` + 아이콘 `icon-unselected`예요. **빈 칸을 투명도로 만들지 않아요.** 배리언트를 바꿔요.

---

## 공통으로 지킬 것

1. **인스턴스를 떼어내지 않아요.** 스트릭 부품은 서로를 품고 있어서, 떼어내면 나중에 식물을 고쳐도 그 화면만 안 바뀌어요.
2. **배리언트로 해결돼요.** 상태가 안 맞으면 색을 덮어쓰지 말고 맞는 배리언트를 찾아요. 없으면 물어봐 주세요.
3. **일러스트 색은 HEX, UI 색은 토큰.** 식물·불꽃 안쪽은 HEX, 버튼 면·글자는 토큰이에요.
4. **식물을 고치면 위젯·달력이 같이 바뀌어요.** 고치기 전에 어디에 쓰이는지 먼저 봐요.

---

## 아직 안 정한 것 · 확인 필요

| 무엇 | 상태 |
|---|---|
| 바닥 그림자 컬러 | **미정.** 어두운 그레이에 투명도를 주는 방향으로 갈 예정이라 HEX 하나로 못 적어요. 정하기 전까지 그림자를 임의로 칠하지 않아요 |
| 눈 색 `#555555` | 라이브러리 원본에 남아 있어요. `#545454`로 통일하기로 했고, 아이콘 수정 때 같이 고쳐요 |
| 불꽃 일수 구간이 어긋나요 | 아이콘은 `7-69days`인데 플로팅 버튼은 `6-69days`예요. **6일째에 아이콘과 버튼 모양이 달라져요.** 어느 쪽이 맞는지 확인 필요 |
| 70일 이상 구간 이름 | `Floating Button Set`만 `70-days`고 나머지는 `70-99days`예요. 100일 이상을 어떻게 할지 확인 필요 |
| `Calendar Date Cell` 크기 | 설명은 44×28인데 실제는 42×28이에요 |
| `Floating Button Set` 날짜 글자 | 텍스트 스타일이 안 걸려 있어요 (Bold 12 직접 입력) |
| `Status Icon`과 `Calendar Icon`의 상태 이름 | 하나는 `doing-morning`(하이픈), 다른 하나는 `doing_morning`(밑줄)이에요. 상태 종류도 서로 달라요 |
| `Widget/State6·7·8` | 어떤 조건에서 뜨는지 확인 안 됨 |
| `Status Icon`의 배리언트 2개 | `doing-afternoon`·`doing-evening`이 **세트 프레임 밖에 나가 있어요.** 그래서 세트 그림에도 안 담기고 디스크립션에도 빠져 있어요 |
| 상태가 바뀌는 조건 | 아침·낮·저녁을 가르는 시각, `doing_emergency`가 되는 조건, `doing-morning-n`이 무엇인지 확인 안 됨 |
