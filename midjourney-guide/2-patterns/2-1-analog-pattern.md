# 2-1) 아날로그 패턴 — 4가지 템플릿 × 밝은 팔레트 (Classic Geometric Seamless)

> **레퍼런스 기반 4가지 템플릿 안에서만 변형**하는 클래식 기하 패턴 프롬프트입니다. 점·X 스테이셔너리(A) / 3색 스타 벽지(B) / 쿼트리폴 바닥타일(C) / 아이소 3D 큐브(D) — 이 네 가지 공식에서 벗어나지 않고, **모든 컬러는 밝고 환한 톤**으로 통일했어요. 검증된 규칙성 + 상쾌한 분위기.

---

**📌 이 프롬프트는 어떤 용도인가요?**

**4가지 검증된 템플릿** 을 바로 복사해서 쓰거나, 각 템플릿 안에서 **모티프·컬러만** 변주해서 시리즈를 만드는 프롬프트예요. 무작위로 새 모티프를 추가하지 않아요 — A~D 공식 안에서만 움직입니다.

이런 데 쓸 수 있어요:

- 명함·청첩장·레터헤드 배경
- Spoonflower / Redbubble 원단·벽지
- 세라믹 타일·바닥재
- 카페·베이커리·리빙 벽지·쿠션
- 럭셔리 박스·쇼핑백

> ⚠️ **4 템플릿 외부 금지.** 캡슐·원·반원·삼각·사각 같은 단순 도형은 이 가이드에서 다루지 않아요. 모티프는 반드시 A(점·마크) · B(스타) · C(쿼트리폴·로제트) · D(아이소 3D) 중 하나.
>
> ⚠️ **컬러는 밝은 톤만.** 딥 네이비·차콜·블랙·딥 티얼·딥 버건디 금지. 크림·민트·파우더 블루·더스티 핑크·버터 옐로우·피치·라벤더 같은 **밝고 환한 톤** 전용이에요.
>

---

**🎯 4가지 레퍼런스 템플릿 (바로 복사 / 밝은 버전)**

---

**템플릿 A — 📐 점·X 스테이셔너리**

```
Seamless repeating pattern of a tiny filled square and a small X mark alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, arranged as a precise 6 by 6 diagonal diamond lattice, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage green marks on warm cream, on warm cream background, flat top-down view, minimalist classic stationery design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

**템플릿 B — ✦ 3색 8포인트 스타 벽지**

```
Seamless repeating pattern of a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees, with a tiny center dot, rendered as a flat solid color silhouette with a slightly darker inner star layered on top, arranged as a clear 3 by 4 half-drop repeat, stars rotating through three colors in strict ABCABC order (dusty pink, butter yellow, and powder blue), every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, on soft sage cream background, flat top-down view, bright vintage wallpaper design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

**템플릿 C — ✿ 쿼트리폴 바닥타일**

```
Seamless repeating pattern of a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel, rendered as a solid flat color silhouette with crisp vector edges, no outline, arranged as a clear 5 by 5 strict square grid with motifs touching at corners, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream motifs on soft mint background, on soft mint background, flat top-down view, bright mid-century bistro tile design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

**템플릿 D — 🟥 아이소 3D 큐브**

```
Seamless repeating pattern of a single isometric 3D cube with three visible faces (top, left, right) each rendered in a distinct flat color tone (lightest on top, medium on right, slightly deeper on left), crisp vector edges, no outlines, arranged as an isometric tessellation where cubes tile edge-to-edge creating a continuous 3D illusion, every cube identical in size shape and orientation, mathematically precise repeat, butter cream lightest face, peach medium face, coral pink deeper face, on warm cream background, flat top-down view, bright classic isometric geometric design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**🚀 모듈형 변수 (4 템플릿 내부 변주만)**

---

**📐 마스터 프롬프트 본문**

```
Seamless repeating pattern of {motif}, {rendering}, arranged as a {grid_count} {layout}, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, {color_palette}, on {background}, flat top-down view, bright classic surface design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**⚙️ 옵션 파라미터**

| **파라미터** | **권장값** | **메모** |
| --- | --- | --- |
| `--ar` | `1:1` | 타일은 반드시 정사각형 |
| `--s` | `120`~`220` | 모노라인 낮게 / 3D·레이어드 높게 |
| `--tile` | **필수** | 빼면 seamless 안 됨 |
| `--chaos` | `0` (기본) | **절대 올리지 말 것** |

---

**📌 변수 5개**

**1. `{motif}` — 4 템플릿별 모티프만**

**A 계열 — 스테이셔너리 미니 마크:**
- `a single small X mark`
- `a single tiny filled square`
- `a single small plus sign cross`
- `a tiny dot and a small X alternating in strict ABAB order`
- `a tiny filled square and a small X alternating in strict ABAB order`

**B 계열 — 볼드 스타:**
- `a single bold 4-point star`
- `a single bold 5-point star`
- `a single bold 6-point star`
- `a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees, with a tiny center dot`

**C 계열 — 페탈·로제트:**
- `a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel`
- `a single bold trefoil formed by three rounded petals`
- `a single bold 6-petal rosette flower`
- `a single bold 8-petal rosette flower`
- `a single bold four-leaf clover shape`

**D 계열 — 아이소 3D:**
- `a single isometric 3D cube with three visible faces in three distinct flat color tones`
- `a single isometric 3D stacked double-cube with three visible faces`
- `a single isometric 3D hexagonal prism with three visible faces`

> ⚠️ **이 20개 외부 금지.** 캡슐·원·반원·삼각·사각·육각 같은 단독 도형은 4 템플릿 어디에도 속하지 않아요.
>

**2. `{rendering}` — 템플릿별 렌더링**

**① 모노라인 + 점선 격자 (템플릿 A 전용):**
- `rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs`

**② 플랫 실루엣 + 이너 레이어 (템플릿 B 전용):**
- `rendered as a flat solid color silhouette with a slightly darker inner layer for depth`

**③ 플랫 실루엣 (템플릿 C 전용):**
- `rendered as a solid flat color silhouette with crisp vector edges, no outline, no texture`

**④ 아이소 3D 3톤 (템플릿 D 전용):**
- `rendered as an isometric 3D shape with three flat color tones for top, left, and right faces`

**3. `{grid_count}` — 템플릿별 카운트**

| **템플릿** | **권장 카운트** | **프롬프트** |
| --- | --- | --- |
| **A** (점·X) | 5~6 칸 | `a precise 6 by 6` |
| **B** (스타) | 3~4 칸 | `a clear 3 by 4` |
| **C** (쿼트리폴) | 4~5 칸 | `a clear 5 by 5` |
| **D** (3D 큐브) | 4~5 칸 | `a clear 4 by 5 isometric` |

**4. `{layout}` — 템플릿별 배치**

- `diagonal diamond lattice, rows rotated 45 degrees` *(A 전용)*
- `half-drop repeat, every other column shifted down by exactly half the motif height` *(B 전용)*
- `strict square grid with motifs touching at corners` *(C 전용)*
- `isometric tessellation where shapes tile edge-to-edge creating a continuous 3D illusion` *(D 전용)*

**5. `{color_palette}` 및 `{background}` — 밝은 톤만**

**A 계열 — 2색 마크 (밝은):**
- `soft sage green marks on warm cream`
- `dusty pink marks on ivory`
- `powder blue marks on soft bone white`
- `butter yellow marks on cream`
- `soft coral marks on warm off-white`

**B 계열 — ABCABC 3색 로테이션 (밝은):**
- `rotating through three colors in strict ABCABC order (dusty pink, butter yellow, and powder blue)`
- `rotating through three colors in strict ABCABC order (soft sage, dusty pink, and cream)`
- `rotating through three colors in strict ABCABC order (lavender, peach, and mint)`
- `rotating through three colors in strict ABCABC order (coral, lemon, and sky blue)`
- `rotating through three colors in strict ABCABC order (butter yellow, sage green, and terracotta)`

**C 계열 — 2색 듀오톤 (밝은):**
- `warm cream motifs on soft mint background`
- `dusty pink motifs on cream background`
- `butter yellow motifs on soft sage background`
- `coral motifs on powder blue background`
- `lavender motifs on warm ivory background`

**D 계열 — 아이소 3톤 (밝은):**
- `butter cream lightest face, peach medium face, coral pink deeper face`
- `mint lightest face, soft sage medium face, sage green deeper face`
- `ivory lightest face, powder blue medium face, dusty blue deeper face`
- `cream lightest face, butter yellow medium face, mustard deeper face`
- `soft lavender lightest face, dusty lilac medium face, plum deeper face`

**배경 (전부 밝게):**
- `warm cream background`
- `ivory cardstock background`
- `soft mint background`
- `soft sage cream background`
- `powder blue background`
- `dusty peach background`
- `soft butter yellow background`
- `warm off-white background`

---

**✏️ 적용 예시 8개 — 4 템플릿 × 2 변형**

---

**예시 1 — 📐 템플릿 A 변형 : 점·X 스테이셔너리 (세이지)**

```
Seamless repeating pattern of a tiny filled square and a small X mark alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, arranged as a precise 6 by 6 diagonal diamond lattice, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, soft sage green marks on warm cream, on warm cream background, flat top-down view, minimalist classic stationery design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**예시 2 — 📐 템플릿 A 변형 : 점·X 스테이셔너리 (더스티 핑크)**

```
Seamless repeating pattern of a tiny dot and a small X alternating in strict ABAB order, rendered in ultra-thin crisp hairline strokes with faint dashed connecting lines between motifs, arranged as a precise 5 by 5 diagonal diamond lattice, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, dusty pink marks on ivory, on ivory cardstock background, flat top-down view, minimalist classic stationery design, tileable, no text, no variation in motif placement. --ar 1:1 --s 120 --tile
```

---

**예시 3 — ✦ 템플릿 B 변형 : 3색 8포인트 스타 (핑크·옐로우·블루)**

```
Seamless repeating pattern of a single bold 8-point compass star formed by two overlapping 4-point stars rotated 45 degrees, with a tiny center dot, rendered as a flat solid color silhouette with a slightly darker inner star layered on top, arranged as a clear 3 by 4 half-drop repeat, stars rotating through three colors in strict ABCABC order (dusty pink, butter yellow, and powder blue), every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, on soft sage cream background, flat top-down view, bright vintage wallpaper design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 4 — ✦ 템플릿 B 변형 : 6포인트 스타 (라벤더·피치·민트)**

```
Seamless repeating pattern of a single bold 6-point star, rendered as a flat solid color silhouette with a slightly darker inner layer for depth, arranged as a clear 4 by 4 half-drop repeat, stars rotating through three colors in strict ABCABC order (lavender, peach, and mint), every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, on warm cream background, flat top-down view, bright vintage wallpaper design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 5 — ✿ 템플릿 C 변형 : 쿼트리폴 (크림 on 민트)**

```
Seamless repeating pattern of a single bold quatrefoil formed by four curved pointed petals radiating outward like a pinwheel, rendered as a solid flat color silhouette with crisp vector edges, no outline, arranged as a clear 5 by 5 strict square grid with motifs touching at corners, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, warm cream motifs on soft mint background, on soft mint background, flat top-down view, bright mid-century bistro tile design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 6 — ✿ 템플릿 C 변형 : 6-Petal 로제트 (코랄 on 파우더 블루)**

```
Seamless repeating pattern of a single bold 6-petal rosette flower, rendered as a solid flat color silhouette with crisp vector edges, no outline, arranged as a clear 4 by 4 strict square grid with motifs touching at corners, every motif identical in size shape and orientation, mathematically precise repeat with uniform spacing, coral motifs on powder blue background, on powder blue background, flat top-down view, bright mid-century bistro tile design, tileable, no text, no variation in motif placement. --ar 1:1 --s 180 --tile
```

---

**예시 7 — 🟥 템플릿 D 변형 : 아이소 큐브 (핑크 3톤)**

```
Seamless repeating pattern of a single isometric 3D cube with three visible faces, rendered as an isometric 3D shape with three flat color tones for top, left, and right faces, arranged in an isometric tessellation where shapes tile edge-to-edge creating a continuous 3D illusion, every cube identical in size shape and orientation, mathematically precise repeat, butter cream lightest face, peach medium face, coral pink deeper face, on warm cream background, flat top-down view, bright classic isometric geometric design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**예시 8 — 🟥 템플릿 D 변형 : 아이소 육각 프리즘 (민트 3톤)**

```
Seamless repeating pattern of a single isometric 3D hexagonal prism with three visible faces, rendered as an isometric 3D shape with three flat color tones for top, left, and right faces, arranged in an isometric tessellation where shapes tile edge-to-edge creating a continuous 3D illusion, every prism identical in size shape and orientation, mathematically precise repeat, mint lightest face, soft sage medium face, sage green deeper face, on warm cream background, flat top-down view, bright classic isometric geometric design, tileable, no text, no variation in motif placement. --ar 1:1 --s 200 --tile
```

---

**🔧 변주 팁 (4 템플릿 내부)**

| **이걸 바꾸시면** | **효과** |
| --- | --- |
| 템플릿 A 에서 마크 종류·2색 팔레트만 변경 | 스테이셔너리 컬러 시리즈 |
| 템플릿 B 에서 스타 포인트(4/5/6/8)·ABCABC 팔레트 변경 | 빈티지 벽지 시리즈 |
| 템플릿 C 에서 로제트 페탈수(3/4/6/8)·듀오톤 변경 | 바닥타일 컬렉션 |
| 템플릿 D 에서 3D 형태(큐브·스택·프리즘)·3톤 변경 | 아이소 3D 시리즈 |
| `{grid_count}` 숫자 조정 | 같은 템플릿 내 크기 변주 |
| `--tile` 제거 | seamless 실패 (절대 금지) |
| `--chaos` 상승 | 규칙성 붕괴 (절대 금지) |

---

**⚠️ 핵심 팁 5가지**

1. **4 템플릿 외부로 나가지 마세요.** 모티프는 A(마크) / B(스타) / C(로제트) / D(아이소 3D) 중 하나. 다른 도형 추가하면 규칙성 무너져요.
2. **컬러는 전부 밝은 톤.** 딥 네이비·차콜·블랙·딥 버건디 같은 어두운 톤 금지. 크림·민트·파우더 블루·더스티 핑크·버터 옐로우·피치·라벤더·코랄·세이지 전용.
3. **템플릿별 렌더링 고정.** A = 모노라인+점선, B = 이너 레이어, C = 플랫 실루엣, D = 3톤 아이소. 섞으면 템플릿이 무너져요.
4. **규칙성 키워드 필수.** `strict`, `mathematically precise repeat`, `identical in size shape and orientation`, `no variation in motif placement`.
5. **한 번에 성공 어려움.** 4~8회 재생성 각오. 마음에 드는 컷에서 `--seed` 고정해 시리즈화.

---

**✅ 시리즈 만드는 추천 흐름**

1. **4 템플릿 중 하나** 메인 선택.
2. 그 템플릿의 **모티프·컬러만 4~6가지로 변주** (외부 템플릿은 섞지 않음).
3. `--seed [번호]` 고정으로 질감·톤 일관성 유지.
4. 컬렉션 팔레트는 한 계열로 통일 (파스텔 / 보타니컬 / 썸머 등).

> 💡 **상시판매형 추천 조합 (전부 밝은 톤).**
> ① 템플릿 A 파스텔 4색 (세이지·핑크·블루·옐로우) — 명함·레터헤드.
> ② 템플릿 B 3색 로테이션 4종 (핑크옐로우블루 / 라벤더피치민트 / 코랄레몬하늘 / 세이지핑크크림) — 빈티지 벽지 컬렉션.
> ③ 템플릿 C 듀오톤 4종 (쿼트리폴·트레포일·6-Petal·클로버) — 바닥타일·카페 인테리어.
> ④ 템플릿 D 3톤 아이소 4종 (핑크·민트·블루·옐로우 그라데이션) — 럭셔리 박스·웹 배경.
>
