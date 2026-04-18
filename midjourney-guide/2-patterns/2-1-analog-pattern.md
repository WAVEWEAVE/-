# 2-1) 아날로그 패턴 — 큼직한 기하 × 지정 그리드 (3×3 / 4×4 / 5×5)

> **큼직한 기하 모티프를 타일 한 장에 정확히 몇 × 몇 개 배치할지 숫자로 지정**해 반복시키는 seamless 패턴 프롬프트입니다. `3×3` 은 큰 그래픽 블록, `4×4` 는 밸런스, `5×5` 는 세밀한 반복 — 숫자를 명시하면 미드저니가 크기·간격을 흔들지 않아요. 스테이셔너리·벽지·럭셔리 패키지에 바로 써요.

---

**📌 이 프롬프트는 어떤 용도인가요?**

**큼직한 단순 기하 모티프**를 **지정된 행·열 개수**로 타일에 배치하는 프롬프트예요. 작게 흩뿌리는 게 아니라, 모티프 하나하나가 **잘 보이는 크기**로 반복돼요.

이런 데 쓸 수 있어요:

- 럭셔리 박스·쇼핑백 큰 면적 surface
- 벽지·쿠션·러그 (모티프가 확실히 보임)
- Spoonflower / Redbubble 원단
- 세라믹 타일·바닥재
- 목업 / 웹 히어로 배경
- 명함 뒷면·청첩장 포인트 배경

> ⚠️ **그리드 카운트를 숫자로 박는 게 핵심.** "small motif" 같은 모호한 표현 대신 **`a 3 by 3 grid` / `a 4 by 4 grid`** 로 직접 지정하면 미드저니가 모티프 크기·간격을 일정하게 유지해요. 3×3 = 큼직 / 4×4 = 기본 / 5×5 = 세밀 / 6×6 이상은 비추 (규칙 무너짐).
>

---

**🚀 빠른 시작**

1. 그리드 카운트 결정 (`3×3`·`4×4`·`5×5` 중 하나).
2. 모티프 하나 선택 (12개 목록).
3. 렌더링 하나 선택 (4종).
4. 격자 종류 선택 (5종).
5. 컬러·배경 조합 → 프롬프트 복사 → 미드저니.

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern arranged as {grid_count} of {motif}, {rendering}, {layout_type}, each motif large and clearly visible, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, on {background}, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

> 💡 **`{grid_count} of {motif}` 구문이 핵심이에요.** 예: `a 3 by 3 grid of large circles` — 이게 미드저니에게 "정확히 9개" 라고 알려줘요.
>

---

**⚙️ 옵션 파라미터**

| **파라미터** | **권장값** | **메모** |
| --- | --- | --- |
| `--ar` | `1:1` | 타일은 반드시 정사각형 |
| `--s` | `100`~`300` | 모노라인 낮게 / 스티플 높게 |
| `--tile` | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본) | **절대 올리지 말 것** |

---

**📌 변수 5개 — 모두 필수**

**1. `{grid_count}` — 타일 안에 몇 × 몇?**

| **카운트** | **프롬프트 표현** | **인상** |
| --- | --- | --- |
| **3 × 3 (9개)** | `a large 3 by 3 grid` | **큼직·그래픽·포인트 배경** (박스·포스터·쿠션) |
| **4 × 4 (16개)** | `a clear 4 by 4 grid` | **밸런스·스테이셔너리·벽지 기본** |
| **5 × 5 (25개)** | `a precise 5 by 5 grid` | **세밀·리넨·소품 surface** |

> 💡 **처음이라면 4×4 로 시작하세요.** 안정적이고 어떤 모티프에도 잘 맞아요. 큼직한 효과를 극대화하려면 3×3.
>
> ⚠️ **6×6 이상은 비추.** 미드저니가 규칙성을 못 지켜요.
>

**2. `{motif}` — 단순 기하 모티프 12종**

**A. 점·마크 (극도로 단순 — 3×3 에는 부적합, 4×4·5×5 권장):**

- `a single tiny filled dot`
- `a single small X mark`
- `a single small plus sign cross`
- `a tiny dot and a small X alternating in strict ABAB order`

**B. 단순 폴리곤 (3×3 에 강력):**

- `a single large solid triangle`
- `a single large solid square`
- `a single large solid diamond`
- `a single large hexagon outline`

**C. 단순 곡선 (3×3 에 강력):**

- `a single large filled circle`
- `a single large semicircle`
- `a single large vertical capsule shape`

**D. 단순 장식:**

- `a single large quatrefoil four-petal shape`

> 💡 **그리드 카운트에 맞춰 크기 단어 조절.**
>
> - 3×3 → `large` 로 기술 (예: `a single large circle`)
> - 4×4 → `medium` 또는 그냥 크기 언급 없이
> - 5×5 → `small` 로 기술
>
> 💡 **모티프 1종 원칙.** 점·X ABAB 교차만 예외. 그 외엔 단일 모티프 반복.
>

**3. `{rendering}` — 렌더링 4종**

**① 모노라인:**
- `rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill`

**② 플랫 컬러 블록:**
- `rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture`

**③ 스티플 그레인:**
- `rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel`

**④ 아웃라인 + 대비 필:**
- `rendered with medium-weight crisp outlines and a contrasting flat fill color inside`

**4. `{layout_type}` — 격자 종류 5종**

(그리드 카운트와 결합해서 쓰는 배치 방식)

- `arranged in a strict square grid layout, motifs in perfectly straight rows and columns` *(정방형 — 기본)*
- `arranged in a diagonal diamond lattice, rows rotated 45 degrees` *(대각선 다이아)*
- `arranged in a half-drop repeat, every other column shifted down by exactly half the motif height` *(하프 드롭)*
- `arranged in a half-brick repeat, every other row shifted right by exactly half the motif width` *(하프 브릭)*
- `arranged in a triangular lattice layout` *(삼각 격자)*

**5. `{color_palette}` 및 `{background}` — 컬러·배경**

**컬러 팔레트 (2~3색 제한):**

미니멀 스테이셔너리:
- `charcoal black on warm off-white`
- `deep navy on cream ivory`

럭셔리·아트데코:
- `metallic gold on deep navy`
- `metallic gold on charcoal grey`

빈티지 스티플:
- `warm cream stipple on deep navy`
- `ivory dotwork on midnight blue`

미드센추리·벽지:
- `powder blue and cream, mid-century palette`
- `terracotta and warm cream, vintage palette`
- `sage green and soft cream, muted palette`
- `dusty blue on muted grey, vintage wallpaper palette`

**배경:**

- `deep navy background` / `charcoal grey background` / `midnight blue background`
- `warm cream paper` / `ivory cardstock` / `off-white stationery paper`
- `soft muted grey background`

---

**✏️ 적용 예시 8개 — 그리드 카운트·모티프·렌더링 다양하게**

---

**예시 1 — 🔵 큼직한 원 3×3 × 플랫 블록 × 정방형 그리드**

```
Seamless repeating pattern arranged as a large 3 by 3 grid of a single large filled circle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a strict square grid layout, motifs in perfectly straight rows and columns, each motif large and clearly visible, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, powder blue and cream, mid-century palette, on ivory cardstock, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 2 — 🔺 삼각형 3×3 × 플랫 블록 × 삼각 격자**

```
Seamless repeating pattern arranged as a large 3 by 3 grid of a single large solid triangle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a triangular lattice layout, each motif large and clearly visible, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, terracotta and warm cream, vintage palette, on warm cream paper, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 3 — ◐ 반원 4×4 × 플랫 블록 × 정방형 그리드 (미드센추리)**

```
Seamless repeating pattern arranged as a clear 4 by 4 grid of a single large semicircle, rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture, arranged in a strict square grid layout, motifs in perfectly straight rows and columns, each motif large and clearly visible, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, sage green and soft cream, muted palette, on warm cream paper, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**예시 4 — ⬡ 육각 아웃라인 4×4 × 모노라인 × 하프드롭**

```
Seamless repeating pattern arranged as a clear 4 by 4 grid of a single large hexagon outline, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a half-drop repeat, every other column shifted down by exactly half the motif height, each motif large and clearly visible, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, metallic gold on charcoal grey, on charcoal grey background, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 140 --tile
```

---

**예시 5 — ⬭ 캡슐 4×4 × 스티플 그레인 × 하프드롭**

```
Seamless repeating pattern arranged as a clear 4 by 4 grid of a single large vertical capsule shape, rendered with dense pointillism stipple dot fill, halftone grain texture, vintage engraving feel, arranged in a half-drop repeat, every other column shifted down by exactly half the motif height, each motif large and clearly visible, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream stipple on deep navy, on deep navy background, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 280 --tile
```

---

**예시 6 — ✦ 쿼트리폴 4×4 × 아웃라인 + 필 × 대각선 다이아몬드**

```
Seamless repeating pattern arranged as a clear 4 by 4 grid of a single large quatrefoil four-petal shape, rendered with medium-weight crisp outlines and a contrasting flat fill color inside, arranged in a diagonal diamond lattice, rows rotated 45 degrees, each motif large and clearly visible, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty blue on muted grey, vintage wallpaper palette, on soft muted grey background, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 7 — ✖️ 점·X 5×5 × 모노라인 × 대각선 다이아몬드 (스테이셔너리)**

```
Seamless repeating pattern arranged as a precise 5 by 5 grid of a tiny dot and a small X alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a diagonal diamond lattice, rows rotated 45 degrees, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, deep navy on cream ivory, on warm cream paper, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**예시 8 — ➕ 십자 5×5 × 모노라인 × 정방형 그리드**

```
Seamless repeating pattern arranged as a precise 5 by 5 grid of a single small plus sign cross, rendered in ultra-thin crisp hairline strokes, single uniform line weight, no fill, arranged in a strict square grid layout, motifs in perfectly straight rows and columns, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, charcoal black on warm off-white, on off-white stationery paper, flat top-down view, bold clean graphic composition, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**🔧 변주 팁**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| `3×3 → 4×4 → 5×5` | 큼직 → 밸런스 → 세밀 (같은 모티프로 3버전) |
| `{motif}` 고정 + `{rendering}` 변경 | 같은 기하로 4가지 분위기 |
| `{rendering}` 고정 + `{motif}` 변경 | 같은 질감의 기하 컬렉션 |
| `{layout_type}` 변경 | 정방형 → 다이아 → 하프드롭 변주 |
| 큰 모티프 + 3×3 조합 | 포스터·쿠션·박스 포인트 |
| 작은 모티프 + 5×5 조합 | 스테이셔너리·리넨 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

**⚠️ 핵심 팁 5가지**

1. **그리드 카운트를 숫자로 박으세요.** `a 3 by 3 grid / a 4 by 4 grid / a 5 by 5 grid` — 이 구문이 미드저니에게 모티프 개수를 강제해요. 숫자 없이 "small" / "scattered" 쓰면 흐트러져요.
2. **3×3 = 큼직 / 4×4 = 기본 / 5×5 = 세밀 / 6×6 이상 금지.** 카운트가 올라갈수록 모티프는 작게 표현되고, 규칙성은 떨어져요.
3. **모티프 크기 단어를 카운트에 맞춰.** 3×3 엔 `large`, 4×4 엔 표기 없이 / `medium`, 5×5 엔 `small / tiny`.
4. **규칙성 키워드 필수.** `strict`, `mathematically precise repeat`, `identical in size shape and orientation`, `no variation in motif placement` — 빠지면 망가짐.
5. **한 번에 성공 어려움.** 4~8회 재생성 각오. 마음에 드는 컷에서 `--seed` 고정해 시리즈화.

---

**✅ 시리즈 만드는 추천 흐름**

1. **그리드 카운트 하나** 선택 (예: 4×4 로 통일).
2. 같은 카운트 × 같은 렌더링 × 같은 팔레트 밑에 **모티프 4~6종** 변주 (원·반원·삼각·사각·다이아·캡슐).
3. `--seed [번호]` 고정으로 선 두께·그레인 일관성 유지.
4. 제품 용도에 맞춰 **카운트만 바꿔 3버전 제작** (3×3 쿠션 / 4×4 벽지 / 5×5 원단).

> 💡 **상시판매형 추천 조합.**
> ① 3×3 플랫블록 미드센추리 4종 (원·반원·삼각·사각) — 쿠션·포스터.
> ② 4×4 스티플 네이비·크림 4종 (원·반원·캡슐·다이아) — 럭셔리 박스·벽지.
> ③ 4×4 모노라인 골드 아트데코 4종 (육각·다이아·쿼트리폴·원) — 청첩장·호텔.
> ④ 5×5 스테이셔너리 4종 (점X·십자·다이아·원) — 명함·레터헤드.
>
