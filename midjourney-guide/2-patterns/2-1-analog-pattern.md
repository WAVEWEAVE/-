# 2-1) 아날로그 패턴 — 클래식 기하·곡선 × 스티플 그레인 (Strict Seamless)

> **얇은 모노라인 또는 점묘·할프톤 그레인 질감으로 그려낸 고전 기하·곡선 패턴** 프롬프트입니다. 아치·물결·육각 스트라이프·쿼트리폴 같은 클래식 모티프를 스티플 점묘 텍스처나 모노라인으로 표현해 — 럭셔리 패키지·벽지·스테이셔너리·브랜드 배경에 강해요. 아날로그 감성의 핵심은 **스티플(dotwork) 할프톤 그레인** 입니다.

---

**📌 이 프롬프트는 어떤 용도인가요?**

**고전 기하·곡선 모티프**를 **모노라인 또는 스티플 그레인 텍스처**로 표현하고, **엄격한 격자 반복**으로 타일링하는 프롬프트예요.

이런 데 쓸 수 있어요:

- 럭셔리 브랜드 패키지·박스·쇼핑백
- 호텔·리빙 벽지·쿠션·러그
- 명함·청첩장·레터헤드 배경
- Spoonflower / Redbubble 원단·벽지
- 목업 배경 / 웹사이트 히어로

> ⚠️ **"아날로그 = 스티플 그레인" 이 핵심.** 여기서 아날로그는 수채화·판화 잉크가 아니라, **점묘(dotwork)·할프톤·스프레이 그레인 텍스처** 를 뜻해요. 옛날 판화·리소그래프의 거친 점묘 질감 느낌. 모티프는 고전 기하·곡선, 배치는 엄격한 격자 반복이에요.
>

---

**🚀 빠른 시작**

1. 아래 2가지 스타일 중 하나를 고르세요. (모노라인 / 스티플 그레인)
2. 원하는 예시를 고르세요. (스타일당 4개, 총 8개)
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern of {motif}, {rendering_style}, arranged in {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, on {background}, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**⚙️ 옵션 파라미터**

| **파라미터** | **스타일 A (모노라인)** | **스타일 B (스티플 그레인)** | **메모** |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` | 타일은 정사각형 필수 |
| `--s` | `100`~`200` | `200`~`350` | A 낮을수록 선 깔끔 / B 높을수록 그레인 풍부 |
| `--tile` | **필수** | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본) | `0` (기본) | **절대 올리지 말 것** |
| `--niji 6` | 비추천 | 비추천 | 고전 톤이 일러스트화됨 |

---

**📌 변수 5개 — 모두 필수**

**1. `{motif}` — 어떤 고전 모티프?**

**스타일 A — 모노라인 (얇은 선):**

- `a single set of concentric nested arches forming a capsule shape` *(겹친 아치 캡슐)*
- `a single seigaiha wave scale with three concentric arcs` *(세이가이하 물결)*
- `a single hexagon filled with parallel vertical stripes` *(스트라이프 육각)*
- `a single quatrefoil four-petal rosette outline` *(쿼트리폴 네잎꽃)*
- `a tiny dot and a small X mark alternating in strict ABAB order` *(점·X 교차)*
- `a single small diamond outline with a center dot` *(다이아 + 점)*

**스타일 B — 스티플 그레인 (점묘 텍스처):**

- `a single vertical capsule column shape filled with fine stipple dot texture` *(스티플 캡슐 컬럼)*
- `a single wavy diamond shape filled with pointillism stipple gradient` *(스티플 웨이브 다이아)*
- `a single large circle filled with halftone dot gradient` *(할프톤 원)*
- `a single interlocking oval shape filled with dense stipple texture` *(스티플 오벌)*
- `a single scalloped half-circle filled with spray grain texture` *(그레인 반원)*
- `a single rounded square tile filled with gradient dotwork texture` *(도트워크 타일)*

> 💡 **스타일 B 모티프는 "속을 스티플로 채운 큰 도형" 이에요.** 아웃라인이 아니라 면 전체가 점묘 그라데이션으로 채워져 있는 게 포인트.
>

**2. `{rendering_style}` — 렌더링 방식**

**스타일 A — 모노라인:**

- `rendered in ultra-thin crisp hairline strokes, single line weight throughout`
- `rendered in fine parallel line strokes with equal spacing between lines`
- `rendered in elegant thin metallic gold lines with crisp vector edges`

**스타일 B — 스티플 그레인:**

- `rendered with dense pointillism stipple dot texture fill, grainy dotwork shading, vintage engraving feel`
- `rendered with halftone dot gradient fill, fading from dense to sparse dots, classic print grain`
- `rendered with fine spray grain texture fill, soft airbrushed dotwork, risograph print feel`
- `rendered with crisp stipple dotwork fill, uniform dot density, vintage etching style`

> 💡 **스타일 B의 "stipple / dotwork / halftone / grain" 키워드가 아날로그 감성의 핵심이에요.** 이거 빼면 그냥 플랫 벡터가 돼요.
>

**3. `{layout}` — 격자 배치 (정형만)**

- `a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing` *(정방형 그리드)*
- `a diagonal diamond lattice, motifs placed at every 45-degree grid intersection` *(대각선 다이아)*
- `a half-drop repeat, every other column shifted down by exactly half the motif height` *(하프 드롭)*
- `a half-brick repeat, every other row shifted right by exactly half the motif width` *(하프 브릭)*
- `a hexagonal tessellation, motifs tessellating edge-to-edge in a honeycomb grid` *(벌집 테셀레이션)*
- `a wave row repeat, motifs arranged in perfectly parallel horizontal wave rows, each row identical` *(물결 평행 반복 — 세이가이하 전용)*
- `a scalloped row repeat, motifs stacked in offset rows with each scallop tangent to the next` *(스캘럽 오프셋 — 캡슐·아치 전용)*

> 💡 **모티프별 추천 레이아웃:** 세이가이하 → 물결 평행 / 아치·캡슐 → 스캘럽 오프셋 or 하프드롭 / 육각 → 벌집 테셀레이션 / 쿼트리폴 → 다이아 격자.
>

**4. `{color_palette}` — 2~3색 듀오톤/트리톤**

**스타일 A — 클래식 라인:**

- `thin cream lines on deep navy background, classic luxury`
- `metallic gold lines on charcoal grey, art deco palette`
- `teal line strokes on warm cream, vintage oriental palette`
- `soft dusty blue on warm cream, muted vintage wallpaper palette`

**스타일 B — 스티플 그레인:**

- `warm cream stippled motifs on deep navy, vintage print palette`
- `cream dotwork on dark charcoal, engraving palette`
- `ivory stipple on midnight navy, classic etching palette`
- `tan stippled texture on black background, vintage poster palette`

**5. `{background}` — 배경 톤**

- `deep navy background`
- `charcoal grey background`
- `midnight blue background`
- `warm cream paper`
- `ivory background`
- `soft muted grey background`

---

**✏️ 적용 예시 8개**

---

**예시 1 — 🌊 모노라인 세이가이하 물결 — 스타일 A**

```
Seamless repeating pattern of a single seigaiha wave scale with three concentric arcs, rendered in ultra-thin crisp hairline strokes, single line weight throughout, arranged in a wave row repeat, motifs arranged in perfectly parallel horizontal wave rows, each row identical, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, teal line strokes on warm cream, vintage oriental palette, on warm cream paper, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 150 --tile
```

---

**예시 2 — 🌀 모노라인 겹친 아치 캡슐 — 스타일 A**

```
Seamless repeating pattern of a single set of concentric nested arches forming a capsule shape, rendered in elegant thin metallic gold lines with crisp vector edges, arranged in a scalloped row repeat, motifs stacked in offset rows with each scallop tangent to the next, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, metallic gold lines on charcoal grey, art deco palette, on charcoal grey background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 3 — ⬡ 모노라인 스트라이프 육각 벌집 — 스타일 A**

```
Seamless repeating pattern of a single hexagon filled with parallel vertical stripes, rendered in fine parallel line strokes with equal spacing between lines, arranged in a hexagonal tessellation, motifs tessellating edge-to-edge in a honeycomb grid, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, metallic gold lines on charcoal grey, art deco palette, on charcoal grey background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 4 — ✦ 모노라인 쿼트리폴 다이아 격자 — 스타일 A**

```
Seamless repeating pattern of a single quatrefoil four-petal rosette outline, rendered in ultra-thin crisp hairline strokes, single line weight throughout, arranged in a diagonal diamond lattice, motifs placed at every 45-degree grid intersection, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft dusty blue on warm cream, muted vintage wallpaper palette, on soft muted grey background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 150 --tile
```

---

**예시 5 — ⬢ 스티플 캡슐 컬럼 하프드롭 — 스타일 B**

```
Seamless repeating pattern of a single vertical capsule column shape filled with fine stipple dot texture, rendered with dense pointillism stipple dot texture fill, grainy dotwork shading, vintage engraving feel, arranged in a half-drop repeat, every other column shifted down by exactly half the motif height, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream stippled motifs on deep navy, vintage print palette, on deep navy background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 280 --tile
```

---

**예시 6 — ◆ 스티플 웨이브 다이아 그리드 — 스타일 B**

```
Seamless repeating pattern of a single wavy diamond shape filled with pointillism stipple gradient, rendered with halftone dot gradient fill, fading from dense to sparse dots, classic print grain, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, ivory stipple on midnight navy, classic etching palette, on midnight blue background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 300 --tile
```

---

**예시 7 — ⬭ 스티플 인터로킹 오벌 하프브릭 — 스타일 B**

```
Seamless repeating pattern of a single interlocking oval shape filled with dense stipple texture, rendered with fine spray grain texture fill, soft airbrushed dotwork, risograph print feel, arranged in a half-brick repeat, every other row shifted right by exactly half the motif width, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, tan stippled texture on black background, vintage poster palette, on charcoal grey background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 280 --tile
```

---

**예시 8 — ◖ 스티플 반원 스캘럽 — 스타일 B**

```
Seamless repeating pattern of a single scalloped half-circle filled with spray grain texture, rendered with crisp stipple dotwork fill, uniform dot density, vintage etching style, arranged in a scalloped row repeat, motifs stacked in offset rows with each scallop tangent to the next, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, cream dotwork on dark charcoal, engraving palette, on deep navy background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 320 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{rendering_style}` A → B | 모노라인 → 스티플 그레인 (같은 모티프 2버전) |
| `{layout}` 고정 + `{motif}` 변경 | 같은 격자의 고전 모티프 컬렉션 |
| `{color_palette}` 네이비 → 차콜/미드나잇 | 같은 클래식 기조 내 깊이감 변주 |
| `--s` 값 상승 (스타일 B) | 스티플 그레인 질감 극대화 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

**⚠️ 핵심 팁 5가지**

1. **"아날로그 = 스티플 그레인".** 스타일 B 를 쓸 때 `stipple / dotwork / halftone / spray grain / pointillism` 이 네 단어 중 반드시 하나 이상 넣으세요. 이게 아날로그 감성의 핵심이에요.
2. **모티프 1종 원칙.** 고전 곡선·기하 모티프는 복잡해서 2종 섞으면 격자가 무너져요. **단일 모티프 반복**이 정석. 점·X 같은 초소형 모티프만 예외적으로 ABAB 교차 허용.
3. **규칙성 키워드 필수.** `strict`, `mathematically precise`, `identical in size shape and orientation`, `no variation in motif placement` — 빠지면 배치 흐트러짐.
4. **모티프별 레이아웃 매칭.** 세이가이하 → 물결 평행 / 아치 → 스캘럽 오프셋 / 육각 → 벌집 / 쿼트리폴 → 다이아 — 이 궁합을 벗어나면 고전미가 안 살아요.
5. **스티플 스타일은 `--s 250~350`.** 그레인 질감은 stylize 값이 높아야 풍부하게 나와요. 반대로 모노라인은 `--s 100~180` 으로 억제해야 선이 깔끔.

---

**✅ 시리즈 만드는 추천 흐름**

1. **스타일 (A 모노라인 or B 스티플)** 하나 선택.
2. 같은 스타일 × 같은 컬러 팔레트로 **고전 모티프 4종 (아치·물결·육각·쿼트리폴)** 변주.
3. `--seed [번호]` 고정으로 선 두께·그레인 밀도 일관성 유지.
4. 시리즈 내 컬러 팔레트는 한 가지로 통일 (전부 네이비+크림 또는 전부 차콜+골드).

> 💡 **상시판매형 추천 조합.** ① 스티플 그레인 네이비+크림 4종 (캡슐·웨이브·오벌·반원) — 럭셔리 박스·벽지. ② 모노라인 골드 아트데코 4종 (육각·아치·쿼트리폴·다이아) — 호텔 어메니티·청첩장. ③ 모노라인 세이가이하 + 스티플 웨이브 페어 — 오리엔탈 감성 라인업.
>
