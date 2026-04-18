# 2-1) 아날로그 패턴 — 큼직한 기하 타일 (Classic Geometric Seamless)

> **레퍼런스 기반 4가지 템플릿**으로 빠르게 시작할 수 있는 클래식 기하 패턴 프롬프트입니다. 점·X 스테이셔너리 / 3색 8포인트 스타 벽지 / 쿼트리폴 바닥타일 / 아이소메트릭 3D 큐브 — 4대 정석 패턴을 확실히 뽑아내요. 큼직한 모티프 · 지정 그리드 · 규칙적 반복이 핵심.

---

**📌 이 프롬프트는 어떤 용도인가요?**

**클래식 기하 모티프를 정확한 반복 격자로** 배치하는 프롬프트예요. 아래 4가지 레퍼런스 스타일이 기본 탬플릿이고, 모듈 변수로 자유롭게 변주할 수 있어요.

이런 데 쓸 수 있어요:

- 명함·청첩장·레터헤드 배경
- 럭셔리 박스·쇼핑백
- Spoonflower / Redbubble 원단·벽지
- 세라믹 타일·바닥재
- 호텔·리빙 벽지·쿠션
- 웹 배경·목업

> ⚠️ **4가지 템플릿으로 시작하세요.** 템플릿 A (점·X 스테이셔너리) / 템플릿 B (3색 스타 벽지) / 템플릿 C (쿼트리폴 타일) / 템플릿 D (아이소 3D 큐브) — 이 넷이 검증된 정석이에요. 변형은 모듈 변수로.
>

---

**🎯 4가지 레퍼런스 템플릿 (바로 복사)**

---

**템플릿 A — 📐 점·X 스테이셔너리 (Image 1)**

```
Seamless repeating pattern of a tiny filled square and a small X mark alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, arranged as a precise 6 by 6 diagonal diamond lattice, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, charcoal black marks on soft warm grey, on soft warm grey background, flat top-down view, minimalist classic stationery design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

**템플릿 B — ✦ 3색 8포인트 스타 벽지 (Image 2)**

```
Seamless repeating pattern of a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees, with a tiny center dot, rendered as a flat solid color silhouette with a slightly darker inner star layered on top, arranged as a clear 3 by 4 half-drop repeat, stars rotating through three colors in strict ABCABC order (olive green, dark navy, and dusty light blue), every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, on soft sage cream background, flat top-down view, vintage wallpaper design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

**템플릿 C — ✿ 쿼트리폴 바닥타일 (Image 3)**

```
Seamless repeating pattern of a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel, rendered as a solid flat color silhouette with crisp vector edges, no outline, arranged as a clear 5 by 5 strict square grid with motifs touching at corners, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream motifs on deep teal background, on deep teal background, flat top-down view, mid-century bistro tile design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

**템플릿 D — 🟥 아이소메트릭 3D 큐브 (Image 4)**

```
Seamless repeating pattern of a single isometric 3D cube with three visible faces (top, left, right) each rendered in a distinct flat color tone (lightest on top, medium on right, darkest on left), crisp vector edges, no outlines, arranged as an isometric tessellation where cubes tile edge-to-edge creating a continuous 3D illusion, every cube identical in size shape and orientation, mathematically precise repeat, dusty pink lightest face, warm cream medium face, deep burgundy darkest face, on warm cream background, flat top-down view, classic isometric geometric design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**🚀 모듈형 변수 (템플릿 변주용)**

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern of {motif}, {rendering}, arranged as a {grid_count} {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, on {background}, flat top-down view, bold clean classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**⚙️ 옵션 파라미터**

| **파라미터** | **권장값** | **메모** |
| --- | --- | --- |
| `--ar` | `1:1` | 타일은 반드시 정사각형 |
| `--s` | `120`~`280` | 모노라인·블록 낮게 / 스티플·3D 높게 |
| `--tile` | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본) | **절대 올리지 말 것** |

---

**📌 변수 5개**

**1. `{motif}` — 5 계열 × 12+ 옵션**

**A. 미니 마크 (템플릿 A):**
- `a single small X mark`
- `a single tiny filled square`
- `a single small plus sign cross`
- `a tiny dot and a small X alternating in strict ABAB order`
- `a tiny filled square and a small X alternating in strict ABAB order`

**B. 스타 (템플릿 B):**
- `a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees, with a tiny center dot`
- `a single bold 6-point star`
- `a single bold 5-point star`

**C. 폴리곤:**
- `a single bold solid triangle`
- `a single bold solid square`
- `a single bold solid diamond`
- `a single bold hexagon outline`

**D. 곡선·장식 (템플릿 C 계열):**
- `a single bold filled circle`
- `a single bold semicircle`
- `a single bold vertical capsule shape`
- `a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel`

**E. 아이소 3D (템플릿 D):**
- `a single isometric 3D cube with three visible faces in three distinct flat color tones`

**2. `{rendering}` — 렌더링 5종**

**① 플랫 실루엣 (기본):**
- `rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture`

**② 플랫 레이어드 (2 톤 겹침 — 템플릿 B 계열):**
- `rendered as a flat solid color silhouette with a slightly darker inner layer for depth`

**③ 모노라인 + 점선 격자 (템플릿 A 계열):**
- `rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs`

**④ 아이소 3D 3톤 (템플릿 D 계열):**
- `rendered as an isometric 3D shape with three flat color tones for top, left, and right faces`

**⑤ 스티플 그레인 (빈티지 에칭):**
- `rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel`

**3. `{grid_count}` — 타일당 반복 수**

| **카운트** | **프롬프트** | **인상** |
| --- | --- | --- |
| **3 × 3** | `a large 3 by 3` | 포인트 큼직 (박스·포스터) |
| **4 × 4** | `a clear 4 by 4` | 밸런스 (벽지 기본) |
| **5 × 5** | `a clear 5 by 5` | 타일·원단 밸런스 |
| **6 × 6** | `a precise 6 by 6` | 세밀 (스테이셔너리 전용) |

> ⚠️ **7×7 이상은 금지.** 규칙성 무너짐.
>

**4. `{layout}` — 배치 6종**

- `strict square grid with motifs clearly separated` *(간격형 그리드)*
- `strict square grid with motifs touching at corners` *(엣지 터치 — 템플릿 C)*
- `diagonal diamond lattice, rows rotated 45 degrees` *(대각선 다이아)*
- `half-drop repeat, every other column shifted down by exactly half the motif height` *(하프드롭 — 템플릿 B)*
- `half-brick repeat, every other row shifted right by exactly half the motif width` *(하프브릭)*
- `isometric tessellation where shapes tile edge-to-edge creating a continuous 3D illusion` *(아이소 테셀 — 템플릿 D)*

**5. `{color_palette}` 및 `{background}`**

**듀오톤 (2색):**
- `charcoal black on warm off-white`
- `deep navy on cream ivory`
- `warm cream motifs on deep teal background` *(템플릿 C)*
- `metallic gold on charcoal grey`

**3색 로테이션 (템플릿 B):**
- `motifs rotating through three colors in strict ABCABC order (olive green, dark navy, and dusty light blue)`
- `motifs rotating through three colors in strict ABCABC order (terracotta, mustard, and sage green)`
- `motifs rotating through three colors in strict ABCABC order (dusty pink, powder blue, and cream)`

**아이소 3톤 (템플릿 D):**
- `dusty pink lightest face, warm cream medium face, deep burgundy darkest face`
- `light grey, medium grey, dark charcoal faces`
- `mint cream, teal medium, deep pine darkest`

**미드센추리·빈티지:**
- `powder blue and cream, mid-century palette`
- `sage green and soft cream, muted palette`
- `dusty blue on muted grey, vintage wallpaper palette`

**배경 톤:**
- `warm cream paper` / `ivory cardstock` / `soft muted grey`
- `deep teal` / `deep navy` / `charcoal grey` / `soft sage cream`

---

**✏️ 적용 예시 8개 — 4 템플릿 + 4 변주**

---

**예시 1 — 🔷 템플릿 A : 점·X 스테이셔너리**

```
Seamless repeating pattern of a tiny filled square and a small X mark alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, arranged as a precise 6 by 6 diagonal diamond lattice, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, charcoal black marks on soft warm grey, on soft warm grey background, flat top-down view, minimalist classic stationery design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**예시 2 — ✦ 템플릿 B : 3색 8포인트 스타**

```
Seamless repeating pattern of a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees, with a tiny center dot, rendered as a flat solid color silhouette with a slightly darker inner star layered on top, arranged as a clear 3 by 4 half-drop repeat, stars rotating through three colors in strict ABCABC order (olive green, dark navy, and dusty light blue), every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, on soft sage cream background, flat top-down view, vintage wallpaper design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 3 — ✿ 템플릿 C : 쿼트리폴 바닥타일**

```
Seamless repeating pattern of a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel, rendered as a solid flat color silhouette with crisp vector edges, no outline, arranged as a clear 5 by 5 strict square grid with motifs touching at corners, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream motifs on deep teal background, on deep teal background, flat top-down view, mid-century bistro tile design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 4 — 🟥 템플릿 D : 아이소 3D 큐브**

```
Seamless repeating pattern of a single isometric 3D cube with three visible faces, rendered as an isometric 3D shape with three flat color tones for top, left, and right faces, arranged in an isometric tessellation where shapes tile edge-to-edge creating a continuous 3D illusion, every cube identical in size shape and orientation, mathematically precise repeat, dusty pink lightest face, warm cream medium face, deep burgundy darkest face, on warm cream background, flat top-down view, classic isometric geometric design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**예시 5 — 🔺 변주 : 3색 삼각 하프드롭**

```
Seamless repeating pattern of a single bold solid triangle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged as a clear 4 by 5 half-drop repeat, triangles rotating through three colors in strict ABCABC order (terracotta, mustard, and sage green), every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, on warm cream background, flat top-down view, mid-century wallpaper design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 6 — ⚫ 변주 : 큼직한 원 3×3 정방형 그리드**

```
Seamless repeating pattern of a single bold filled circle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged as a large 3 by 3 strict square grid with motifs clearly separated, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, powder blue and cream, mid-century palette, on ivory cardstock, flat top-down view, bold clean graphic design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 7 — ⬡ 변주 : 육각 아웃라인 4×4 하프드롭 (아트데코)**

```
Seamless repeating pattern of a single bold hexagon outline, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged as a clear 4 by 4 half-drop repeat, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, metallic gold on charcoal grey, on charcoal grey background, flat top-down view, art deco surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 140 --tile
```

---

**예시 8 — ⬭ 변주 : 캡슐 스티플 4×4 하프드롭 (빈티지 에칭)**

```
Seamless repeating pattern of a single bold vertical capsule shape, rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel, arranged as a clear 4 by 4 half-brick repeat, every other row shifted right by exactly half the motif width, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream stipple on deep navy, on deep navy background, flat top-down view, vintage engraving design, tileable, no text, no variation in motif placement. --ar 1:1 --s 280 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| 듀오톤 → `ABCABC 3색 로테이션` | 템플릿 B 같은 빈티지 벽지 |
| `motifs clearly separated` → `motifs touching at corners` | 템플릿 C 같은 타일 바닥 |
| 플랫 실루엣 → 아이소 3D 3톤 | 템플릿 D 같은 3D 기하 |
| `3 by 3` → `5 by 5` → `6 by 6` | 포인트 → 기본 → 세밀 |
| `{motif}` 고정 + `{rendering}` 변경 | 같은 기하 4분위기 시리즈 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

**⚠️ 핵심 팁 5가지**

1. **4개 템플릿부터 시작.** 레퍼런스 4장에서 검증된 조합이에요. 바로 복사해서 돌려보고, 마음에 들면 모듈 변수로 변주.
2. **그리드 카운트는 숫자로.** `a 4 by 4 / a 5 by 5` 구문 필수. 모티프 개수를 숫자로 박아야 크기가 흔들리지 않아요.
3. **3색 로테이션은 템플릿 B 공식 그대로.** `rotating through three colors in strict ABCABC order (A색, B색, C색)` — 이 문법을 깨면 랜덤 색 배치됨.
4. **아이소 3D는 3톤 필수.** `lightest top / medium right / darkest left` — 3면 톤 지정이 3D 환영의 핵심.
5. **규칙성 키워드는 전부 넣기.** `strict`, `mathematically precise repeat`, `identical in size shape and orientation`, `no variation in motif placement` — 하나라도 빠지면 흐트러져요.

---

**✅ 시리즈 만드는 추천 흐름**

1. **4개 템플릿 중 하나**를 메인으로 정하세요.
2. 그 템플릿의 **컬러만 4~6가지로 변주** (팔레트 통일).
3. `--seed [번호]` 고정으로 선 두께·그레인·3D 톤 일관성 유지.
4. 같은 컬렉션 = 같은 템플릿 × 같은 그리드 카운트.

> 💡 **상시판매형 추천 조합.**
> ① 템플릿 B (3색 8포인트 스타) 4계절 컬러 4종 — 빈티지 벽지 컬렉션.
> ② 템플릿 C (쿼트리폴 바닥타일) 4색 4종 — 카페·베이커리 내부 바닥·벽.
> ③ 템플릿 D (아이소 3D 큐브) 4톤 컴비 4종 — 럭셔리 박스·웹 배경.
> ④ 템플릿 A (점·X 스테이셔너리) 2색 4종 — 명함·레터헤드·청첩장 세트.
>
