# 2-1) 아날로그 패턴 — 정형화된 기하학 반복 (Strict Geometric Seamless)

> **수학적으로 정형화된 기하학 모티프**를 다양한 렌더링(모노라인 / 플랫 블록 / 스티플 그레인 / 스트라이프 필 / 솔리드 실루엣)으로 표현하고, 엄격한 격자 구조로 반복시키는 seamless 패턴 프롬프트입니다. 스테이셔너리·벽지·원단·럭셔리 패키지·타일까지 모두 커버합니다.

---

**📌 이 프롬프트는 어떤 용도인가요?**

정형화된 기하 모티프를 **위치·크기·방향이 한 치도 흐트러지지 않는 타일**로 만드는 프롬프트예요. 렌더링 방식만 바꾸면 같은 기하 구조로 완전히 다른 분위기(미니멀 스테이셔너리·미드센추리 블록·빈티지 에칭·아트데코 라인)가 나와요.

이런 데 쓸 수 있어요:

- 명함·레터헤드·청첩장 배경
- 럭셔리 브랜드 박스·쇼핑백·쇼룸 배경
- Spoonflower / Redbubble 원단·벽지
- 바닥재·세라믹 타일 surface
- 호텔·리빙 벽지·쿠션
- 목업 / 웹 히어로 배경

> ⚠️ **"정형화된 기하학" 이 이 가이드의 테마예요.** 모티프는 기하 도형(원·삼각·사각·육각·아치·물결·스캘럽 등), 배치는 엄격한 격자, 렌더링은 5종 중 선택. 수채·과슈 같은 회화 매체는 범위 밖이에요.
>

---

**🚀 빠른 시작**

1. 아래 5가지 렌더링 중 하나를 선택.
2. 6가지 모티프 계열 중 하나를 선택.
3. 8가지 정형 격자 중 하나를 선택.
4. 컬러·배경을 골라 완성 프롬프트를 만드세요.
5. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern of {motif}, {rendering}, arranged in {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, on {background}, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**⚙️ 옵션 파라미터**

| **파라미터** | **권장값** | **메모** |
| --- | --- | --- |
| `--ar` | `1:1` | 타일은 반드시 정사각형 |
| `--s` | `100`~`350` | 모노라인 낮게 / 스티플 높게 |
| `--tile` | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본) | **절대 올리지 말 것** |
| `--niji 6` | 비추천 | 고전 톤이 일러스트화됨 |

---

**📌 변수 5개 — 모두 필수**

**1. `{motif}` — 기하 모티프 (6 계열 × 20+ 옵션)**

**A. 점·마크 (Micro marks):**

- `a single tiny filled dot`
- `a single small X mark`
- `a single small plus sign cross`
- `a single tiny asterisk star`
- `a tiny dot and a small X alternating in strict ABAB order`

**B. 폴리곤 (Polygons):**

- `a single solid equilateral triangle`
- `a single solid square`
- `a single solid diamond (rotated square)`
- `a single regular hexagon`
- `a single regular octagon`
- `a single solid pentagon`

**C. 곡선·아치 (Curves & arcs):**

- `a single semicircle`
- `a single quarter-circle arc filling a square cell`
- `a single full circle ring`
- `a single horizontal oval`
- `a single vertical capsule stadium shape`
- `a single set of three nested concentric arches forming a capsule`
- `a single seigaiha wave scale with three concentric arcs`
- `a single scallop shape`

**D. 격자·장식 (Lattice & ornamental):**

- `a single quatrefoil four-petal rosette`
- `a single trefoil three-petal shape`
- `a single chevron zigzag stripe`
- `a single L-shaped bracket corner`
- `a single simplified fleur-de-lis`
- `a single small eight-point compass star`

**E. 라인 기반 (Line-based motifs):**

- `a single set of four nested concentric squares`
- `a single set of nested concentric circles`
- `a single bundle of parallel stripes filling a square cell`
- `a single crosshatched square with diagonal hatching`
- `a single hexagon filled with parallel vertical stripes`

**F. 테셀레이팅 (Edge-to-edge tessellations):**

- `a single herringbone parallelogram tile`
- `a single basketweave rectangle tile`
- `a single pinwheel of four right triangles`
- `a single isometric cube with three visible faces`
- `a single Truchet quarter-circle tile`

> 💡 **모티프 1종 원칙.** 격자를 지키려면 단일 모티프 반복이 정석. 점·X 같은 초소형만 예외적으로 ABAB 교차 허용. 3종 이상은 격자 붕괴.
>

**2. `{rendering}` — 렌더링 5종**

**① 모노라인 (Monoline):**
- `rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill`

**② 플랫 컬러 블록 (Flat block):**
- `rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture`

**③ 스티플 그레인 (Stipple grain):**
- `rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel`

**④ 스트라이프 필 (Striped fill):**
- `rendered as a shape filled with fine parallel stripe hatching inside its silhouette, crisp thin lines`

**⑤ 아웃라인 + 대비 필 (Outline + fill):**
- `rendered with medium-weight crisp outlines and a contrasting flat fill color inside`

> 💡 **렌더링별 추천 모티프:**
>
> - 모노라인 → 곡선·아치·격자·라인 계열 (C·D·E)
> - 플랫 블록 → 폴리곤·쿼터아크 (B·C 일부)
> - 스티플 → 캡슐·오벌·다이아·반원 (B·C 대형)
> - 스트라이프 필 → 육각·사각·쿼터아크 (B·F)
> - 아웃라인+필 → 테셀레이션·쿼트리폴 (F·D)
>

**3. `{layout}` — 정형 격자 8종**

- `a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing`
- `a diagonal diamond lattice, motifs at every 45-degree grid intersection`
- `a half-drop repeat, every other column shifted down by exactly half the motif height`
- `a half-brick repeat, every other row shifted right by exactly half the motif width`
- `a hexagonal tessellation, motifs tessellating edge-to-edge in a honeycomb grid`
- `a triangular lattice, motifs at each node of an equilateral triangle grid`
- `a wave row repeat, motifs in perfectly parallel horizontal rows, each row identical`
- `a scalloped offset repeat, motifs in offset rows with each scallop tangent to the next`

> 💡 **모티프별 레이아웃 추천:**
>
> - 점·X·폴리곤 → 정방형 / 다이아몬드 / 하프드롭
> - 아치·캡슐·스캘럽 → 스캘럽 오프셋 / 하프드롭
> - 세이가이하 물결 → 물결 평행 반복
> - 육각·테셀레이션 → 벌집·삼각 테셀레이션
> - 쿼트리폴·콤파스 → 다이아몬드 격자
>

**4. `{color_palette}` — 2~3색 듀오톤/트리톤**

**미니멀 스테이셔너리:**
- `charcoal black on warm off-white`
- `deep navy on cream ivory`
- `slate grey on soft bone white`

**럭셔리·아트데코:**
- `metallic gold on deep navy`
- `metallic gold on charcoal grey`
- `gold outlines on dark emerald`

**빈티지 판화·에칭:**
- `warm cream stipple on deep navy`
- `tan dotwork on black`
- `ivory grain on midnight blue`

**미드센추리·모던:**
- `powder blue, cream, and slate, mid-century palette`
- `terracotta, mustard, and warm cream, vintage palette`
- `sage green and soft cream, muted mid-century palette`

**오리엔탈·빈티지 벽지:**
- `teal lines on warm cream`
- `dusty blue motifs on muted grey`

**5. `{background}` — 배경 톤**

- `deep navy background`
- `charcoal grey background`
- `midnight blue background`
- `dark emerald background`
- `warm cream paper`
- `ivory cardstock`
- `soft muted grey background`
- `off-white stationery paper`

---

**✏️ 적용 예시 8개 — 렌더링·모티프·레이아웃 다양하게**

---

**예시 1 — ✖️ 점·X 교차 × 모노라인 × 대각선 다이아몬드**

```
Seamless repeating pattern of a tiny dot and a small X alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a diagonal diamond lattice, motifs at every 45-degree grid intersection, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, deep navy on cream ivory, on warm cream paper, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**예시 2 — 🔺 삼각형 × 플랫 컬러 블록 × 삼각 격자**

```
Seamless repeating pattern of a single solid equilateral triangle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a triangular lattice, motifs at each node of an equilateral triangle grid, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, terracotta, mustard, and warm cream, vintage palette, on warm cream paper, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 3 — ◐ 쿼터아크 × 플랫 블록 × 정방형 그리드 (바우하우스)**

```
Seamless repeating pattern of a single quarter-circle arc filling a square cell, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a strict square grid, motifs aligned in perfectly straight rows and columns, identical spacing, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, powder blue, cream, and slate, mid-century palette, on ivory cardstock, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**예시 4 — ⬡ 육각 × 스트라이프 필 × 벌집 테셀레이션 (아트데코)**

```
Seamless repeating pattern of a single hexagon filled with parallel vertical stripes, rendered as a shape filled with fine parallel stripe hatching inside its silhouette, crisp thin lines, arranged in a hexagonal tessellation, motifs tessellating edge-to-edge in a honeycomb grid, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, metallic gold on charcoal grey, on charcoal grey background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 5 — 🌊 세이가이하 × 모노라인 × 물결 평행 반복**

```
Seamless repeating pattern of a single seigaiha wave scale with three concentric arcs, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a wave row repeat, motifs in perfectly parallel horizontal rows, each row identical, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, teal lines on warm cream, on warm cream paper, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 140 --tile
```

---

**예시 6 — ⬭ 캡슐 컬럼 × 스티플 그레인 × 하프드롭**

```
Seamless repeating pattern of a single vertical capsule stadium shape, rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel, arranged in a half-drop repeat, every other column shifted down by exactly half the motif height, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream stipple on deep navy, on deep navy background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 300 --tile
```

---

**예시 7 — ✦ 쿼트리폴 × 아웃라인 + 대비 필 × 다이아몬드 격자**

```
Seamless repeating pattern of a single quatrefoil four-petal rosette, rendered with medium-weight crisp outlines and a contrasting flat fill color inside, arranged in a diagonal diamond lattice, motifs at every 45-degree grid intersection, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty blue motifs on muted grey, on soft muted grey background, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 8 — ▰ 헤링본 × 플랫 블록 × 하프브릭 (테셀레이션)**

```
Seamless repeating pattern of a single herringbone parallelogram tile, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a half-brick repeat, every other row shifted right by exactly half the motif width, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, charcoal black on warm off-white, on off-white stationery paper, flat top-down view, clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{rendering}` 변경 | 같은 기하로 5가지 분위기 시리즈 (라인·블록·스티플·스트라이프·아웃라인) |
| `{rendering}` 고정 + `{motif}` 변경 | 같은 질감의 기하 컬렉션 (예: 전부 스티플 그레인) |
| `{layout}` 변경 | 그리드·다이아·벌집·물결 변주 |
| `{color_palette}` 변경 | 동일 기하로 4계절·4분위기 버전 |
| `--s` 낮춤 | 선·블록 더 깔끔 |
| `--s` 높임 | 스티플·그레인 질감 풍부 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

**⚠️ 핵심 팁 5가지**

1. **"정형화된 기하" 가 테마예요.** 모티프는 수학적 기하 도형만, 레이아웃은 엄격한 격자만, 렌더링은 5종 중 선택. 회화적 매체(수채·과슈)는 이 가이드에 안 맞아요.
2. **규칙성 키워드 필수.** `strict`, `mathematically precise`, `identical in size shape and orientation`, `no variation in motif placement` — 이거 빠지면 배치 흐트러짐.
3. **모티프 1종 원칙.** 여러 종 섞으면 격자가 무너져요. 점·X 같은 초소형만 `ABAB` 교차 허용.
4. **렌더링·모티프 매칭이 핵심.** 곡선/아치 → 모노라인, 대형 도형 → 스티플, 셀 있는 도형 → 스트라이프 필, 테셀레이션 → 아웃라인+필. 이 궁합을 맞추면 성공률이 확 올라요.
5. **`--s` 는 렌더링에 맞춰.** 모노라인 `100~180`, 플랫블록 `150~220`, 스티플 `250~350`, 스트라이프 필 `180~250`. 스타일 벗어나면 질감이 엇나가요.

---

**✅ 시리즈 만드는 추천 흐름**

1. **렌더링 하나** 를 정하세요 (예: 스티플 그레인).
2. 같은 렌더링 × 같은 팔레트 × 같은 레이아웃 밑에 **모티프만 4~6종** 변주 (원·캡슐·다이아·오벌·반원·쿼트리폴).
3. `--seed [번호]` 고정으로 선 두께·그레인 밀도 일관성 유지.
4. 컬렉션 팔레트는 한 가지로 통일.

> 💡 **상시판매형 추천 조합.**
> ① 스티플 네이비·크림 6종 (원·캡슐·오벌·반원·다이아·쿼트리폴) — 럭셔리 박스·벽지.
> ② 플랫블록 미드센추리 4종 (쿼터아크·반원·삼각·사각) — 벽지·쿠션.
> ③ 모노라인 골드 아트데코 4종 (육각·아치·쿼트리폴·콤파스) — 호텔·청첩장.
> ④ 스트라이프 필 모던 그래픽 4종 (스트라이프 육각·크로스해치 사각·중첩 원·헤링본) — 표지·패키지.
>
