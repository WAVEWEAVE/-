# 2-1) 아날로그 패턴 — 기하 도형 × 정석 아날로그 인쇄 (Strict Seamless)

> **원·삼각형·사각형·십자 같은 기하학적 도형을, 실크스크린·리소그래프·리노컷·레터프레스 같은 정석 아날로그 인쇄 매체로 찍어낸 seamless 패턴** 프롬프트입니다. 모티프는 기하 도형, 질감은 손맛 있는 인쇄 잉크, 배치는 타일처럼 수학적으로 정형화 — 바우하우스·미드센추리·북유럽 크래프트 감성에 강해요.

---

**📌 이 프롬프트는 어떤 용도인가요?**

기하 도형을 **아날로그 인쇄 잉크 질감**으로 표현하되, **위치·크기·방향은 한 치 오차 없이 격자로 반복되는** 정형 타일을 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- 포장지·쇼핑백·리본 surface 디자인
- Spoonflower / Redbubble 원단·벽지
- 타일·바닥재·세라믹 프린트
- 노트·다이어리·플래너 커버
- 브랜드 패키지 배경 (미드센추리·북유럽 감성)

> ⚠️ **회화 매체 금지.** 수채화·파스텔·과슈 같은 그림 매체는 이 가이드 범위가 **아닙니다**. 여기서는 **실크스크린·리소그래프·리노컷·레터프레스·펜 드로잉** 같은 정석 인쇄/드로잉 매체만 사용합니다. 기하 도형 × 인쇄 잉크 질감 × 엄격한 격자, 이 세 가지 조합이 핵심이에요.
>

---

**🚀 빠른 시작**

1. 아래 2가지 스타일 중 하나를 고르세요. (실크스크린 / 리노컷 판화)
2. 원하는 예시를 고르세요. (스타일당 4개, 총 8개)
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern of {motif}, printed in {analog_medium}, arranged in {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, on {background}, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**⚙️ 옵션 파라미터**

| **파라미터** | **스타일 A (실크스크린/리소)** | **스타일 B (리노컷/레터프레스)** | **메모** |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` | 타일은 정사각형 필수 |
| `--s` | `150`~`250` | `100`~`200` | 너무 올리면 도형이 복잡해짐 |
| `--tile` | **필수** | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본) | `0` (기본) | **절대 올리지 말 것** |
| `--niji 6` | 비추천 | 비추천 | 인쇄 질감이 날아감 |

---

**📌 변수 5개 — 모두 필수**

**1. `{motif}` — 어떤 기하 도형을 반복하나요?**

단일 도형 하나, 또는 2종 교차가 규칙성이 가장 잘 나와요.

- `a single solid filled circle dot`
- `a single equilateral triangle`
- `a single solid square`
- `a single diamond (rotated square)`
- `a single plus sign cross`
- `a single X mark`
- `a single solid semicircle arc`
- `a single short horizontal bar stripe`
- `a single six-pointed asterisk star`
- `a solid circle and a triangle alternating in strict ABAB order` *(2종 교차)*
- `a filled square and a plus sign alternating in strict ABAB order` *(2종 교차)*

> 💡 **도형은 단순할수록 좋아요.** 복잡한 별·톱니바퀴 같은 건 반복 시 시각적 피로가 심해요. 원·삼각형·사각형·십자가 기본값.
>

**2. `{analog_medium}` — 어떤 정석 아날로그 매체?**

**스타일 A — 실크스크린 / 리소그래프 계열 (평면 잉크):**

- `silkscreen print with flat matte ink and subtle ink texture`
- `risograph print with slightly uneven ink coverage and visible grain`
- `offset print with soft halftone dot texture`
- `screen printed poster style with solid flat color and crisp edges`

**스타일 B — 리노컷 / 레터프레스 계열 (눌림·판화):**

- `linocut block print with crisp carved edges and visible ink texture`
- `letterpress print with slight ink impression into paper`
- `hand-stamped rubber block print with even ink`
- `woodblock print style with subtle wood grain in the ink`

> 💡 **매체 선택 기준:** A는 깔끔하고 모던한 그래픽 감성 (미드센추리 포스터·북유럽 브랜드). B는 거칠고 공예적인 감성 (인디 스튜디오·크래프트 패키지).
>

**3. `{layout}` — 격자 배치 (정형만)**

**6가지 모두 수학적 정형 격자예요.**

- `a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif` *(정방형 그리드 — 기본)*
- `a half-drop repeat, every other column shifted down by exactly half the motif height, rows perfectly aligned` *(하프 드롭)*
- `a half-brick repeat, every other row shifted right by exactly half the motif width` *(하프 브릭)*
- `a diamond lattice, motifs placed on each intersection of a 45-degree grid` *(다이아몬드 격자)*
- `an ogee lattice, motifs centered inside each interlocking oval cell` *(오지 격자)*
- `a hexagonal tessellation, motifs centered in each hexagon cell` *(벌집형)*

> 💡 **성공률 순서:** 정방형 > 하프드롭 > 하프브릭 > 다이아몬드 > 오지 > 헥사. 처음엔 반드시 **정방형 그리드**로 시작.
>

**4. `{color_palette}` — 색감은? (2~3색 제한)**

정석 인쇄물은 색 수를 제한해야 인쇄 느낌이 살아나요.

- `deep navy ink on warm cream paper`
- `rust red and charcoal on ivory`
- `mustard yellow and black on off-white`
- `forest green and cream, two-tone print`
- `burnt orange and deep brown, vintage print palette`
- `cobalt blue and red on ivory, classic risograph duotone`
- `single black ink on natural kraft paper`
- `olive green and terracotta on cream`

**5. `{background}` — 배경 종이 질감은?**

- `warm cream paper with subtle fiber texture`
- `aged off-white paper with faint grain`
- `ivory cardstock with slight tooth`
- `natural kraft paper with soft brown warmth`
- `textured printmaking paper with visible fiber`

---

**✏️ 적용 예시 8개**

---

**예시 1 — ⚫ 실크스크린 원 정방형 그리드 — 스타일 A**

```
Seamless repeating pattern of a single solid filled circle dot, printed in silkscreen print with flat matte ink and subtle ink texture, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, deep navy ink on warm cream paper, on warm cream paper with subtle fiber texture, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 2 — 🔺 리소그래프 삼각형 하프드롭 — 스타일 A**

```
Seamless repeating pattern of a single equilateral triangle, printed in risograph print with slightly uneven ink coverage and visible grain, arranged in a half-drop repeat, every other column shifted down by exactly half the motif height, rows perfectly aligned, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, mustard yellow and black on off-white, on ivory cardstock with slight tooth, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**예시 3 — ➕ 실크스크린 십자 하프브릭 — 스타일 A**

```
Seamless repeating pattern of a single plus sign cross, printed in screen printed poster style with solid flat color and crisp edges, arranged in a half-brick repeat, every other row shifted right by exactly half the motif width, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, rust red and charcoal on ivory, on aged off-white paper with faint grain, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 4 — ⬛➕ 리소 사각·십자 교차 그리드 — 스타일 A**

```
Seamless repeating pattern of a filled square and a plus sign alternating in strict ABAB order, printed in risograph print with slightly uneven ink coverage and visible grain, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, cobalt blue and red on ivory, classic risograph duotone, on textured printmaking paper with visible fiber, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**예시 5 — ♦️ 리노컷 다이아몬드 격자 — 스타일 B**

```
Seamless repeating pattern of a single diamond (rotated square), printed in linocut block print with crisp carved edges and visible ink texture, arranged in a diamond lattice, motifs placed on each intersection of a 45-degree grid, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, forest green and cream, two-tone print, on natural kraft paper with soft brown warmth, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 150 --tile
```

---

**예시 6 — ✖️ 레터프레스 X 정방형 그리드 — 스타일 B**

```
Seamless repeating pattern of a single X mark, printed in letterpress print with slight ink impression into paper, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, single black ink on natural kraft paper, on natural kraft paper with soft brown warmth, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 130 --tile
```

---

**예시 7 — ◗ 리노컷 반원 헥사곤 — 스타일 B**

```
Seamless repeating pattern of a single solid semicircle arc, printed in hand-stamped rubber block print with even ink, arranged in a hexagonal tessellation, motifs centered in each hexagon cell, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, burnt orange and deep brown, vintage print palette, on textured printmaking paper with visible fiber, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 160 --tile
```

---

**예시 8 — ⚫🔺 우드블록 원·삼각 교차 하프드롭 — 스타일 B**

```
Seamless repeating pattern of a solid circle and a triangle alternating in strict ABAB order, printed in woodblock print style with subtle wood grain in the ink, arranged in a half-drop repeat, every other column shifted down by exactly half the motif height, rows perfectly aligned, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, olive green and terracotta on cream, on ivory cardstock with slight tooth, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 170 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{layout}` 변경 | 같은 도형으로 격자 구조 시리즈 |
| `{layout}` 고정 + `{motif}` 변경 | 같은 격자의 도형 컬렉션 |
| `{analog_medium}` A → B | 모던 포스터 → 공예 크래프트 전환 |
| `{color_palette}` 를 듀오톤으로 | 리소그래프·실크스크린 감성 극대화 |
| `--s` 값 낮춤 | 도형이 더 단순·선명 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

**⚠️ 핵심 팁 5가지**

1. **"정석 아날로그 인쇄" 매체만 쓰세요.** 실크스크린·리소·리노컷·레터프레스·우드블록·스탬프 — 이 6종이 전부예요. 수채화·파스텔·과슈 같은 회화 매체는 이 가이드에 안 맞아요.
2. **규칙성 키워드는 무조건 박으세요.** `strict grid`, `mathematically precise`, `identical in size shape and orientation`, `no variation in motif placement` — 이거 빠지면 배치가 흐트러져요.
3. **도형 1종 또는 2종 교차만.** 3종 이상이면 격자가 무너져요. 2종은 반드시 `alternating in strict ABAB order` 로 교차 규칙 명시.
4. **색은 2~3색 듀오톤/트리톤.** 정석 인쇄는 색 수 제한이 핵심. 4색 이상이면 인쇄 느낌이 날아가요.
5. **반드시 2x2 타일 테스트.** 포토샵 「패턴으로 정의」 로 큰 캔버스에 깔아보고 이음매·크기·위치를 확인. 한 번에 성공 어려움 — 4~8회 재생성 각오.

---

**✅ 시리즈 만드는 추천 흐름**

1. **도형 1종** + **매체 1종** + **격자 1종** 을 정하세요.
2. 같은 조합으로 **컬러만 3~4가지 변주** (딥 네이비 / 머스터드 / 러스트 / 포레스트).
3. 마음에 드는 컷에서 `--seed [번호]` 고정해 인쇄 질감 일관성 유지.
4. 한 컬렉션 = 한 도형 (예: 원 시리즈 4색, 삼각 시리즈 4색).

> 💡 **상시판매형 추천 조합.** ① 리소그래프 듀오톤 기하 시리즈 (원·삼각·사각·십자 4종) — 미드센추리 포스터·패키지. ② 리노컷 단색 크래프트 시리즈 — 인디 브랜드·공예 패키지. ③ 실크스크린 2색 교차 패턴 (ABAB) — 원단·벽지·타일.
>
