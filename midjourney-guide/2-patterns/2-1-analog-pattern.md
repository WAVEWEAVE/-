# 2-1) 아날로그 패턴 — 정형화된 격자 반복 (Strict Seamless)

> **손으로 그린 아날로그 질감을, 타일처럼 수학적으로 정형화된 격자 위에서 완벽하게 똑같이 반복시키는 seamless 패턴** 프롬프트입니다. 수채화·리노컷 판화 느낌을 살리되 — **위치·크기·간격은 오차 없이 동일**하게 고정돼요. 포장지·원단·벽지·타일에 바로 쓸 수 있어요.

---

**📌 이 프롬프트는 어떤 용도인가요?**

손그림 질감은 살리되, **모티프의 위치·크기·방향이 한 치 오차 없이 격자 위에서 반복되는** 정형 타일을 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- 포장지·리본·쇼핑백 surface 디자인
- Spoonflower / Redbubble 원단·벽지 판매
- 타일·바닥재·세라믹 프린트
- 노트·다이어리·플래너 내지·커버
- 굿즈 배경 패턴 (에코백·파우치·폰케이스)

> ⚠️ **"규칙적"이 핵심이에요.** 스캐터·랜덤·자연스러운 배치는 이 가이드 범위가 **아닙니다**. 여기서는 모든 모티프가 **똑같은 크기·똑같은 간격·똑같은 방향**으로 반복돼야 해요. `--tile` 은 필수, 프롬프트에 "strict grid / mathematically precise / identical / uniform" 같은 규칙성 키워드를 반드시 넣어야 합니다.
>

---

**🚀 빠른 시작**

1. 아래 2가지 스타일 중 하나를 고르세요. (수채화 / 판화)
2. 원하는 예시를 고르세요. (스타일당 4개, 총 8개)
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern of {motif}, rendered in {analog_medium}, arranged in {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, on {background}, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 250 --tile
```

---

**⚙️ 옵션 파라미터**

| **파라미터** | **스타일 A (수채화 보태니컬)** | **스타일 B (리노컷 판화)** | **메모** |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` | 타일은 정사각형 필수 |
| `--s` | `200`~`350` | `100`~`200` | 높으면 질감↑ 규칙성↓ |
| `--tile` | **필수** | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본 유지) | `0` (기본 유지) | **절대 올리지 말 것** — 배치가 랜덤해짐 |
| `--niji 6` | 비추천 | 비추천 | 아날로그 질감이 날아감 |

---

**📌 변수 5개 — 모두 필수**

**1. `{motif}` — 무엇이 반복되나요?**

정형 반복에서는 **한 종류의 단일 모티프** 또는 **2종이 교차**하는 게 제일 규칙적으로 나와요.

- `a single small wildflower bloom` *(단일 꽃 한 송이)*
- `one sprig of lavender` *(라벤더 한 가지)*
- `a single lemon with one leaf` *(레몬 하나)*
- `one small mushroom` *(버섯 한 개)*
- `a single snowflake` *(눈송이 한 개)*
- `one small star and one crescent moon alternating` *(별·달 2종 교차)*
- `a single simple diamond shape` *(다이아몬드 단일)*
- `one coffee bean` *(커피콩 한 알)*

> 💡 **모티프가 많을수록 규칙성이 깨져요.** 정형 타일은 **1~2종**이 황금비율. 3종 이상 쓰고 싶으면 `alternating in strict ABAB order` 같은 교차 규칙을 명시하세요.
>

**2. `{analog_medium}` — 어떤 아날로그 매체인가요?**

매체는 **질감**만 담당하고 **배치 규칙성은 레이아웃이 담당**해요. 매체 설명에 "uneven / slight misalignment / hand-drawn imperfection" 같은 문구는 빼세요 — 위치까지 흐트러져요.

**스타일 A — 수채화 보태니컬:**

- `clean watercolor painting with soft pigment and gentle edges`
- `tidy watercolor wash with subtle granulation, crisp silhouette`
- `gouache painting with matte opaque finish and clean brushstrokes`

**스타일 B — 리노컷 판화:**

- `linocut block print with crisp carved lines and even ink coverage`
- `clean hand-stamped print with uniform ink, sharp edges`
- `woodblock print style with visible grain but clean impressions`
- `vintage rubber stamp print with consistent pressure`

**3. `{layout}` — 격자 배치 (정형만)**

**모두 수학적으로 정형화된 격자만 포함되어 있어요.**

- `a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif` *(정방형 격자 — 가장 규칙적)*
- `a half-drop repeat, every other column shifted down by exactly half the motif height, rows perfectly aligned` *(하프 드롭 — 클래식)*
- `a half-brick repeat, every other row shifted right by exactly half the motif width` *(하프 브릭 — 벽돌식)*
- `a diamond lattice, motifs placed on each intersection of a 45-degree grid` *(다이아몬드 격자)*
- `an ogee lattice, motifs centered inside each interlocking oval cell` *(오지 격자 — 고전)*
- `a hexagonal tessellation, motifs centered in each hexagon cell` *(벌집형)*

> 💡 **성공률 순서:** 정방형 그리드 > 하프드롭 > 하프브릭 > 다이아몬드 > 오지 > 헥사. 초보자는 반드시 **정방형 그리드**부터 시작하세요.
>

**4. `{color_palette}` — 색감은?**

**스타일 A** — 수채화 투명감 (2~3색):

- `soft sage green and dusty pink, muted watercolor tones`
- `warm terracotta and cream, earthy watercolor palette`
- `dusty lavender and mint, gentle pastel watercolor`
- `ochre yellow and olive green, vintage botanical palette`

**스타일 B** — 판화 2색 제한:

- `deep indigo ink on warm cream`
- `rust red and charcoal on ivory paper`
- `forest green and black ink, limited two-tone palette`
- `burnt sienna and off-white, vintage print palette`

**5. `{background}` — 배경 종이 질감은?**

- `warm cream paper with subtle fiber texture`
- `aged off-white watercolor paper with faint grain`
- `natural linen canvas texture background`
- `ivory paper with faint vintage yellowing`
- `kraft paper with soft brown warmth`

---

**✏️ 적용 예시 8개**

---

**예시 1 — 🌸 수채화 들꽃 정방형 그리드 — 스타일 A**

```
Seamless repeating pattern of a single small wildflower bloom, rendered in clean watercolor painting with soft pigment and gentle edges, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage green and dusty pink, muted watercolor tones, on warm cream paper with subtle fiber texture, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 250 --tile
```

---

**예시 2 — 🍋 수채화 레몬 하프드롭 — 스타일 A**

```
Seamless repeating pattern of a single lemon with one leaf, rendered in tidy watercolor wash with subtle granulation, crisp silhouette, arranged in a half-drop repeat, every other column shifted down by exactly half the motif height, rows perfectly aligned, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, ochre yellow and olive green, vintage botanical palette, on aged off-white watercolor paper with faint grain, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 280 --tile
```

---

**예시 3 — 💜 수채화 라벤더 다이아몬드 격자 — 스타일 A**

```
Seamless repeating pattern of one sprig of lavender, rendered in gouache painting with matte opaque finish and clean brushstrokes, arranged in a diamond lattice, motifs placed on each intersection of a 45-degree grid, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty lavender and mint, gentle pastel watercolor, on warm cream paper with subtle fiber texture, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 250 --tile
```

---

**예시 4 — 🍄 수채화 버섯 하프브릭 — 스타일 A**

```
Seamless repeating pattern of one small mushroom, rendered in clean watercolor painting with soft pigment and gentle edges, arranged in a half-brick repeat, every other row shifted right by exactly half the motif width, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm terracotta and cream, earthy watercolor palette, on ivory paper with faint vintage yellowing, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 250 --tile
```

---

**예시 5 — ⭐ 리노컷 별·달 교차 그리드 — 스타일 B**

```
Seamless repeating pattern of one small star and one crescent moon alternating in strict ABAB order, rendered in linocut block print with crisp carved lines and even ink coverage, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, deep indigo ink on warm cream, on kraft paper with soft brown warmth, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 150 --tile
```

---

**예시 6 — ❄️ 판화 눈송이 헥사곤 — 스타일 B**

```
Seamless repeating pattern of a single snowflake, rendered in clean hand-stamped print with uniform ink, sharp edges, arranged in a hexagonal tessellation, motifs centered in each hexagon cell, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, forest green and black ink, limited two-tone palette, on natural linen canvas texture background, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 150 --tile
```

---

**예시 7 — ☕ 스탬프 커피콩 정방형 그리드 — 스타일 B**

```
Seamless repeating pattern of one coffee bean, rendered in vintage rubber stamp print with consistent pressure, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing between every motif, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, burnt sienna and off-white, vintage print palette, on kraft paper with soft brown warmth, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 8 — ♦️ 판화 다이아몬드 오지 격자 — 스타일 B**

```
Seamless repeating pattern of a single simple diamond shape, rendered in woodblock print style with visible grain but clean impressions, arranged in an ogee lattice, motifs centered inside each interlocking oval cell, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, rust red and charcoal on ivory paper, on aged off-white watercolor paper with faint grain, flat top-down view, tileable surface design, no text, no variation in motif placement. --ar 1:1 --s 150 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{layout}` 변경 | 같은 꽃으로 그리드/하프드롭/다이아 시리즈 |
| `{layout}` 고정 + `{motif}` 변경 | 같은 격자 구조의 모티프 컬렉션 |
| `{analog_medium}` 스타일 A → B | 수채 → 판화 전환, 같은 격자 유지 |
| `--s` 값 낮춤 | 모티프 단순화, 규칙성 선명 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos 5` 이상 | **규칙성 붕괴** — 이 가이드 취지 이탈 |

---

**⚠️ 핵심 팁 5가지**

1. **"규칙성 키워드"를 반드시 박으세요.** `strict grid`, `mathematically precise`, `identical in size shape and orientation`, `no variation in motif placement` — 이 문구들이 위치·크기 일관성을 붙잡아줘요.
2. **모티프는 1~2종만.** 3종 이상이면 격자가 무너져요. 꼭 여러 종을 쓰려면 `alternating in strict ABAB order` 로 교차 규칙을 명시.
3. **매체 설명에 "uneven / slight misalignment" 금지.** 질감 설명에 이런 단어가 들어가면 위치까지 흐트러져요.
4. **`--chaos` 는 0 고정.** 기본값을 건드리지 마세요. 올리는 순간 랜덤 배치로 바뀝니다.
5. **반드시 2x2 타일 테스트.** 출력 이미지를 포토샵 「패턴으로 정의」 → 큰 캔버스에 적용해서 이음매·크기 차이·위치 어긋남이 있는지 확인하세요. 한 번에 성공하기 어려워요 — 4~8회 재생성 각오.

---

**✅ 시리즈 만드는 추천 흐름**

1. 한 가지 **매체(수채화 or 판화)** 와 **격자 구조(그리드/하프드롭 등)** 를 정하세요.
2. 같은 매체·같은 격자로 **모티프만 바꿔서 4~6종** 만드세요.
3. 마음에 드는 컷에서 `--seed [번호]` 를 고정해 질감·격자 일관성을 유지하세요.
4. 컬러는 시리즈 내에서 2~3색 팔레트 하나로 통일하세요.

> 💡 **상시판매형 추천 조합.** ① 수채 보태니컬 정방형 4계절 세트 — 포장지·노트 커버 스테디셀러. ② 리노컷 2색 하프드롭 컬렉션 — 크래프트 패키지·벽지. ③ 단일 기하 모티프 (다이아·별·눈송이) 다이아몬드 격자 — 타일·원단 surface.
>
