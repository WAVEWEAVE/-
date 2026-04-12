# POD 공감 유머 밈 — 미드저니 프롬프트 가이드 (비주얼 온리)

> **그림만으로 "이거 나잖아"를 끌어내는** 공감형 유머 일러스트 프롬프트입니다.
> 텍스트 없이 **표정·상황·캐릭터만으로** 유머가 전달되는 POD 디자인 소스에 최적화했습니다.
> T셔츠, 머그컵, 에코백, 스티커 등 전 POD 상품에 바로 사용 가능합니다.

---

## 📌 이 프롬프트는 어떤 용도인가요?

**텍스트 없이 그림만으로 웃기는** 유머 일러스트를 만드는 프롬프트예요.

이런 데 쓸 수 있어요:
- POD T셔츠 · 머그컵 · 에코백 · 스티커 메인 일러스트
- Redbubble / Etsy / 마플샵 업로드 소스
- 텍스트를 나중에 추가하거나 아예 안 써도 완성되는 디자인
- 공감 동물 캐릭터 시리즈 굿즈

> ⚠️ **"meme" "funny face" 단어를 쓰지 마세요.**
> `"meme"` 은 저작권 있는 실제 밈 이미지를 생성합니다.
> `"funny face"` 는 실제 사람 얼굴이 나옵니다.
> 이 프롬프트는 `humorous illustration` + `exaggerated cartoon character` 로 그 함정을 피했습니다.

> ⚠️ **비주얼 온리 핵심 원칙**
> 유머가 그림만으로 읽혀야 합니다.
> 상황의 과장, 표정의 극단, 캐릭터의 아이덴티티로 유머를 전달하세요.
> "커피컵에 매달리는 작은 캐릭터"는 설명 없이도 공감이 됩니다.

---

## 🚀 빠른 시작

1. 아래 예시 8개 중 내 타겟 고객과 맞는 걸 고르세요.
2. **"완성 프롬프트"** 를 통째로 복사하세요.
3. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

## 📐 마스터 프롬프트 본문

```
A humorous illustration of {meme_scene}, drawn in {art_style}, with {color_scheme} on a {background} background, {composition}. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 300
```

---

## ⚙️ 옵션 파라미터

| 파라미터 | 권장값 | 메모 |
| --- | --- | --- |
| `--ar` | `1:1` 정방형 (기본) / `16:9` 2컷 대비 구도 | |
| `--v` | `8` | 고정 |
| `--style` | `raw` | 고정. 일러스트 충실도 필수 |
| `--s` | `250` 권장 / `350` 표정·과장 강조 / `150` 절제 | 유머 일러스트는 300~350이 표정이 잘 살아요 |

---

## 📌 변수 4개 — 모두 필수

### 1. `{meme_scene}` — 어떤 상황인가요?

**비주얼 온리의 핵심 변수.** 텍스트 없이 읽히려면 상황 묘사가 매우 구체적이어야 합니다.

**공감 포인트별 예시:**

**☕ 커피 · 에너지 의존**
- `a tiny cartoon character desperately clinging to an oversized coffee cup twice their height, eyes wide with desperate gratitude`
- `a cartoon character with an empty expression staring blankly into a coffee mug, one hand already reaching for a second cup`

**😴 수면 · 피로 공감**
- `a cartoon character enthusiastically punching an alarm clock that woke them up, mid-swing with gleeful determination`
- `a cartoon character melting off a couch like a liquid puddle, boneless and completely limp, with heavy-lidded eyes`

**🐱🐶 반려동물 권력 역학**
- `a tiny cartoon human bowing deeply while serving gourmet food to a large imperious cat sitting on an oversized throne, the cat looking completely unimpressed`
- `a cartoon character being dragged horizontally across the floor by an enormous excited dog on a leash, body stretched flat behind the dog`

**🦝 카오틱 동물 캐릭터** *(아이덴티티가 곧 유머)*
- `a raccoon character wearing a tiny crown, sitting on a pile of snacks and miscellaneous treasures with a deeply satisfied expression, guarding it all with tiny arms`
- `a round opossum character hanging upside down from a branch with a completely unbothered expression, surrounded by floating stars and chaos`
- `a capybara character sitting perfectly still in the center of utter chaos — things falling around it — with an expression of supreme indifference`

**💤 월요일 · 주말 대비** *(2컷 구도)*
- `two side-by-side panels: left shows a cartoon character on Friday as a sparkling vibrant sun with jazz hands, right shows the exact same character on Monday as a wilted drooping plant with empty eyes`

> 💡 **비주얼 온리 체크리스트**
> - 상황만 봐도 공감이 가나요? → OK
> - 글자가 있어야 웃기나요? → 장면을 더 과장하거나, 캐릭터 아이덴티티를 더 강화하세요
> - 표정이 극단적인가요? → 미드저니는 과장할수록 잘 읽힙니다

---

### 2. `{art_style}` — 어떤 그림체?

- `bold retro cartoon style with thick black outlines and exaggerated expressions, like a 1990s editorial illustration`
- `clean flat vector style with simple geometric shapes and deadpan expression, like a modern infographic character`
- `chunky bold graphic with high-contrast fills and wildly exaggerated proportions, like a vintage punk zine illustration`
- `soft rounded character design with large expressive eyes and subtle blush marks, in a modern wholesome cartoon style`
- `loose sketchy linework with rough texture and imperfect proportions, like a hand-doodled notebook cartoon`

> 💡 **유머 강도 × 그림체 매칭**
> | 유머 강도 | 추천 그림체 |
> |---|---|
> | 강한 과장 · 풍자 | `bold retro cartoon` / `punk zine` |
> | 귀엽고 공감가는 | `wholesome cartoon` / `flat vector` |
> | 카오틱 · 너구리 | `chunky bold graphic` / `sketchy` |
> | 데드판 · 허무 | `clean flat vector` + `deadpan expression` |

---

### 3. `{color_scheme}` — 컬러는?

**2~3색이 POD 인쇄에 최적입니다.** 고대비일수록 썸네일에서 잘 읽혀요.

- `charcoal black and muted mustard yellow`
- `forest green and warm cream with dark outlines`
- `burnt orange and off-white only`
- `deep navy and pale yellow`
- `deep burgundy and pale pink with black outlines`
- `midnight blue and warm cream`
- `matte black and neon lime` *(Gen Z / 다크 유머)*
- `warm terracotta and off-white`

> ⚠️ `"pastel"` 단어 금지 — 인쇄 시 색이 죽습니다.
> `muted` `deep` `warm` `charcoal` 같은 수식어가 훨씬 선명하게 나옵니다.

---

### 4. `{background}` — 배경은?

- `clean white` *(기본 · 배경 제거 후 사용 쉬움)*
- `off-white`
- `warm cream`
- `soft light gray`
- `matte black` *(다크 유머 · 다크 모드 굿즈)*

---

## ✏️ 적용 예시 8개

---

### 예시 1 — ☕ 커피 의존증 (번트오렌지+아이보리)

```
A humorous illustration of a tiny cartoon character desperately clinging to an oversized coffee cup twice their height, eyes wide with desperate gratitude, drawn in bold retro cartoon style with thick black outlines and exaggerated expressions, like a 1990s editorial illustration, with burnt orange and off-white only on a clean white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 300
```

---

### 예시 2 — 😴 알람 격파 (차콜+머스타드)

```
A humorous illustration of a cartoon character enthusiastically punching an alarm clock that woke them up, mid-swing with gleeful determination, still wearing pajamas with wild bedhead hair, drawn in chunky bold graphic with high-contrast fills and wildly exaggerated proportions, like a vintage punk zine illustration, with charcoal black and muted mustard yellow on a clean white background, centered as one large illustration with wide margins. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 350
```

---

### 예시 3 — 🐱 고양이 왕좌 (차콜+테라코타)

```
A humorous illustration of a tiny cartoon human bowing deeply while serving gourmet food on a silver tray to a large imperious cat sitting on an oversized ornate throne, the cat looking completely unimpressed with one paw raised dismissively, drawn in bold retro cartoon style with thick black outlines and exaggerated scale difference, like a 1990s editorial illustration, with charcoal black and warm terracotta on a clean white background, centered as one large illustration filling the frame. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 300
```

---

### 예시 4 — 🦝 너구리 과자 수호자 (포레스트그린+크림)

```
A humorous illustration of a raccoon character wearing a tiny crown, sitting possessively on a pile of snacks and miscellaneous treasures with a deeply satisfied expression, arms spread wide to guard everything, drawn in soft rounded character design with large expressive eyes and subtle blush marks, in a modern wholesome cartoon style, with forest green and warm cream with dark outlines on a clean white background, centered as one large illustration with wide margins. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 300
```

---

### 예시 5 — 🛋️ 소파에 녹아드는 집돌이 (네이비+페일옐로)

```
A humorous illustration of a cartoon character melting off a couch like a liquid puddle, completely boneless and limp, with heavy-lidded blissful eyes, a remote control loosely in one hand, drawn in clean flat vector style with simple geometric shapes and deadpan expression, like a modern infographic character, with deep navy and pale yellow on an off-white background, centered as one large illustration filling the frame. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 250
```

---

### 예시 6 — 😶 카피바라 무관심 (테라코타+크림)

```
A humorous illustration of a round capybara character sitting perfectly still in the center of absolute chaos — objects flying, things falling, a tiny fire in the background — wearing a completely calm and indifferent expression, drawn in chunky bold graphic with high-contrast fills and exaggerated surroundings, like a vintage punk zine illustration, with warm terracotta and off-white on a clean white background, centered as one large illustration with wide margins. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 300
```

---

### 예시 7 — 🐕 강아지한테 끌려가는 집사 (버건디+크림)

```
A humorous illustration of a cartoon character being dragged horizontally across the floor by an enormous excited dog on a leash, the human's body stretched completely flat like a flag behind the sprinting dog, legs trailing in the air, with a resigned but loving expression on their face, drawn in bold retro cartoon style with thick black outlines and exaggerated proportions, with deep burgundy and pale cream on a clean white background, centered as one large illustration. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 1:1 --v 8 --style raw --s 350
```

---

### 예시 8 — 📅 금요일 vs 월요일 대비 (2컷 / 버건디+페일핑크)

```
A humorous illustration of two side-by-side panels: left panel shows a cartoon character on Friday as a sparkling vibrant sun with jazz hands and a glowing halo, right panel shows the exact same character on Monday as a wilted drooping plant in a pot with empty hollow eyes and drooping leaves, drawn in chunky bold graphic with high-contrast fills and exaggerated expressions, like a vintage punk zine illustration, with deep burgundy and pale pink with black outlines on a clean white background, placed side by side with even breathing room. The joke reads entirely from the visual with no text or speech bubbles. Print-ready flat vector graphic, clean edges, no gradients. --ar 16:9 --v 8 --style raw --s 300
```

---

## 🔧 변주 팁

| 이걸 바꾸면 | 효과 |
| --- | --- |
| `{meme_scene}` 만 | 같은 스타일·컬러로 **다른 공감 주제** 시리즈 |
| `{art_style}` 만 | 같은 캐릭터를 `bold retro` → `wholesome` → `sketchy` 버전으로 |
| `{color_scheme}` 만 | 다크 모드: `matte black and neon lime` / 따뜻한: `terracotta and cream` |
| `--ar 1:1 → 16:9` | 2컷 대비 구도 (예시 8처럼) |
| `--s 300 → 400` | 과장이 더 세지고 표정이 극단적으로 |
| `--s 300 → 150` | 더 절제되고 깔끔한 인포그래픽 느낌 |
| `{background}` 를 `matte black` 으로 | 다크 굿즈 라인 |
| `--sref [첫 결과 URL]` 추가 | 캐릭터 여러 포즈를 같은 톤으로 통일할 때 |

---

## ⚠️ 핵심 팁 6가지

1. **"meme" 키워드 절대 금지.** 저작권 있는 실제 밈 캐릭터가 생성됩니다.
2. **"funny face" 금지.** 실제 사람 얼굴이 나옵니다. `exaggerated cartoon character` 로 쓰세요.
3. **상황을 극단적으로 묘사하세요.** 미드저니는 과장이 강할수록 유머가 잘 읽힙니다. "slightly tired"보다 "melting off a couch like a liquid puddle"이 훨씬 잘 나옵니다.
4. **컬러는 2~3색, `pastel` 금지.** 인쇄 시 색이 죽습니다. `muted` `deep` `warm` 으로 쓰세요.
5. **카오틱 동물은 `--s 300~400`.** 너구리·오포섬·카피바라는 스타일라이즈 수치가 높을수록 캐릭터가 살아납니다.
6. **배경은 `clean white`.** 나중에 배경 제거 도구로 투명화하면 모든 상품에 바로 쓸 수 있어요.

---

## ✅ 시리즈 만드는 추천 흐름

1. 예시 하나를 골라 먼저 돌려보세요.
2. 마음에 들면 `{meme_scene}` 만 바꿔서 같은 캐릭터·스타일로 4~5개 시리즈를 만드세요.
3. 첫 결과의 `-seed` 값을 다음 프롬프트에 붙이면 캐릭터 톤이 통일됩니다.
4. 통일된 시리즈 3개 이상 완성 후 `--sref [첫 결과 URL]` 로 스타일을 고정하세요.

> 💡 **상시판매형 추천 순서**
> 1. **카오틱 동물 캐릭터** (너구리·카피바라·오포섬) — 텍스트 없이 가장 잘 팔리는 유형
> 2. **반려동물 권력 역학** (고양이 왕좌·강아지 집사) — 특정 견종/묘종으로 세분화하면 더 강해짐
> 3. **에너지 의존 시리즈** (커피·알람·소파) — 공감 포인트 보편성 최강
