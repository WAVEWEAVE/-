# 2-1) 아날로그 패턴 — 규칙적 반복 (Seamless)

> **손으로 그린 듯한 아날로그 감성을 규칙적으로 반복시키는 seamless 패턴** 프롬프트입니다. 수채화 번짐·색연필 결·스탬프 자국·리노컷 판화 느낌을 살려, 포장지·원단·벽지·노트 커버에 강해요. `--tile` 파라미터가 핵심이에요 — 이게 없으면 그냥 일러스트가 돼요.

---

**📌 이 프롬프트는 어떤 용도인가요?**

손그림 질감이 살아 있는 모티프를 **상하좌우로 끊김 없이 이어지는 타일**로 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- 포장지·리본·쇼핑백 surface 디자인
- Spoonflower / Redbubble 원단·벽지 판매
- 노트·다이어리·플래너 내지·커버
- 굿즈 배경 패턴 (에코백·파우치·폰케이스)
- 브랜드 패키지 배경 패턴

> ⚠️ **`--tile` 파라미터가 없으면 seamless 반복이 안 돼요.** 이어붙였을 때 경계선이 티 나면 실패예요. 포토샵 「패턴으로 정의」 나 [pattern.monster](http://pattern.monster) 에서 반드시 연결 테스트를 하세요.
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
Seamless repeating pattern of {motif}, {analog_medium}, {layout}, {color_palette}, on {background}, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 250 --tile
```

---

**⚙️ 옵션 파라미터**

| **파라미터** | **스타일 A (수채화 보태니컬)** | **스타일 B (리노컷 판화)** | **메모** |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` | 타일은 정사각형 필수 |
| `--s` | `250`~`400` | `150`~`250` | A는 번짐 풍부, B는 선 강조 |
| `--tile` | **필수** | **필수** | 빼면 seamless 안 됨 |
| `--niji 6` | 비추천 | 비추천 | 아날로그 질감이 날아감 |

---

**📌 변수 5개 — 모두 필수**

**1. `{motif}` — 무엇이 반복되나요?**

아날로그 패턴은 모티프가 단순할수록 반복했을 때 예뻐요.

- `small wildflowers and tiny leaves`
- `vintage botanical herbs and dried stems`
- `tiny citrus fruits — lemons, oranges, and leaves`
- `scattered mushrooms and forest ferns`
- `simple geometric diamonds and dots`
- `hand-drawn stars and crescent moons`
- `tiny birds, twigs, and berries`
- `coffee cups, beans, and croissants`

> 💡 **모티프는 2~3종류 섞는 게 제일 예뻐요.** 꽃 하나만 반복하면 단조롭고, 5가지 이상 섞으면 어지러워요.
>

**2. `{analog_medium}` — 어떤 아날로그 매체인가요?**

**스타일 A — 수채화 보태니컬:**

- `loose watercolor painting with soft bleeding edges and visible pigment pooling`
- `delicate watercolor wash with gentle granulation texture`
- `gouache painting with matte opaque finish and visible brushstrokes`

**스타일 B — 리노컷 판화:**

- `linocut block print with rough carved lines and ink texture`
- `hand-stamped potato print with uneven ink distribution`
- `woodblock print style with visible grain and slight misalignment`
- `vintage rubber stamp print with faded ink edges`

**3. `{layout}` — 배치는 어떻게?**

반복 배치 방식이 패턴 전체 분위기를 결정해요.

- `evenly spaced grid layout, each motif repeated at regular intervals` *(정방형 그리드 — 가장 기본)*
- `half-drop repeat, motifs staggered in alternating rows` *(하프 드롭 — 클래식)*
- `diamond grid layout with motifs on each lattice point` *(다이아몬드 격자)*
- `scattered random-looking arrangement but seamlessly tileable` *(스캐터 — 자연스러움)*
- `densely packed mosaic with motifs touching edges` *(밀집 배치)*
- `loose airy arrangement with generous negative space between motifs` *(여백 많음)*

> 💡 **seamless 성공률 순서:** 그리드 > 하프드롭 > 다이아몬드 > 스캐터. 초보자는 그리드로 시작하세요.
>

**4. `{color_palette}` — 색감은?**

**스타일 A** — 수채화 투명감:

- `soft sage green and dusty pink, muted watercolor tones`
- `warm terracotta and cream, earthy watercolor palette`
- `dusty lavender and mint, gentle pastel watercolor`
- `ochre yellow and olive green, vintage botanical palette`

**스타일 B** — 판화 2~3색 제한:

- `deep indigo ink on warm cream`
- `rust red and charcoal on ivory paper`
- `forest green and black ink, limited two-tone palette`
- `burnt sienna and off-white, vintage print palette`

**5. `{background}` — 배경 종이 질감은?**

아날로그 감성의 핵심은 "종이 위에 그린 듯한" 배경이에요.

- `warm cream paper with subtle fiber texture`
- `aged off-white watercolor paper with slight grain`
- `natural linen canvas texture background`
- `ivory paper with faint vintage yellowing`
- `kraft paper with soft brown warmth`

---

**✏️ 적용 예시 8개**

---

**예시 1 — 🌿 수채화 들꽃 그리드 — 스타일 A**

```
Seamless repeating pattern of small wildflowers and tiny leaves, loose watercolor painting with soft bleeding edges and visible pigment pooling, evenly spaced grid layout, each motif repeated at regular intervals, soft sage green and dusty pink, muted watercolor tones, on warm cream paper with subtle fiber texture, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 300 --tile
```

---

**예시 2 — 🍋 수채화 시트러스 하프드롭 — 스타일 A**

```
Seamless repeating pattern of tiny citrus fruits — lemons, oranges, and leaves, delicate watercolor wash with gentle granulation texture, half-drop repeat, motifs staggered in alternating rows, ochre yellow and olive green, vintage botanical palette, on aged off-white watercolor paper with slight grain, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 350 --tile
```

---

**예시 3 — 🍄 수채화 버섯 스캐터 — 스타일 A**

```
Seamless repeating pattern of scattered mushrooms and forest ferns, gouache painting with matte opaque finish and visible brushstrokes, scattered random-looking arrangement but seamlessly tileable, warm terracotta and cream, earthy watercolor palette, on ivory paper with faint vintage yellowing, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 300 --tile
```

---

**예시 4 — 🌱 수채화 허브 여백형 — 스타일 A**

```
Seamless repeating pattern of vintage botanical herbs and dried stems, loose watercolor painting with soft bleeding edges and visible pigment pooling, loose airy arrangement with generous negative space between motifs, dusty lavender and mint, gentle pastel watercolor, on warm cream paper with subtle fiber texture, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 400 --tile
```

---

**예시 5 — ⭐ 리노컷 별·달 다이아몬드 — 스타일 B**

```
Seamless repeating pattern of hand-drawn stars and crescent moons, linocut block print with rough carved lines and ink texture, diamond grid layout with motifs on each lattice point, deep indigo ink on warm cream, on kraft paper with soft brown warmth, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 200 --tile
```

---

**예시 6 — 🐦 판화 새·잔가지 그리드 — 스타일 B**

```
Seamless repeating pattern of tiny birds, twigs, and berries, woodblock print style with visible grain and slight misalignment, evenly spaced grid layout, each motif repeated at regular intervals, rust red and charcoal on ivory paper, on natural linen canvas texture background, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 180 --tile
```

---

**예시 7 — ☕ 스탬프 커피 밀집 — 스타일 B**

```
Seamless repeating pattern of coffee cups, beans, and croissants, hand-stamped potato print with uneven ink distribution, densely packed mosaic with motifs touching edges, burnt sienna and off-white, vintage print palette, on kraft paper with soft brown warmth, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 220 --tile
```

---

**예시 8 — ♦️ 판화 기하 하프드롭 — 스타일 B**

```
Seamless repeating pattern of simple geometric diamonds and dots, vintage rubber stamp print with faded ink edges, half-drop repeat, motifs staggered in alternating rows, forest green and black ink, limited two-tone palette, on aged off-white watercolor paper with slight grain, tileable surface design, evenly spaced repeat, no text. --ar 1:1 --s 200 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{analog_medium}` 변경 | 같은 모티프, 매체별 시리즈 (수채/판화/색연필) |
| `{analog_medium}` 고정 + `{motif}` 변경 | 같은 질감의 보태니컬 컬렉션 |
| `{layout}` 를 그리드 → 스캐터 | 정갈함 → 자연스러움 |
| `--s 200 → 400` | 아날로그 번짐·질감이 더 극적으로 |
| `--tile` 제거 | seamless 실패 (일러스트 한 장이 됨) |
| `{background}` 를 `kraft paper` 로 | 빈티지·공예 느낌 극대화 |

---

**⚠️ 핵심 팁 5가지**

1. **`--tile` 은 절대 빼지 마세요.** 이게 없으면 상하좌우 이음매가 어긋나서 패턴으로 못 써요.
2. **모티프는 작고 단순할수록 반복이 예뻐요.** 복잡한 꽃 한 송이보다 작은 꽃 여러 개가 훨씬 잘 이어져요.
3. **색은 2~4가지로 제한하세요.** 색이 많으면 반복 시 산만하고 인쇄 비용도 올라가요.
4. **수채화는 `--s 300+`, 판화는 `--s 200-`.** A는 번짐이 살아야 하고 B는 선이 깔끔해야 해요.
5. **출력 후 반드시 연결 테스트하세요.** 포토샵에서 2x2 로 이어붙여보거나 [pattern.monster](http://pattern.monster) 에 올려 경계선 확인이 필수예요.

---

**✅ 시리즈 만드는 추천 흐름**

1. 한 가지 **매체(수채화 or 판화)** 를 정하세요.
2. 같은 매체·같은 컬러 팔레트로 **모티프만 바꿔서 4~6종** 만드세요.
3. 마음에 드는 컷에서 `--seed [번호]` 를 고정해 질감 일관성을 유지하세요.
4. 계절별 컬렉션 (봄 들꽃 / 여름 시트러스 / 가을 버섯 / 겨울 별·달) 으로 묶어 판매하세요.

> 💡 **상시판매형 추천 조합.** ① 수채 보태니컬 4계절 세트 — 포장지·노트 커버 스테디셀러. ② 리노컷 빈티지 2~3색 시리즈 — 크래프트 패키지·브랜드 배경. ③ 스탬프 키친 모티프 (커피·빵·과일) — 카페·베이커리 굿즈.
>
