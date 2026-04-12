# POD 공감 유머 밈 — 미드저니 프롬프트 가이드

> **"이거 나잖아"** 를 끌어내는 공감형 유머 일러스트를 만드는 프롬프트입니다.
> T셔츠, 머그컵, 에코백 등 POD 상품에 바로 쓸 수 있어요.
> **텍스트는 미드저니로 생성하지 않습니다.** 일러스트만 뽑고, 문구는 Canva / Photoshop에서 따로 추가하세요.

---

## 📌 이 프롬프트는 어떤 용도인가요?

그라데이션 없이 **인쇄에 바로 적합한 플랫 벡터 유머 일러스트**를 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- POD T셔츠 · 머그컵 · 에코백 · 폰케이스 디자인
- Redbubble / Merch by Amazon / 마플샵 업로드 소스
- 직장인 · 내향인 · 반려동물 집사 등 **니치 굿즈** 메인 이미지
- SNS 카드뉴스 · 블로그 공감 삽화

> ⚠️ **"meme" "funny face" 단어를 쓰지 마세요.**
> `"meme"` 은 드레이크·놀란 아저씨 같은 저작권 있는 실제 밈 이미지를 끌어옵니다.
> `"funny face"` 는 실제 사람 얼굴로 생성됩니다.
> 이 프롬프트는 `humorous illustration` + `cartoon character` 로 그 함정을 피했습니다.

---

## 🚀 빠른 시작

1. 아래 예시 8개 중 내 타겟 고객과 맞는 걸 고르세요.
2. **"완성 프롬프트"** 를 통째로 복사하세요.
3. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.
4. 결과 이미지를 **Canva** 에서 열고, 문구 레이어를 따로 추가하세요.

---

## 📐 마스터 프롬프트 본문

```
A humorous illustration of {meme_scene}, drawn in {art_style}, conveying a {humor_tone} mood, with {color_scheme} on a clean white background, {text_space}. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 1:1 --v 8 --style raw --s 250
```

---

## ⚙️ 옵션 파라미터

| 파라미터 | 권장값 | 메모 |
| --- | --- | --- |
| `--ar` | `1:1` 정방형 (기본) / `16:9` 가로형 (세트·대비 구도) | |
| `--v` | `8` | 고정 |
| `--style` | `raw` | 고정. 일러스트 충실도에 필수 |
| `--s` | `200` 절제 / `250` 권장 / `350` 장식적 | 유머 장르는 250~350이 표정·과장이 잘 살아요 |

---

## 📌 변수 5개 — 모두 필수

### 1. `{meme_scene}` — 어떤 공감 상황인가요?

**가장 중요한 변수.** 상황이 구체적일수록 "이거 나잖아" 반응이 세집니다.

공감 서브타입 4가지로 분류해 예시를 드릴게요:

**🗂 직장인 공감**
- `a disheveled cartoon office worker slumped over a desk, holding a tiny coffee cup with dark circles under enormous eyes`
- `a row of three cartoon office workers sitting at a meeting table with identical hollow expressions and glazed eyes, one secretly napping`

**🏠 내향인 / 집돌이**
- `a content cartoon character curled up on a couch surrounded by books and a cat, with a tiny panicked expression at a phone showing a social invitation`
- `a cartoon character happily hiding under a blanket fortress labeled "do not disturb", surrounded by snacks and a glowing screen`

**☕ 커피 / 음식 문화**
- `a tiny cartoon character desperately clinging to an oversized coffee cup twice their height, with exaggerated wide awake eyes`
- `a cartoon character with a blissful expression surrounded by floating snacks and desserts like a food deity`

**🐱 반려동물 집사**
- `a tiny cartoon human being commanded by a large imperious cat sitting on a throne, the human bowing while holding a tray of gourmet food`
- `a cartoon dog owner being dragged across the floor by an excited dog three times their size`

> 💡 **니치를 좁게 잡을수록 팔립니다.** "직장인 공감"보다 "회의가 메일이었을 때의 그 표정"이 훨씬 강해요.

---

### 2. `{art_style}` — 어떤 그림체?

- `bold retro cartoon style with thick black outlines and exaggerated proportions, like a 1990s editorial illustration`
- `clean flat vector style with simple geometric shapes and deadpan facial expression, like a modern infographic character`
- `chunky bold graphic with high-contrast fills and exaggerated expressions, like a vintage punk zine illustration`
- `thick confident strokes and exaggerated scale differences, like a contemporary editorial cartoon`
- `soft rounded character design with simplified features and subtle blush marks, in a modern wholesome cartoon style`

> 💡 **유머 강도에 따라 그림체를 고르세요.**
> - 강한 과장·풍자 → `bold retro cartoon` / `punk zine`
> - 부드러운 공감·귀여운 → `wholesome cartoon` / `flat vector`

---

### 3. `{humor_tone}` — 유머 무드는?

- `deadpan exhausted` — 무표정 탈진 (직장인·월요일)
- `wholesome antisocial` — 순수한 은둔 (내향인)
- `dramatically dependent` — 과장된 의존 (커피·음식)
- `dry corporate` — 건조한 직장 풍자 (오피스 유머)
- `relatable defeated` — 공감 좌절 (어른 생활)
- `self-aware chaotic` — 자조적 혼돈 (SNS·폰 중독)

---

### 4. `{color_scheme}` — 컬러는?

**2~3색이 POD 인쇄에 가장 안전합니다.** 고대비가 썸네일에서 잘 읽혀요.

- `charcoal black and muted mustard yellow`
- `forest green and warm cream with dark outlines`
- `burnt orange and off-white only`
- `deep navy and pale yellow`
- `deep burgundy and pale pink with black outlines`
- `midnight blue and warm cream`
- `charcoal black and warm cream with a single terracotta accent`
- `muted sage green and warm cream with black outlines`

> ⚠️ **"pastel" 단어를 피하세요.** 인쇄 시 색이 죽고 밀도가 낮아져요.
> POD 인쇄에는 `muted`, `charcoal`, `deep`, `warm` 같은 수식어가 훨씬 정확하게 나옵니다.

---

### 5. `{text_space}` — 텍스트 공간은?

미드저니가 텍스트를 그리면 글자가 깨집니다. 대신 **공간만 지정**하고 나중에 Canva에서 추가하세요.

- `with empty space at the top third for overlaid text`
- `with blank space at the bottom for a caption`
- `centered as one large illustration with top margin for text overlay`
- `with generous white margin all around for text placement`
- `as a standalone illustration with no text space needed` (텍스트 없는 순수 일러스트)
- `spaced side by side with even breathing room and space above for text` (세트형)

---

## ✏️ 적용 예시 8개

---

### 예시 1 — 월요일 생존자 (직장인 / 차콜+머스타드)

```
A humorous illustration of a disheveled cartoon office worker slumped over a desk, holding a tiny coffee cup with dark circles under enormous eyes, drawn in bold retro cartoon style with thick black outlines and exaggerated proportions, like a 1990s editorial illustration, conveying a deadpan exhausted mood, with charcoal black and muted mustard yellow on a clean white background, with empty space at the top third for overlaid text. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 1:1 --v 8 --style raw --s 250
```

**추천 문구:** "Survived another Monday" / "Monday? Already?" / "월요일엔 커피가 곧 나야"

---

### 예시 2 — 집돌이의 행복 (내향인 / 포레스트그린+크림)

```
A humorous illustration of a content cartoon character curled up on a couch surrounded by books and a cat, wearing pajamas and holding a steaming mug, with a tiny panicked expression at a phone showing a social invitation, drawn in clean flat vector style with simple geometric shapes and deadpan facial expression, like a modern infographic character, conveying a wholesome antisocial mood, with forest green and warm cream with dark outlines on a clean white background, centered as one large illustration with top margin for text overlay. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 1:1 --v 8 --style raw --s 250
```

**추천 문구:** "Sorry, I have plans with my couch" / "No thanks, I'm busy" / "오늘도 집이 최고야"

---

### 예시 3 — 커피 없이는 못 사는 (커피 문화 / 번트오렌지+아이보리)

```
A humorous illustration of a tiny cartoon character desperately clinging to an oversized coffee cup twice their height, with exaggerated wide awake eyes and steam swirling around them, drawn in thick confident strokes with exaggerated proportions, like a contemporary editorial cartoon, conveying a dramatically dependent mood, with burnt orange and off-white only on a clean white background, with blank space at the bottom for a caption. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 1:1 --v 8 --style raw --s 300
```

**추천 문구:** "Don't talk to me before coffee" / "But first, coffee" / "커피가 없으면 나도 없어"

---

### 예시 4 — 그 회의는 메일이었어야 했어 (오피스 / 네이비+페일옐로)

```
A humorous illustration of a row of three cartoon office workers sitting at a meeting table, all with identical hollow empty expressions and glazed eyes, one secretly napping with eyes drawn open, drawn in precise thin lines with restrained geometry in a Scandinavian editorial style, conveying a dry corporate humor mood, with deep navy and pale yellow on a clean white background, spaced in a single horizontal row with empty space above for text. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 16:9 --v 8 --style raw --s 200
```

**추천 문구:** "This meeting could've been an email" / "Another day, another pointless meeting" / "이건 메일로 왔어야 했다"

---

### 예시 5 — 수면 갈망 (수면 부족 / 미드나잇블루+크림)

```
A humorous illustration of a cartoon character with a blissful expression floating on a giant cloud shaped like a pillow, wrapped in a blanket cocoon with a tiny alarm clock falling in the distance, drawn in soft rounded character design with simplified features and subtle blush marks, in a modern wholesome cartoon style, conveying a dreamy escapist mood, with midnight blue and warm cream with soft outlines on a clean white background, centered as one large illustration with top margin for text overlay. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 1:1 --v 8 --style raw --s 300
```

**추천 문구:** "I dream of sleeping" / "Just 5 more minutes" / "어른도 낮잠이 필요해"

---

### 예시 6 — 폰 중독 자조 (디지털 / 세이지그린+크림)

```
A humorous illustration of a cartoon character whose entire face has been replaced by a glowing phone screen, sitting cross-legged with the phone held in front of their face, small swirling stars and hearts floating around, drawn in bold continuous outlines with simplified geometric forms, like a Dribbble-featured editorial icon, conveying a self-aware chaotic mood, with muted sage green and warm cream with black outlines on a clean white background, with blank space at the bottom for a caption. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 1:1 --v 8 --style raw --s 250
```

**추천 문구:** "Screen time: all of it" / "Put the phone down. Lol, no" / "오늘도 폰이 나의 전부야"

---

### 예시 7 — 금요일 vs 월요일 대비 세트 (어른 생활 / 버건디+페일핑크)

```
A humorous illustration of two side-by-side cartoon character panels: left panel shows a character on Friday evening with sparkly eyes and arms raised in triumph, right panel shows the exact same character on Monday morning as a wilted sad plant with drooping leaves and empty eyes, drawn in chunky bold graphic style with high-contrast fills and exaggerated expressions, like a vintage punk zine illustration, conveying a relatable weekly cycle mood, with deep burgundy and pale pink with black outlines on a clean white background, spaced side by side with even breathing room and space above for text. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 16:9 --v 8 --style raw --s 250
```

**추천 문구:** "Friday / Monday" / "Me: 5pm Friday vs 8am Monday" / "금요일 나 / 월요일 나"

---

### 예시 8 — 고양이 집사의 현실 (반려동물 / 차콜+테라코타)

```
A humorous illustration of a tiny cartoon human being commanded by a large imperious cat sitting on a throne, the human bowing while holding a tray of gourmet food with an adoring smile, the cat looking unimpressed, drawn in bold retro cartoon style with thick outlines and exaggerated scale difference, like a 1990s editorial illustration, conveying a relatable pet ownership power dynamic mood, with charcoal black and warm cream with a single terracotta accent on a clean white background, centered as one large illustration with bottom space for a caption. Print-ready graphic design, flat vector style, clean edges, no gradients, no text in image. --ar 1:1 --v 8 --style raw --s 250
```

**추천 문구:** "Not my cat, I work for her" / "My cat owns me" / "나는 고양이 직원입니다"

---

## 🔧 변주 팁

| 이걸 바꾸면 | 효과 |
| --- | --- |
| `{meme_scene}` 만 | 같은 스타일·컬러로 **다른 공감 주제** 시리즈 |
| `{humor_tone}` 만 | 같은 캐릭터를 `deadpan` → `chaotic` → `wholesome` 버전으로 |
| `{color_scheme}` 만 | 다크모드용: `matte black and neon lime`, 밝은 컬러: `deep teal and warm yellow` |
| `--ar 1:1 → 16:9` | 대비 2컷 구도 (예시 7처럼) |
| `--s 250 → 350` | 표정·과장이 더 강해지고 유머가 진해짐 |
| `--s 250 → 150` | 더 절제되고 깔끔한 인포그래픽 느낌 |
| `{text_space}` 를 `top` → `bottom` | 캡션 위치 이동 |
| `--sref [URL]` 추가 | 여러 상품을 같은 캐릭터 톤으로 통일할 때 |

---

## ⚠️ 핵심 팁 7가지

1. **"meme" 키워드 절대 금지.** 드레이크, 놀란 아저씨 등 저작권 있는 실제 밈 이미지가 생성됩니다.
2. **텍스트는 미드저니로 만들지 마세요.** 글자가 항상 깨집니다. 일러스트만 뽑고 Canva에서 추가하세요.
3. **"funny face" 금지.** 실제 사람 얼굴이 생성됩니다. `exaggerated cartoon character` 로 대체하세요.
4. **컬러는 2~3색.** 그라데이션 없는 단색이 인쇄 색 재현률이 높아요. `pastel` 단어는 피하세요.
5. **니치를 좁게 잡으세요.** "직장인 유머"보다 "회의 생존자", "월요일 증오"가 공감이 더 강합니다.
6. **문구는 6단어 이내.** 썸네일에서 한 번에 읽혀야 팔립니다. 긴 문장은 후킹력이 떨어집니다.
7. **POD 플랫폼마다 배경 처리 확인.** `clean white background` 로 생성 후 필요하면 배경 제거 도구로 투명화하세요.

---

## ✅ 시리즈 만드는 추천 흐름

1. 타겟 고객 하나를 정하세요. (직장인? 내향인? 반려동물 집사?)
2. 예시에서 가장 가까운 것을 골라 먼저 돌려보세요.
3. 마음에 들면 `{meme_scene}` 만 바꿔서 같은 스타일로 4~5개 시리즈를 만드세요.
4. 첫 결과의 `-seed` 값을 복사해서 다음에 붙이면 캐릭터 톤이 통일됩니다.
5. 완성된 일러스트를 Canva에 올리고 문구 레이어를 추가하면 상품 소스 완성.

> 💡 **밈 트렌드는 유통기한이 짧습니다.** 트렌드형(특정 밈 소재)은 빠르게 출시하고, 공감형(직장인·내향인·커피)은 시즌 무관하게 꾸준히 팔립니다. 둘을 병행하는 게 최적입니다.

---

## 📊 POD 플랫폼별 권장 사이즈

| 플랫폼 | 권장 이미지 사이즈 | 참고 |
| --- | --- | --- |
| Merch by Amazon | 4500 × 5400px (15×18인치, 300dpi) | T셔츠 기준 |
| Redbubble | 7632 × 6480px | 클래식 티 기준 |
| 마플샵 | 3000 × 3000px 이상 | 정방형 권장 |
| TeePublic | 4200 × 4800px | T셔츠 기준 |

> ⚠️ 미드저니 기본 출력은 저해상도입니다. **Upscale** 기능 또는 Adobe Firefly / Topaz 업스케일러로 인쇄 해상도로 올린 뒤 업로드하세요.
