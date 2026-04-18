# 2-1) 아날로그 패턴 — 정형화된 기하 타일

> **정형화된 기하 모티프를 타일처럼 규칙적으로 반복**시키는 seamless 패턴 프롬프트입니다. 점·X 스테이셔너리, 3색 8포인트 스타 벽지, 쿼트리폴 바닥타일, 도트 아웃라인 라티스 — 4가지 검증된 스타일을 제공합니다. 명함·청첩장·벽지·원단·세라믹 타일에 바로 쓸 수 있어요.

---

## 📌 이 프롬프트는 어떤 용도인가요?

**큼직한 기하 모티프를 숫자로 지정된 격자에 엄격하게 반복**시키는 seamless 패턴을 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- 명함·레터헤드·청첩장 배경
- Spoonflower / Redbubble 원단·벽지
- 세라믹 타일·바닥재
- 카페·리빙 벽지·쿠션
- 럭셔리 박스·쇼핑백

> ⚠️ **컬러는 밝은 톤만.** 딥 네이비·차콜·블랙 금지. 크림·민트·더스티 핑크·파우더 블루·버터 옐로우·피치·라벤더·코랄·세이지 전용이에요.
>
> ⚠️ **모티프는 4 스타일 안에서만.** 캡슐·원·반원 같은 단독 도형은 4 스타일 밖이라 이 가이드에서 다루지 않아요.

---

## 🚀 빠른 시작

1. 아래 **스타일 A (스테이셔너리)** · **B (스타 벽지)** · **C (바닥타일)** · **D (도트 아웃라인 라티스)** 중 하나를 고르세요.
2. 원하는 예시를 고르세요. (스타일당 2개, 총 8개)
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

## 📐 마스터 프롬프트 본문

```
Seamless repeating pattern of {motif}, {art_style}, arranged as a {grid_count} {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

## ⚙️ 옵션 파라미터

| **파라미터** | **스타일 A·D** | **스타일 B·C** | **메모** |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` | 타일은 정사각형 필수 |
| `--s` | `120`~`150` | `180`~`220` | A·D 얕게(라인) / B·C 풍부하게(면) |
| `--tile` | **필수** | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본 유지) | `0` (기본 유지) | 올리면 규칙성 붕괴 |

---

## 📌 변수 5개 — 모두 필수

### 1. `{motif}` — 어떤 기하 모티프?

**스타일 A — 스테이셔너리 미니 마크:**

- `a single small X mark`
- `a single tiny filled square`
- `a single small plus sign cross`
- `a tiny dot and a small X alternating in strict ABAB order`
- `a tiny filled square and a small X alternating in strict ABAB order`

**스타일 B — 볼드 스타:**

- `a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees with a tiny center dot`
- `a single bold 6-point star with a tiny center dot`
- `a single bold 5-point star`
- `a single bold 4-point star`

**스타일 C — 페탈·로제트:**

- `a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel`
- `a single bold trefoil formed by three rounded petals`
- `a single bold 6-petal rosette flower`
- `a single bold four-leaf clover shape`

**스타일 D — 도트 아웃라인 라티스:**

- `a single hexagon outline drawn with tiny evenly-spaced dots forming dashed edges, with a small solid filled dot at every vertex`
- `a single flat isometric cube lattice cell drawn with tiny evenly-spaced dots forming dashed edges, no face fill no shading, with a small solid filled dot at every vertex and Y-junction`
- `a single diamond rhombus outline drawn with tiny evenly-spaced dots forming dashed edges, with a small solid filled dot at every vertex`
- `a single triangle outline drawn with tiny evenly-spaced dots forming dashed edges, with a small solid filled dot at every vertex`

> 💡 **모티프 1종 원칙.** 점·X ABAB 교차만 예외. 그 외엔 단일 모티프 반복이 정석이에요.
>

### 2. `{art_style}` — 4가지 스타일 중 선택

**스타일 A — 📐 스테이셔너리 라인** (점·X 대각선 다이아 계열)

```
rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, classic stationery engraving feel
```

**스타일 B — ✦ 3색 스타 벽지** (빈티지 벽지 계열)

```
rendered as a flat solid color silhouette with a slightly darker inner layer for depth, motifs rotating through three colors in strict ABCABC order, vintage wallpaper aesthetic
```

**스타일 C — ✿ 바닥타일** (쿼트리폴 비스트로 계열)

```
rendered as a solid flat color silhouette with crisp vector edges, no outline, mid-century bistro floor tile aesthetic
```

**스타일 D — ⬡ 도트 아웃라인 라티스** (도트·대시 외곽선 + 정점 도트 계열)

```
rendered as outline-only shapes drawn with tiny evenly-spaced dots forming dashed line edges, small solid filled dot at every vertex intersection, no fill inside shapes, clean single-accent color on light background, delicate stationery geometric feel
```

> 💡 **스타일 선택 기준**
>
> |  | **A 스테이셔너리** | **B 스타 벽지** | **C 바닥타일** | **D 도트 아웃라인 라티스** |
> | --- | --- | --- | --- | --- |
> | 무드 | 미니멀 · 클래식 | 빈티지 · 귀여움 | 미드센추리 · 그래픽 | 스테이셔너리 · 모던 |
> | 어울리는 상품 | 명함·청첩장 | 벽지·쿠션 | 타일·에코백 | 명함·노트·포장지·벽지 |
> | 모티프 크기 | 아주 작게 | 큼직 | 중간 | 중간·큼직 |

### 3. `{color_palette}` — 색감은? (전부 밝은 톤만)

**스타일 A** — 2색 듀오톤 마크:

- `soft sage green marks on warm cream background`
- `dusty pink marks on ivory background`
- `powder blue marks on soft bone white background`
- `butter yellow marks on warm cream background`
- `soft coral marks on warm off-white background`

**스타일 B** — ABCABC 3색 로테이션 + 밝은 배경:

- `rotating through three colors in strict ABCABC order (dusty pink, butter yellow, and powder blue), on soft sage cream background`
- `rotating through three colors in strict ABCABC order (soft sage, dusty pink, and cream), on warm cream background`
- `rotating through three colors in strict ABCABC order (lavender, peach, and mint), on ivory background`
- `rotating through three colors in strict ABCABC order (coral, lemon yellow, and sky blue), on warm cream background`

**스타일 C** — 2색 듀오톤 (엣지 터치용):

- `warm cream motifs on soft mint background`
- `dusty pink motifs on warm cream background`
- `butter yellow motifs on soft sage background`
- `coral motifs on powder blue background`
- `lavender motifs on warm ivory background`

**스타일 D** — 싱글 악센트 컬러 (도트+대시 아웃라인용, 듀오톤):

- `warm mustard gold dotted outlines and vertex dots on warm cream background`
- `dusty pink dotted outlines and vertex dots on ivory background`
- `soft sage green dotted outlines and vertex dots on warm cream background`
- `powder blue dotted outlines and vertex dots on soft bone white background`
- `coral dotted outlines and vertex dots on warm cream background`
- `lavender dotted outlines and vertex dots on ivory background`

> 💡 **"pastel" 막연한 표현 피하세요.** `dusty pink`, `butter yellow`, `soft sage` 처럼 **구체적인 색 이름** 이 훨씬 또렷하게 나와요.
>

### 4. `{grid_count}` — 타일에 몇 × 몇?

숫자로 박아야 모티프 크기·간격이 흔들리지 않아요.

| **카운트** | **프롬프트 표현** | **인상** | **추천 스타일** |
| --- | --- | --- | --- |
| **3 × 3** | `a large 3 by 3 grid` | 큼직·그래픽 | B |
| **4 × 4** | `a clear 4 by 4 grid` | 밸런스 | B, C, D |
| **5 × 5** | `a clear 5 by 5 grid` | 타일·원단 | C, D |
| **6 × 6** | `a precise 6 by 6 grid` | 세밀 | A, D |

> ⚠️ **7×7 이상 금지.** 규칙성이 무너져요.
>

### 5. `{layout}` — 배치 방식

- `diagonal diamond lattice, rows rotated 45 degrees` *(스타일 A 전용)*
- `half-drop repeat, every other column shifted down by exactly half the motif height` *(스타일 B 기본)*
- `half-brick repeat, every other row shifted right by exactly half the motif width` *(스타일 B 변주)*
- `strict square grid with motifs touching at corners` *(스타일 C 전용)*
- `flat hexagonal honeycomb lattice, hexagons edge-to-edge sharing dotted edges, vertex dots at every shared corner` *(스타일 D — 헥사곤)*
- `isometric cube lattice drawn flat with no face shading, three dashed edges meeting at every Y-junction vertex with a solid dot marker` *(스타일 D — 아이소 라티스)*
- `diamond grid lattice, rhombus cells edge-to-edge sharing dotted edges, vertex dots at every shared corner` *(스타일 D — 다이아 그리드)*
- `triangular tessellation, triangles edge-to-edge sharing dotted edges, vertex dots at every shared corner` *(스타일 D — 트라이앵글)*

> 💡 **스타일 × 레이아웃 궁합은 위 표기대로.** A엔 다이아, B엔 하프드롭/하프브릭, C엔 엣지터치 그리드, D엔 라티스(헥사곤/아이소/다이아/트라이앵글) — 벗어나면 해당 스타일의 느낌이 깨져요.
>

---

## ✏️ 적용 예시 8개

---

### 예시 1 — 📐 점·X 스테이셔너리 (세이지+크림) — 스타일 A

```
Seamless repeating pattern of a tiny filled square and a small X mark alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, classic stationery engraving feel, arranged as a precise 6 by 6 grid diagonal diamond lattice, rows rotated 45 degrees, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage green marks on warm cream background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

### 예시 2 — 📐 점·X 스테이셔너리 (더스티 핑크) — 스타일 A

```
Seamless repeating pattern of a tiny dot and a small X alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, classic stationery engraving feel, arranged as a precise 6 by 6 grid diagonal diamond lattice, rows rotated 45 degrees, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty pink marks on ivory background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

### 예시 3 — 📐 플러스 크로스 스테이셔너리 (버터 옐로우) — 스타일 A

```
Seamless repeating pattern of a single small plus sign cross, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, classic stationery engraving feel, arranged as a precise 6 by 6 grid diagonal diamond lattice, rows rotated 45 degrees, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, butter yellow marks on warm cream background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

### 예시 4 — ✦ 8포인트 스타 3색 벽지 (핑크·옐로우·블루) — 스타일 B

```
Seamless repeating pattern of a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees with a tiny center dot, rendered as a flat solid color silhouette with a slightly darker inner layer for depth, motifs rotating through three colors in strict ABCABC order, vintage wallpaper aesthetic, arranged as a clear 4 by 4 grid half-drop repeat, every other column shifted down by exactly half the motif height, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, rotating through three colors in strict ABCABC order (dusty pink, butter yellow, and powder blue), on soft sage cream background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

### 예시 5 — ✦ 6포인트 스타 3색 벽지 (라벤더·피치·민트) — 스타일 B

```
Seamless repeating pattern of a single bold 6-point star with a tiny center dot, rendered as a flat solid color silhouette with a slightly darker inner layer for depth, motifs rotating through three colors in strict ABCABC order, vintage wallpaper aesthetic, arranged as a clear 4 by 4 grid half-drop repeat, every other column shifted down by exactly half the motif height, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, rotating through three colors in strict ABCABC order (lavender, peach, and mint), on ivory background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

### 예시 6 — ✿ 쿼트리폴 바닥타일 (크림 on 민트) — 스타일 C

```
Seamless repeating pattern of a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel, rendered as a solid flat color silhouette with crisp vector edges, no outline, mid-century bistro floor tile aesthetic, arranged as a clear 5 by 5 grid strict square grid with motifs touching at corners, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream motifs on soft mint background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

### 예시 7 — ✿ 6-Petal 로제트 타일 (코랄 on 파우더 블루) — 스타일 C

```
Seamless repeating pattern of a single bold 6-petal rosette flower, rendered as a solid flat color silhouette with crisp vector edges, no outline, mid-century bistro floor tile aesthetic, arranged as a clear 5 by 5 grid strict square grid with motifs touching at corners, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, coral motifs on powder blue background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

### 예시 8 — ⬡ 아이소 라티스 도트 아웃라인 (머스터드 골드 on 크림) — 스타일 D

```
Seamless repeating pattern of a single flat isometric cube lattice cell drawn with tiny evenly-spaced dots forming dashed edges, no face fill no shading, with a small solid filled dot at every vertex and Y-junction, rendered as outline-only shapes drawn with tiny evenly-spaced dots forming dashed line edges, small solid filled dot at every vertex intersection, no fill inside shapes, clean single-accent color on light background, delicate stationery geometric feel, arranged as a clear 4 by 4 grid isometric cube lattice drawn flat with no face shading, three dashed edges meeting at every Y-junction vertex with a solid dot marker, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm mustard gold dotted outlines and vertex dots on warm cream background, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 140 --tile
```

---

## 🔧 변주 팁

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{color_palette}` 변경 | 같은 모티프 4계절 컬러 시리즈 |
| `{art_style}` A → C 전환 | 같은 기하 구조, 라인 → 바닥타일 전환 |
| `{grid_count}` `3×3 → 5×5` | 큼직 → 밸런스 → 세밀 |
| `{layout}` 변경 (스타일 B 내) | 하프드롭 ↔︎ 하프브릭 변주 |
| ABCABC → ABCDEF 4색 로테이션 | 스타일 B에서 4색 버전으로 확장 |
| `--s` 값 상승 | 3D·레이어드 음영 풍부 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

## ⚠️ 핵심 팁 5가지

1. **스타일·모티프·레이아웃 궁합을 지키세요.** A→다이아·마크 / B→하프드롭·스타 / C→엣지터치·로제트 / D→도트 아웃라인 라티스(헥사곤·아이소·다이아·트라이앵글). 섞으면 스타일의 정체성이 깨져요.
2. **그리드 카운트는 숫자로 박으세요.** `a 3 by 3 / a 4 by 4 / a 5 by 5`. 모호한 "small motif" 대신 개수 지정이 규칙성을 유지해줘요.
3. **색은 전부 밝은 톤.** 구체적인 색 이름으로 (`dusty pink`, `butter yellow`, `soft mint`). "pastel" 같은 막연한 단어는 피하세요.
4. **규칙성 키워드 필수.** `strict`, `mathematically precise repeat`, `identical in size shape and orientation`, `no variation in motif placement` — 하나라도 빠지면 흐트러져요.
5. **한 번에 성공 어려움.** 4~8회 재생성 각오. 마음에 드는 컷에서 `--seed` 고정해 시리즈화하세요.

---

## ✅ 시리즈 만드는 추천 흐름

1. **스타일 하나** 선택 (A/B/C/D 중).
2. 그 스타일 안에서 **모티프·컬러만 4~6가지로 변주** (스타일 자체는 고정).
3. 첫 결과의 `--seed` 를 다음에 붙여 비례·톤 일관성 유지.
4. `--sref [첫 결과 URL]` 추가하면 완벽한 패턴 컬렉션.

> 💡 **상시판매형 추천 조합.** ① 스타일 A 스테이셔너리 4색 (세이지·핑크·블루·옐로우) — 명함·청첩장. ② 스타일 B 3색 로테이션 4계절 (봄·여름·가을·겨울 팔레트) — 벽지 컬렉션. ③ 스타일 C 쿼트리폴·로제트·클로버 3종 듀오톤 — 카페 타일. ④ 스타일 D 도트 아웃라인 라티스 4라티스(헥사곤·아이소·다이아·트라이앵글) × 머스터드 골드 — 모던 스테이셔너리 세트.
>
