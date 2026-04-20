# 2-2) 입체감·고급 텍스처 패턴 — 촉감 있는 표면

> **만져질 듯한 질감으로 규칙적으로 반복**되는 seamless 텍스처 패턴 프롬프트입니다. 케인 위브(라탄·니트), 볼드 엠보싱 기하, 블록프린트 대형 보태니컬, 패브릭 위브 — 4가지 검증된 스타일을 제공합니다. 럭셔리 박스·쇼핑백·쿠션·벽지·쥬얼리 파우치·청첩장에 바로 쓸 수 있어요.

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

1. 아래 **스타일 A (케인 위브)** · **B (볼드 엠보싱 기하)** · **C (블록프린트 보태니컬)** · **D (패브릭 위브)** 중 하나를 고르세요.
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

| **파라미터** | **스타일 A·D** | **스타일 B·C** | **메모** |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` | 타일은 정사각형 필수 |
| `--s` | `200`~`250` | `150`~`200` | A·D 질감 풍부 / B·C 깔끔 |
| `--tile` | **필수** | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본 유지) | `0` (기본 유지) | 올리면 규칙성 붕괴 |

---

## 📌 변수 5개 — 모두 필수

### 1. `{motif}` — 어떤 질감 모티프?

**스타일 A — 케인 위브 (3D 짜임):**

- `a single large woven diamond cell formed by two thick rattan strands crossing diagonally in a bold X`
- `a single large knit-stitch diamond cell with visible chunky yarn loops`
- `a single large caned rattan diamond with a bold X weave at its center`
- `a single large macrame knot diamond unit`

**스타일 B — 볼드 엠보싱 기하:**

- `a single large bold 4-point compass star formed by two overlapping squares rotated 45 degrees`
- `a single large concave square with four inward-curving triangular cutouts carved from each side`
- `a single large bold 8-point star with sharp pointed arms`
- `a single large diamond with a bold dot in the center surrounded by short radiating rays`

**스타일 C — 블록프린트 대형 보태니컬:**

- `a single large hand-carved palm frond leaf with long radiating blades`
- `a single large hand-stamped fern leaf with rough textured edges`
- `a single large bold tropical leaf silhouette with visible center vein`
- `a single large simple oval leaf with hand-carved vein lines`
- `a single large bold flower blossom with five rounded petals`

**스타일 D — 패브릭 위브 텍스처:**

- `a single bold basketweave unit formed by two horizontal bars crossing over and under two vertical bars`
- `a single large concentric diamond unit with three nested diamond outlines`
- `a single bold diamond herringbone weave cell`
- `a single large woven twill diagonal bar unit`

> 💡 **모티프 1종 원칙.** 스타일 안에서 모티프 1개만 선택. 섞지 마세요.
>

### 2. `{art_style}` — 4가지 스타일 중 선택

**스타일 A — 🧶 케인 위브 3D** (라탄·니트·자카드 계열)

```
rendered as a tactile woven rattan cane texture with visible 3D yarn strands and deep dimensional shadows in the diagonal lattice grooves, duotone tone-on-tone aesthetic, Dior Cannage luxury finish
```

**스타일 B — ◆ 볼드 엠보싱 기하** (종이 엠보싱·레터프레스 계열)

```
rendered as a high-contrast bold vector silhouette with subtle paper emboss shadow along motif edges, one accent color silhouette on off-white background, crisp clean edges, luxury letterpress stationery aesthetic
```

**스타일 C — 🌿 블록프린트 대형 보태니컬** (리노컷·핸드스탬프 계열)

```
rendered as a hand-carved linocut block-print stamp with rough uneven edges, visible ink bleed and organic imperfections, tone-on-tone duotone, artisan hand-printed feel
```

**스타일 D — 🧵 패브릭 위브 텍스처** (배스킷·다이아 위브 계열)

```
rendered as a tight woven fabric texture with visible thread weave and subtle over-under shading, duotone tone-on-tone, tactile textile surface finish
```

> 💡 **스타일 선택 기준**
>
> |  | **A 케인 위브** | **B 엠보싱 기하** | **C 블록프린트** | **D 패브릭 위브** |
> | --- | --- | --- | --- | --- |
> | 무드 | 럭셔리 · 촉감 | 미니멀 · 절제 | 아티즌 · 손맛 | 클래식 · 텍스타일 |
> | 어울리는 상품 | 쥬얼리 파우치·핸드백 | 럭셔리 박스·청첩장 | 쿠션·원단·쇼핑백 | 커튼·러그·벽지 |
> | 모티프 크기 | 큼직 | 아주 큼직 | 큼직 | 중간·큼직 |

### 3. `{color_palette}` — 색감은? (전부 밝은 톤만)

**스타일 A** — 톤온톤 듀오톤 (핵심: tone-on-tone):

- `dusty pink tone-on-tone with soft pink strands and slightly deeper pink shadows in the grooves`
- `warm cream tone-on-tone with ivory strands and warm beige shadows`
- `soft sage tone-on-tone with sage strands and deeper sage shadows`
- `powder blue tone-on-tone with light blue strands and dusty blue shadows`
- `butter yellow tone-on-tone with cream yellow strands and honey shadows`

**스타일 B** — 싱글 악센트 on 밝은 배경:

- `warm mustard gold silhouette on soft bone white background`
- `dusty pink silhouette on warm cream background`
- `soft sage silhouette on ivory background`
- `coral silhouette on warm cream background`
- `powder blue silhouette on soft bone white background`

**스타일 C** — 손스탬프 듀오톤:

- `soft sage green ink stamps on warm cream background`
- `dusty pink stamps on ivory background`
- `coral stamps on warm cream background`
- `butter yellow stamps on soft bone white background`
- `warm mustard stamps on ivory background`

**스타일 D** — 위브 듀오톤:

- `powder blue and cream duotone weave`
- `dusty pink and warm cream duotone weave`
- `soft sage and ivory duotone weave`
- `butter yellow and cream duotone weave`
- `coral and soft bone white duotone weave`

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

- `diagonal diamond lattice, rows rotated 45 degrees, with interlocking woven strands sharing edges between cells` *(스타일 A 전용)*
- `strict square grid where every motif's edges touch neighboring motifs creating a continuous tessellation` *(스타일 B 전용)*
- `half-drop repeat, every other column shifted down by exactly half the motif height, organic block-print spacing` *(스타일 C 기본)*
- `offset diamond grid, motifs alternating in slightly rotated rows` *(스타일 C 변주)*
- `basketweave repeat, horizontal and vertical bar units alternating in perpendicular pairs` *(스타일 D — 배스킷)*
- `concentric diamond tessellation, nested diamond units tiled edge-to-edge` *(스타일 D — 다이아)*

> 💡 **스타일 × 레이아웃 궁합은 위 표기대로.** A엔 다이아 라티스, B엔 엣지 터치 그리드, C엔 하프드롭, D엔 배스킷/다이아 위브 — 벗어나면 해당 스타일의 느낌이 깨져요.
>

---

## ✏️ 적용 예시 8개

---

### 예시 1 — 🧶 케인 위브 라탄 (더스티 핑크 톤온톤) — 스타일 A

```
Seamless repeating textured pattern of a single large caned rattan diamond with a bold X weave at its center, rendered as a tactile woven rattan cane texture with visible 3D yarn strands and deep dimensional shadows in the diagonal lattice grooves, duotone tone-on-tone aesthetic, Dior Cannage luxury finish, arranged as a clear 4 by 4 grid diagonal diamond lattice, rows rotated 45 degrees, with interlocking woven strands sharing edges between cells, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty pink tone-on-tone with soft pink strands and slightly deeper pink shadows in the grooves, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 220 --tile
```

---

### 예시 2 — 🧶 니트 다이아 (소프트 세이지 톤온톤) — 스타일 A

```
Seamless repeating textured pattern of a single large knit-stitch diamond cell with visible chunky yarn loops, rendered as a tactile woven rattan cane texture with visible 3D yarn strands and deep dimensional shadows in the diagonal lattice grooves, duotone tone-on-tone aesthetic, Dior Cannage luxury finish, arranged as a large 3 by 3 grid diagonal diamond lattice, rows rotated 45 degrees, with interlocking woven strands sharing edges between cells, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage tone-on-tone with sage strands and deeper sage shadows, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 220 --tile
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

### 예시 5 — 🌿 블록프린트 팜 잎 (세이지 on 크림) — 스타일 C

```
Seamless repeating textured pattern of a single large hand-carved palm frond leaf with long radiating blades, rendered as a hand-carved linocut block-print stamp with rough uneven edges, visible ink bleed and organic imperfections, tone-on-tone duotone, artisan hand-printed feel, arranged as a clear 4 by 4 grid half-drop repeat, every other column shifted down by exactly half the motif height, organic block-print spacing, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage green ink stamps on warm cream background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

### 예시 6 — 🌿 블록프린트 플라워 블라썸 (더스티 핑크 on 아이보리) — 스타일 C

```
Seamless repeating textured pattern of a single large bold flower blossom with five rounded petals, rendered as a hand-carved linocut block-print stamp with rough uneven edges, visible ink bleed and organic imperfections, tone-on-tone duotone, artisan hand-printed feel, arranged as a large 3 by 3 grid half-drop repeat, every other column shifted down by exactly half the motif height, organic block-print spacing, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty pink stamps on ivory background, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

### 예시 7 — 🧵 배스킷 위브 (파우더 블루 & 크림) — 스타일 D

```
Seamless repeating textured pattern of a single bold basketweave unit formed by two horizontal bars crossing over and under two vertical bars, rendered as a tight woven fabric texture with visible thread weave and subtle over-under shading, duotone tone-on-tone, tactile textile surface finish, arranged as a clear 5 by 5 grid basketweave repeat, horizontal and vertical bar units alternating in perpendicular pairs, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, powder blue and cream duotone weave, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 220 --tile
```

---

### 예시 8 — 🧵 컨센트릭 다이아 위브 (버터 옐로우 & 아이보리) — 스타일 D

```
Seamless repeating textured pattern of a single large concentric diamond unit with three nested diamond outlines, rendered as a tight woven fabric texture with visible thread weave and subtle over-under shading, duotone tone-on-tone, tactile textile surface finish, arranged as a clear 4 by 4 grid concentric diamond tessellation, nested diamond units tiled edge-to-edge, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, butter yellow and cream duotone weave, flat top-down view, tactile luxury surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 220 --tile
```

---

## 🔧 변주 팁

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{color_palette}` 변경 | 같은 질감 4계절 컬러 시리즈 |
| `{art_style}` A → D 전환 | 3D 짜임 → 플랫 위브로 톤다운 |
| `{art_style}` A → C 전환 | 럭셔리 → 아티즌 손맛 |
| `{grid_count}` `3×3 → 4×4` | 아주 큼직 → 밸런스 |
| `{layout}` 변경 (스타일 D 내) | 배스킷 ↔︎ 컨센트릭 다이아 변주 |
| `tone-on-tone` 제거 (A·D) | 톤온톤 효과 붕괴 (절대 금지) |
| `--s` 값 상승 | 텍스처·짜임 디테일 풍부 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

## ⚠️ 핵심 팁 5가지

1. **스타일·모티프·레이아웃 궁합을 지키세요.** A→다이아 라티스·라탄 위브 / B→엣지터치·컴파스 스타 / C→하프드롭·블록프린트 / D→배스킷·컨센트릭 위브. 섞으면 스타일의 정체성이 깨져요.
2. **크게크게 원칙.** 3×3 · 4×4 위주. 촘촘하면 텍스처 디테일이 뭉개져요.
3. **색은 전부 밝은 톤.** 구체적인 색 이름으로 (`dusty pink`, `butter yellow`, `soft sage`, `warm mustard gold`). 스타일 A·D는 `tone-on-tone` 키워드 필수.
4. **규칙성 키워드 필수.** `strict`, `mathematically precise repeat`, `identical in size shape and orientation`, `no variation in motif placement` — 하나라도 빠지면 흐트러져요.
5. **질감 디테일은 `--s 200` 이상.** 너무 낮으면 평면처럼 나와서 스타일 A·D의 3D 짜임감이 사라져요.

---

## ✅ 시리즈 만드는 추천 흐름

1. **스타일 하나** 선택 (A/B/C/D 중).
2. 그 스타일 안에서 **모티프·컬러만 4~6가지로 변주** (스타일 자체는 고정).
3. 첫 결과의 `--seed` 를 다음에 붙여 비례·톤 일관성 유지.
4. `--sref [첫 결과 URL]` 추가하면 완벽한 텍스처 컬렉션.

> 💡 **상시판매형 추천 조합.** ① 스타일 A 케인 위브 5색 톤온톤 (핑크·세이지·블루·옐로우·크림) — 쥬얼리 파우치·핸드백 라이닝. ② 스타일 B 엠보싱 컴파스 스타 4색 (머스터드·세이지·핑크·코랄) — 청첩장·레터프레스 박스. ③ 스타일 C 블록프린트 팜·펀·플라워 3모티프 듀오톤 — 쿠션·쇼핑백. ④ 스타일 D 배스킷·컨센트릭 다이아 2레이아웃 × 5색 — 커튼·러그·벽지 컬렉션.
>
