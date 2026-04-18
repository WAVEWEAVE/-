# 2-1) 아날로그 패턴 — 정형화된 기하학 반복 (Simple & Sparse Seamless)

> **단순한 기하 모티프 하나**를 **여백 넉넉한 격자** 위에서 엄격하게 반복시키는 seamless 패턴 프롬프트입니다. 미드저니의 약점(촘촘·복잡한 모티프에서 규칙성 무너짐)을 피하도록 **모티프는 단순**, **배치는 듬성듬성**하게 설계했어요. 스테이셔너리·벽지·럭셔리 패키지·타일에 바로 쓸 수 있어요.

---

**📌 이 프롬프트는 어떤 용도인가요?**

단순 기하 모티프를 **위치·크기·방향이 흐트러지지 않는 타일**로 만들되, **모티프 간 여백을 충분히** 두어 미드저니가 규칙성을 지킬 수 있게 한 프롬프트예요.

이런 데 쓸 수 있어요:

- 명함·레터헤드·청첩장 배경
- 럭셔리 브랜드 박스·쇼핑백
- Spoonflower / Redbubble 원단·벽지
- 바닥재·세라믹 타일
- 호텔·리빙 벽지
- 목업 / 웹 히어로 배경

> ⚠️ **단순함이 성공의 열쇠예요.** 미드저니는 복잡한 모티프·촘촘한 배치에서 반드시 규칙이 무너져요. 이 가이드의 모든 옵션은 **"작고 단순한 모티프 + 여백 넉넉한 배치"** 원칙을 지켜요. 모티프를 복잡하게 꾸미거나 빽빽하게 붙이면 실패해요.
>

---

**🚀 빠른 시작**

1. 아래 4가지 렌더링 중 하나 선택.
2. 12가지 단순 모티프 중 하나 선택.
3. 5가지 여유 있는 격자 중 하나 선택.
4. 컬러·배경을 골라 프롬프트 완성.
5. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern of {motif}, {rendering}, arranged in {layout}, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, {color_palette}, on {background}, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

> 💡 **`small motif with generous uniform spacing` 문구가 이 가이드의 핵심이에요.** 이 한 줄이 미드저니의 "빽빽하게 채우려는 습성" 을 막아줘요.
>

---

**⚙️ 옵션 파라미터**

| **파라미터** | **권장값** | **메모** |
| --- | --- | --- |
| `--ar` | `1:1` | 타일은 반드시 정사각형 |
| `--s` | `100`~`300` | 모노라인 낮게 / 스티플 높게 |
| `--tile` | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본) | **절대 올리지 말 것** |
| `--niji 6` | 비추천 | 고전 톤이 일러스트화됨 |

---

**📌 변수 5개 — 모두 필수**

**1. `{motif}` — 단순 기하 모티프 (4 계열 × 12 옵션)**

**A. 점·마크 (극도로 단순):**

- `a single tiny filled dot`
- `a single small X mark`
- `a single small plus sign cross`
- `a tiny dot and a small X alternating in strict ABAB order`

**B. 단순 폴리곤:**

- `a single small solid triangle`
- `a single small solid square`
- `a single small solid diamond`
- `a single small hexagon outline`

**C. 단순 곡선:**

- `a single small filled circle`
- `a single small semicircle`
- `a single small vertical capsule shape`

**D. 단순 장식 (선택):**

- `a single small quatrefoil four-petal shape`

> ⚠️ **여기 있는 12개만 쓰세요.** 세이가이하·테셀레이션·중첩 라인·스트라이프 필 육각 같은 복잡한 모티프는 미드저니가 격자를 못 지켜요. 더 다양한 결과를 원하면 **모티프는 고정하고 렌더링·컬러·배치를 바꾸세요.**
>
> 💡 **모티프 1종 원칙.** 점·X ABAB 교차만 예외적으로 허용. 그 외엔 단일 모티프 반복.
>

**2. `{rendering}` — 렌더링 4종**

**① 모노라인 (Monoline):**
- `rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill`

**② 플랫 컬러 블록 (Flat block):**
- `rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture`

**③ 스티플 그레인 (Stipple grain):**
- `rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel`

**④ 아웃라인 + 대비 필 (Outline + fill):**
- `rendered with medium-weight crisp outlines and a contrasting flat fill color inside`

> 💡 **스트라이프 필·크로스해치 같은 복잡한 내부 필은 뺐어요.** 미드저니가 내부 패턴까지 규칙적으로 그리질 못해요.
>

**3. `{layout}` — 여유 있는 정형 격자 5종**

**모두 "모티프가 서로 닿지 않는 듬성한 배치" 예요.**

- `a strict square grid with generous spacing, motifs in straight rows and columns with wide gaps` *(정방형 그리드 — 기본 추천)*
- `a diagonal diamond lattice with wide spacing, motifs placed at every 45-degree grid intersection with room between them` *(대각선 다이아 — 스테이셔너리 클래식)*
- `a half-drop repeat with generous spacing, every other column shifted down by exactly half the motif height` *(하프 드롭)*
- `a half-brick repeat with generous spacing, every other row shifted right by exactly half the motif width` *(하프 브릭)*
- `a triangular lattice with wide spacing, motifs at each node of an equilateral triangle grid` *(삼각 격자)*

> ⚠️ **"edge-to-edge 테셀레이션"·"벌집 밀집"·"스캘럽 스택" 같은 빽빽한 배치는 뺐어요.** 미드저니가 이런 배치에서 모티프 크기를 일정하게 유지 못 해요.
>

**4. `{color_palette}` — 2~3색 제한**

**미니멀 스테이셔너리:**
- `charcoal black on warm off-white`
- `deep navy on cream ivory`
- `slate grey on soft bone white`

**럭셔리·아트데코:**
- `metallic gold on deep navy`
- `metallic gold on charcoal grey`

**빈티지 판화 (스티플 전용):**
- `warm cream stipple on deep navy`
- `ivory dotwork on midnight blue`

**미드센추리·벽지:**
- `powder blue and cream, mid-century palette`
- `terracotta and warm cream, vintage palette`
- `sage green and soft cream, muted palette`
- `dusty blue on muted grey, vintage wallpaper palette`

**5. `{background}` — 배경 톤**

- `deep navy background`
- `charcoal grey background`
- `warm cream paper`
- `ivory cardstock`
- `soft muted grey background`
- `off-white stationery paper`

---

**✏️ 적용 예시 8개 — 단순 모티프 × 다양한 렌더링·격자·컬러**

---

**예시 1 — ✖️ 점·X 교차 × 모노라인 × 대각선 다이아몬드**

```
Seamless repeating pattern of a tiny dot and a small X alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a diagonal diamond lattice with wide spacing, motifs placed at every 45-degree grid intersection with room between them, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, deep navy on cream ivory, on warm cream paper, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**예시 2 — 🔺 삼각형 × 플랫 블록 × 삼각 격자**

```
Seamless repeating pattern of a single small solid triangle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a triangular lattice with wide spacing, motifs at each node of an equilateral triangle grid, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, terracotta and warm cream, vintage palette, on warm cream paper, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 3 — ◐ 반원 × 플랫 블록 × 정방형 그리드**

```
Seamless repeating pattern of a single small semicircle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a strict square grid with generous spacing, motifs in straight rows and columns with wide gaps, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, powder blue and cream, mid-century palette, on ivory cardstock, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**예시 4 — ⬡ 육각 아웃라인 × 모노라인 × 하프드롭**

```
Seamless repeating pattern of a single small hexagon outline, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a half-drop repeat with generous spacing, every other column shifted down by exactly half the motif height, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, metallic gold on charcoal grey, on charcoal grey background, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 140 --tile
```

---

**예시 5 — ⬭ 캡슐 × 스티플 그레인 × 하프드롭**

```
Seamless repeating pattern of a single small vertical capsule shape, rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel, arranged in a half-drop repeat with generous spacing, every other column shifted down by exactly half the motif height, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, warm cream stipple on deep navy, on deep navy background, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 280 --tile
```

---

**예시 6 — ✦ 쿼트리폴 × 아웃라인 + 필 × 대각선 다이아몬드**

```
Seamless repeating pattern of a single small quatrefoil four-petal shape, rendered with medium-weight crisp outlines and a contrasting flat fill color inside, arranged in a diagonal diamond lattice with wide spacing, motifs placed at every 45-degree grid intersection with room between them, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, dusty blue on muted grey, vintage wallpaper palette, on soft muted grey background, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 7 — ⚫ 원 × 플랫 블록 × 하프브릭**

```
Seamless repeating pattern of a single small filled circle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a half-brick repeat with generous spacing, every other row shifted right by exactly half the motif width, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, sage green and soft cream, muted palette, on warm cream paper, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 8 — ➕ 십자 × 모노라인 × 정방형 그리드**

```
Seamless repeating pattern of a single small plus sign cross, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a strict square grid with generous spacing, motifs in straight rows and columns with wide gaps, small motif with generous uniform spacing and lots of negative space between motifs, every motif identical in size shape and orientation, mathematically precise repeat, charcoal black on warm off-white, on off-white stationery paper, flat top-down view, minimalist airy composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `{motif}` 고정 + `{rendering}` 변경 | 같은 기하로 4가지 분위기 (라인·블록·스티플·아웃라인) |
| `{rendering}` 고정 + `{motif}` 변경 | 같은 질감의 기하 컬렉션 (예: 전부 스티플 그레인) |
| `{layout}` 변경 | 그리드·다이아·하프드롭·삼각 변주 |
| `{color_palette}` 변경 | 동일 기하로 4분위기 버전 |
| `generous spacing` → `very wide spacing` | 더 듬성듬성, 미니멀 극대화 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

**⚠️ 핵심 팁 5가지**

1. **모티프는 무조건 단순하게.** 위 12개 목록 밖으로 나가지 마세요. 복잡해질수록 미드저니가 격자를 못 지켜요.
2. **`small motif + generous uniform spacing + lots of negative space`** — 이 3종 키워드를 반드시 넣어야 빽빽함을 막을 수 있어요.
3. **규칙성 키워드 필수.** `strict`, `mathematically precise repeat`, `identical in size shape and orientation`, `no variation in motif placement` — 빠지면 배치 흐트러짐.
4. **테셀레이션·벌집·스캘럽은 금지.** edge-to-edge 밀집 배치는 미드저니가 실패해요. 반드시 "여백이 있는" 격자(square / diamond / half-drop / half-brick / triangular)만 쓰세요.
5. **한 번에 성공 어려움.** 4~8회 재생성 각오. 마음에 드는 컷에서 `--seed` 를 고정해 시리즈화하세요.

---

**✅ 시리즈 만드는 추천 흐름**

1. **렌더링 하나** 선택 (예: 스티플 그레인).
2. 같은 렌더링 × 같은 팔레트 × 같은 레이아웃 밑에 **모티프만 4~6종** 변주 (원·반원·삼각·사각·다이아·캡슐).
3. `--seed [번호]` 고정으로 선 두께·그레인 밀도 일관성 유지.
4. 컬렉션 팔레트는 한 가지로 통일.

> 💡 **상시판매형 추천 조합.**
> ① 스티플 네이비·크림 4종 (원·반원·캡슐·다이아) — 럭셔리 박스·벽지.
> ② 플랫블록 미드센추리 4종 (삼각·사각·반원·원) — 벽지·쿠션.
> ③ 모노라인 골드 아트데코 4종 (점X·육각·다이아·십자) — 청첩장·호텔 어메니티.
> ④ 아웃라인+필 파스텔 4종 (쿼트리폴·원·반원·사각) — 빈티지 벽지·스테이셔너리.
>
