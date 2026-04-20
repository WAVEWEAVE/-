# 2-2) 입체감·고급 텍스처 패턴 — 촉감 있는 표면

> **만져질 듯한 질감으로 규칙적으로 반복**되는 seamless 텍스처 패턴 프롬프트입니다. 톤온톤 엠보싱 다이아, 볼드 엠보싱 기하, 자수 크로스스티치, 노이즈 스티플 리소그래프 — 4가지 검증된 스타일을 제공합니다. 럭셔리 박스·쇼핑백·쿠션·벽지·쥬얼리 파우치·청첩장에 바로 쓸 수 있어요.

---

## 📌 이 프롬프트는 어떤 용도인가요?

**표면이 만져지는 듯한 큼직한 모티프를 숫자로 지정된 격자에 엄격하게 반복**시키는 seamless 텍스처 패턴을 만드는 프롬프트예요. 2026 트렌드 **Re:Media Glitch Craft**(디지털 자수 공예) · **Visible Co-Work**(AI × 공예 하이브리드) · **Cloud Dancer** 절제미 라인을 직접 반영했어요.

이런 데 쓸 수 있어요:

- 럭셔리 박스·쇼핑백·쥬얼리 파우치
- 청첩장·명함의 엠보싱 배경
- Spoonflower / Redbubble 원단·쿠션·커튼
- 호텔·부티크 벽지
- 하이엔드 레이블·태그

> ⚠️ **컬러는 밝은 톤만.** 딥 네이비·차콜·블랙 금지. 크림·민트·더스티 핑크·파우더 블루·버터 옐로우·피치·라벤더·코랄·세이지·머스터드 전용이에요.
>
> ⚠️ **모티프는 크게크게.** 촘촘하거나 빽빽한 반복은 텍스처의 디테일을 죽여요. 3×3 · 4×4 위주로만 가세요.

---

## 🚀 빠른 시작

1. 아래 **스타일 A (톤온톤 엠보싱 다이아)** · **B (볼드 엠보싱 기하)** · **C (자수 크로스스티치)** · **D (노이즈 스티플 리소그래프)** 중 하나를 고르세요.
2. 원하는 예시를 고르세요. (스타일당 2개, 총 8개)
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

## 📐 마스터 프롬프트 본문

```
Seamless repeating textured pattern of {motif}, {art_style}, arranged as a {grid_count} {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

## ⚙️ 옵션 파라미터

| **파라미터** | **스타일 A·C** | **스타일 B·D** | **메모** |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` | 타일은 정사각형 필수 |
| `--s` | `200`~`250` | `150`~`200` | A·C 질감 풍부(엠보싱·자수) / B·D 깔끔(플랫) |
| `--tile` | **필수** | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본 유지) | `0` (기본 유지) | 올리면 규칙성 붕괴 |

---

## 📌 변수 5개 — 모두 필수

### 1. `{motif}` — 어떤 질감 모티프?

**스타일 A — 톤온톤 엠보싱 다이아 (순수 기하):**

- `a single large diamond outline with a bold X cross inside dividing it into four triangles`
- `a single large diamond with a smaller diamond nested concentrically inside`
- `a single large quilted diamond cell with crossed diagonal ridges meeting at center`
- `a single large diamond with four dots at each vertex and a small dot at the center`

**스타일 B — 볼드 엠보싱 기하:**

- `a single large bold 4-point compass star formed by two overlapping squares rotated 45 degrees`
- `a single large concave square with four inward-curving triangular cutouts carved from each side`
- `a single large bold 8-point star with sharp pointed arms`
- `a single large diamond with a bold dot in the center surrounded by short radiating rays`

**스타일 C — 자수 크로스스티치 메달리온 (순수 기하):**

- `a single large cross-stitch 8-point compass star medallion with square border`
- `a single large cross-stitch diamond medallion with concentric diamond borders`
- `a single large cross-stitch bordered heart medallion`
- `a single large cross-stitch bold square motif with bordered center cross`
- `a single large cross-stitch 4-point star medallion with diamond border`

**스타일 D — 노이즈 스티플 기하 (단순 도형):**

- `a single large solid circle`
- `a single large solid diamond`
- `a single large solid hexagon`
- `a single large solid rounded square`
- `a single large solid half-circle arch shape`

> 💡 **모티프 1종 원칙.** 스타일 안에서 모티프 1개만 선택. 섞지 마세요.
>

### 2. `{art_style}` — 4가지 스타일 중 선택

**스타일 A — ◇ 톤온톤 엠보싱 다이아** (종이·가죽 엠보싱 계열, 재료감 없음)

```
rendered as a subtle tone-on-tone embossed relief with soft dimensional shadows along motif edges and shallow grooves between cells, smooth matte surface with gentle depth, no literal fabric or material texture, understated luxury emboss finish
```

**스타일 B — ◆ 볼드 엠보싱 기하** (종이 엠보싱·레터프레스 계열)

```
rendered as a high-contrast bold vector silhouette with subtle paper emboss shadow along motif edges, one accent color silhouette on off-white background, crisp clean edges, luxury letterpress stationery aesthetic
```

**스타일 C — 🪡 자수 크로스스티치** (수공예 자수·샘플러 계열)

```
rendered as a hand-embroidered cross-stitch texture with visible X-shaped thread stitches forming the motif, tactile needlepoint fabric surface, duotone thread on linen background, heritage sampler craft aesthetic
```

**스타일 D — 🌾 노이즈 스티플 리소그래프** (리소그래프 스티플 그레인 계열)

```
rendered with a soft risograph-style stippled grain fill inside each motif, fine speckled dots scattered evenly across the motif surface, subtle organic noise texture, duotone risograph print aesthetic, clean outer edges with grainy interior
```

> 💡 **스타일 선택 기준**
>
> |  | **A 엠보싱 다이아** | **B 엠보싱 기하** | **C 크로스스티치** | **D 노이즈 스티플** |
> | --- | --- | --- | --- | --- |
> | 무드 | 고요 · 톤온톤 | 미니멀 · 절제 | 헤리티지 · 공예 | 빈티지 · 리소 프린트 |
> | 어울리는 상품 | 가죽 파우치·청첩장 엠보싱 | 럭셔리 박스·레터프레스 | 쿠션·린넨 패브릭·자수 라벨 | 포스터·스티커·쇼핑백·티셔츠 |
> | 모티프 크기 | 큼직 | 아주 큼직 | 큼직 | 큼직 |

### 3. `{color_palette}` — 색감은? (전부 밝은 톤만)

**스타일 A** — 톤온톤 듀오톤 (핵심: tone-on-tone, 재료감 금지):

- `dusty pink tone-on-tone with slightly deeper pink shadow grooves`
- `warm cream tone-on-tone with warm beige shadow grooves`
- `soft sage tone-on-tone with deeper sage shadow grooves`
- `powder blue tone-on-tone with dusty blue shadow grooves`
- `butter yellow tone-on-tone with honey shadow grooves`

**스타일 B** — 싱글 악센트 on 밝은 배경:

- `warm mustard gold silhouette on soft bone white background`
- `dusty pink silhouette on warm cream background`
- `soft sage silhouette on ivory background`
- `coral silhouette on warm cream background`
- `powder blue silhouette on soft bone white background`

**스타일 C** — 실 색 on 린넨 배경:

- `warm mustard gold cross-stitch threads on warm cream linen background`
- `dusty pink threads on ivory linen background`
- `soft sage threads on warm cream linen background`
- `coral threads on bone white linen background`
- `powder blue threads on ivory linen background`

**스타일 D** — 리소그래프 듀오톤 (스티플 색 on 크림 배경):

- `warm mustard gold risograph stipple on warm cream background`
- `dusty pink stipple on ivory background`
- `soft sage stipple on warm cream background`
- `coral stipple on soft bone white background`
- `powder blue stipple on ivory background`
- `butter yellow stipple on warm cream background`

> 💡 **"pastel" 막연한 표현 피하세요.** `dusty pink`, `butter yellow`, `soft sage` 처럼 **구체적인 색 이름** 이 훨씬 또렷하게 나와요. 특히 스타일 A·D는 `tone-on-tone` 키워드가 필수.
>

### 4. `{grid_count}` — 타일에 몇 × 몇?

텍스처 패턴은 **크게크게**. 촘촘하면 디테일이 죽어요.

| **카운트** | **프롬프트 표현** | **인상** | **추천 스타일** |
| --- | --- | --- | --- |
| **3 × 3** | `a large 3 by 3 grid` | 아주 큼직·고급 | A, B, C |
| **4 × 4** | `a clear 4 by 4 grid` | 밸런스 | A, B, C, D |
| **5 × 5** | `a clear 5 by 5 grid` | 조밀·위브 | D (위브만) |

> ⚠️ **6×6 이상 금지.** 모티프가 뭉개져서 텍스처 디테일이 죽어요.
>

### 5. `{layout}` — 배치 방식

- `diagonal diamond lattice, rows rotated 45 degrees, with motifs sharing edges between cells forming a continuous embossed grid` *(스타일 A 전용)*
- `strict square grid where every motif's edges touch neighboring motifs creating a continuous tessellation` *(스타일 B 전용)*
- `traditional embroidery sampler grid, motifs arranged in strict rows and columns with even generous spacing` *(스타일 C 기본)*
- `half-drop repeat, every other column shifted down by exactly half the motif height, sampler spacing` *(스타일 C 변주)*
- `strict square grid with uniform spacing between motifs` *(스타일 D 기본)*
- `half-drop repeat, every other column shifted down by exactly half the motif height` *(스타일 D 변주)*
- `diagonal diamond lattice, rows rotated 45 degrees with uniform spacing` *(스타일 D 응용)*

> 💡 **스타일 × 레이아웃 궁합은 위 표기대로.** A엔 다이아 라티스, B엔 엣지 터치 그리드, C엔 샘플러 그리드, D엔 스퀘어 그리드/하프드롭 — 벗어나면 해당 스타일의 느낌이 깨져요.
>

---

## ✏️ 적용 예시 8개

---

### 예시 1 — ◇ 톤온톤 엠보싱 X-다이아 (더스티 핑크) — 스타일 A

```
Seamless repeating textured pattern of a single large diamond outline with a bold X cross inside dividing it into four triangles, rendered as a subtle tone-on-tone embossed relief with soft dimensional shadows along motif edges and shallow grooves between cells, smooth matte surface with gentle depth, no literal fabric or material texture, understated luxury emboss finish, arranged as a clear 4 by 4 grid diagonal diamond lattice, rows rotated 45 degrees, with motifs sharing edges between cells forming a continuous embossed grid, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty pink tone-on-tone with slightly deeper pink shadow grooves, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

### 예시 2 — ◇ 톤온톤 엠보싱 네스티드 다이아 (소프트 세이지) — 스타일 A

```
Seamless repeating textured pattern of a single large diamond with a smaller diamond nested concentrically inside, rendered as a subtle tone-on-tone embossed relief with soft dimensional shadows along motif edges and shallow grooves between cells, smooth matte surface with gentle depth, no literal fabric or material texture, understated luxury emboss finish, arranged as a large 3 by 3 grid diagonal diamond lattice, rows rotated 45 degrees, with motifs sharing edges between cells forming a continuous embossed grid, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage tone-on-tone with deeper sage shadow grooves, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

### 예시 3 — ◆ 볼드 엠보싱 컴파스 스타 (머스터드 골드 on 본화이트) — 스타일 B

```
Seamless repeating textured pattern of a single large bold 4-point compass star formed by two overlapping squares rotated 45 degrees, rendered as a high-contrast bold vector silhouette with subtle paper emboss shadow along motif edges, one accent color silhouette on off-white background, crisp clean edges, luxury letterpress stationery aesthetic, arranged as a clear 4 by 4 grid strict square grid where every motif's edges touch neighboring motifs creating a continuous tessellation, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm mustard gold silhouette on soft bone white background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

### 예시 4 — ◆ 볼드 엠보싱 콘케이브 스퀘어 (소프트 세이지 on 아이보리) — 스타일 B

```
Seamless repeating textured pattern of a single large concave square with four inward-curving triangular cutouts carved from each side, rendered as a high-contrast bold vector silhouette with subtle paper emboss shadow along motif edges, one accent color silhouette on off-white background, crisp clean edges, luxury letterpress stationery aesthetic, arranged as a large 3 by 3 grid strict square grid where every motif's edges touch neighboring motifs creating a continuous tessellation, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage silhouette on ivory background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

### 예시 5 — 🪡 크로스스티치 컴파스 스타 메달리온 (머스터드 골드 on 린넨 크림) — 스타일 C

```
Seamless repeating textured pattern of a single large cross-stitch 8-point compass star medallion with square border, rendered as a hand-embroidered cross-stitch texture with visible X-shaped thread stitches forming the motif, tactile needlepoint fabric surface, duotone thread on linen background, heritage sampler craft aesthetic, arranged as a clear 4 by 4 grid traditional embroidery sampler grid, motifs arranged in strict rows and columns with even generous spacing, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm mustard gold cross-stitch threads on warm cream linen background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

### 예시 6 — 🪡 크로스스티치 다이아몬드 메달리온 (더스티 핑크 on 린넨 아이보리) — 스타일 C

```
Seamless repeating textured pattern of a single large cross-stitch diamond medallion with concentric diamond borders, rendered as a hand-embroidered cross-stitch texture with visible X-shaped thread stitches forming the motif, tactile needlepoint fabric surface, duotone thread on linen background, heritage sampler craft aesthetic, arranged as a large 3 by 3 grid half-drop repeat, every other column shifted down by exactly half the motif height, sampler spacing, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty pink threads on ivory linen background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

### 예시 7 — 🌾 노이즈 스티플 서클 (머스터드 골드 on 크림) — 스타일 D

```
Seamless repeating textured pattern of a single large solid circle, rendered with a soft risograph-style stippled grain fill inside each motif, fine speckled dots scattered evenly across the motif surface, subtle organic noise texture, duotone risograph print aesthetic, clean outer edges with grainy interior, arranged as a clear 4 by 4 grid strict square grid with uniform spacing between motifs, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm mustard gold risograph stipple on warm cream background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

### 예시 8 — 🌾 노이즈 스티플 다이아몬드 (더스티 핑크 on 아이보리) — 스타일 D

```
Seamless repeating textured pattern of a single large solid diamond, rendered with a soft risograph-style stippled grain fill inside each motif, fine speckled dots scattered evenly across the motif surface, subtle organic noise texture, duotone risograph print aesthetic, clean outer edges with grainy interior, arranged as a large 3 by 3 grid half-drop repeat, every other column shifted down by exactly half the motif height, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty pink stipple on ivory background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

## 🔧 변주 팁

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{color_palette}` 변경 | 같은 질감 4계절 컬러 시리즈 |
| `{art_style}` A → D 전환 | 톤온톤 엠보싱 → 리소그래프 스티플로 전환 |
| `{art_style}` A → C 전환 | 엠보싱 → 수공예 자수 손맛 |
| `{grid_count}` `3×3 → 4×4` | 아주 큼직 → 밸런스 |
| `{layout}` 변경 (스타일 D 내) | 스퀘어 그리드 ↔︎ 하프드롭 ↔︎ 다이아 라티스 변주 |
| `tone-on-tone` 제거 (스타일 A) | 톤온톤 효과 붕괴 (A에서 절대 금지) |
| `--s` 값 상승 | 텍스처·짜임 디테일 풍부 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

## ⚠️ 핵심 팁 7가지

1. **스타일·모티프·레이아웃 궁합을 지키세요.** A→다이아 라티스·엠보싱 / B→엣지터치·컴파스 스타 / C→샘플러 그리드·크로스스티치 / D→스퀘어 그리드/하프드롭·노이즈 스티플. 섞으면 스타일의 정체성이 깨져요.
2. **재료 이름 금지 (스타일 A).** `rattan`/`cane`/`knit`/`yarn`/`crochet`/`macrame` 같은 단어를 넣으면 MJ가 실제 재료 클로즈업을 그려요. 스타일 A는 순수 기하 + 톤온톤 엠보싱만.
3. **노이즈는 스티플·리소그래프로만 (스타일 D).** `film grain`, `digital noise`, `glitch`, `heavy paper grain` 같은 단어는 피하세요. MJ가 사진 노이즈·글리치·종이 클로즈업으로 가버려요. `risograph-style stippled grain`, `fine speckled dots` 가 정답.
4. **크게크게 원칙.** 3×3 · 4×4 위주. 촘촘하면 텍스처 디테일이 뭉개져요.
5. **색은 전부 밝은 톤.** 구체적인 색 이름으로 (`dusty pink`, `butter yellow`, `soft sage`, `warm mustard gold`). 스타일 A는 `tone-on-tone` 키워드 필수.
6. **규칙성 키워드 필수.** `strict`, `mathematically precise repeat`, `identical in size shape and orientation`, `no variation in motif placement` — 하나라도 빠지면 흐트러져요.
7. **질감 디테일은 스타일별 `--s` 값 맞추기.** A·C는 `200` 이상(엠보싱·자수 결), B·D는 `150~180`(플랫·스티플). 과하면 재료감이 튀어나와요.

---

## ✅ 시리즈 만드는 추천 흐름

1. **스타일 하나** 선택 (A/B/C/D 중).
2. 그 스타일 안에서 **모티프·컬러만 4~6가지로 변주** (스타일 자체는 고정).
3. 첫 결과의 `--seed` 를 다음에 붙여 비례·톤 일관성 유지.
4. `--sref [첫 결과 URL]` 추가하면 완벽한 텍스처 컬렉션.

> 💡 **상시판매형 추천 조합.** ① 스타일 A 엠보싱 다이아 5색 톤온톤 (핑크·세이지·블루·옐로우·크림) — 가죽 파우치·청첩장 엠보싱. ② 스타일 B 엠보싱 컴파스 스타 4색 (머스터드·세이지·핑크·코랄) — 청첩장·레터프레스 박스. ③ 스타일 C 크로스스티치 컴파스·다이아·하트 3메달리온 × 5실 컬러 — 쿠션·린넨 패브릭·자수 라벨. ④ 스타일 D 노이즈 스티플 서클·다이아·헥사곤 3모티프 × 5색 리소그래프 — 포스터·스티커·쇼핑백·티셔츠.
>
