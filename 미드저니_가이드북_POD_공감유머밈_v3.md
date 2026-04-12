> **그림만으로 웃기는 공감 유머 일러스트**를 만드는 프롬프트입니다. 단일 캐릭터도, 2컷 대비 구도도 OK!
> T셔츠·머그컵·에코백 등 POD 상품에 바로 쓸 수 있어요.
> 텍스트 없이 표정·상황만으로 유머가 전달되도록 설계했습니다.

---

## 📌 이 프롬프트는 어떤 용도인가요?

표정·상황·캐릭터만으로 유머가 전달되는 **비주얼 온리 POD 유머 일러스트**를 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- POD T셔츠·머그컵·에코백·스티커 메인 일러스트
- Redbubble / Etsy / 마플샵 업로드 소스
- 텍스트 없이 그림만으로 완성되는 디자인
- 공감 동물 캐릭터 시리즈 굿즈

> ⚠️ **"meme" "funny face" 단어를 쓰지 마세요.** "meme"은 드레이크·놀란 아저씨 같은 저작권 있는 실제 밈을 끌어와요. "funny face"는 실제 사람 얼굴이 나와요. 이 프롬프트는 `humorous illustration` + `exaggerated cartoon character` 로 그 함정을 피했습니다.

---

## 🚀 빠른 시작

1. 아래 예시 중 마음에 드는 걸 고르세요. (단일 캐릭터 6개 + 2컷 대비 2개)
2. **"완성 프롬프트"** 를 통째로 복사하세요.
3. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

## 📐 마스터 프롬프트 본문

```
A humorous illustration of {meme_scene}, drawn in {art_style} with {color_tone} on a {background} background, {composition}. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 300
```

---

## ⚙️ 옵션 파라미터

| 파라미터 | 권장값 | 메모 |
| --- | --- | --- |
| `--ar` | `1:1` 정방형 (기본) / `16:9` 2컷 대비 구도 |  |
| `--v` | `8` | 고정 |
| `--style` | `raw` | 고정. 본문 충실도에 필수 |
| `--s` | `150` 절제 / `300` 권장 / `400` 과장 극대화 |  |

---

## 📌 변수 5개 — 모두 필수

### 1. `{meme_scene}` — 어떤 공감 상황인가요?

**단일 캐릭터**일 때: 상황을 극단적으로 구체화하세요. 과장이 강할수록 잘 읽힙니다.
**2컷 대비**일 때: 대조가 명확할수록 유머가 강해집니다.

단일 캐릭터 예시:

- `a tiny cartoon character desperately clinging to an oversized coffee cup twice their height, eyes wide with desperate gratitude`
- `a cartoon character enthusiastically punching an alarm clock mid-swing, wild bedhead hair and pajamas`
- `a raccoon character wearing a tiny crown, sitting on a pile of snacks with arms spread wide to guard everything`
- `a capybara character sitting perfectly still in the center of utter chaos — objects flying, a tiny fire in the background — completely indifferent`
- `a tiny cartoon human bowing deeply while serving gourmet food to a large imperious cat sitting on a throne, the cat looking completely unimpressed`
- `a cartoon character melting off a couch like a liquid puddle, completely boneless, a remote control loosely in one hand`

2컷 대비 예시:

- `two side-by-side panels: left shows a cartoon character on Friday as a sparkling vibrant sun with jazz hands, right shows the exact same character on Monday as a wilted drooping plant with empty eyes`
- `two panels: left shows a glowing energetic character confidently holding coffee, right shows the same character as a hollow hollow shell reaching desperately for a second cup`

> 💡 **비주얼 온리 체크.** 글자 없이 봐도 웃기나요? → OK. 글자가 있어야 웃기나요? → 상황을 더 극단적으로 묘사하거나, 카오틱 동물 캐릭터로 전환하세요.

### 2. `{art_style}` — 어떤 그림체?

구체적인 디자인 레퍼런스를 넣을수록 캐릭터가 살아나요. 추상적인 "cartoon style"보다 구체적 묘사가 좋아요.

- `bold retro cartoon style with thick black outlines and exaggerated expressions, like a 1990s editorial illustration`
- `chunky bold graphic with high-contrast fills and wildly exaggerated proportions, like a vintage punk zine illustration`
- `soft rounded character design with large expressive eyes and subtle blush marks, in a modern wholesome cartoon style`
- `clean flat vector style with simple geometric shapes and deadpan expression, like a modern infographic character`
- `loose sketchy linework with rough texture and imperfect proportions, like a hand-doodled notebook cartoon`

### 3. `{color_tone}` — 컬러는?

**2~3색이 POD 인쇄에 가장 안전해요.** 고대비일수록 썸네일에서 잘 읽혀요.

- `charcoal black and muted mustard yellow`
- `burnt orange and off-white`
- `forest green and warm cream`
- `deep navy and pale yellow`
- `deep burgundy and pale pink`
- `warm terracotta and off-white`
- `midnight blue and warm cream`
- `matte black and neon lime`

> 💡 **"pastel" 단어를 피하세요.** 미드저니가 인쇄에서 색이 죽는 뿌연 결과를 내요. "muted", "deep", "warm" 같은 수식어가 훨씬 선명하게 나옵니다.

### 4. `{background}` — 배경은?

단색이 가장 안전. 투명을 원하면 `clean white` 후 배경 제거 도구 쓰세요.

- `clean white`
- `off-white`
- `warm cream`
- `soft light gray`
- `matte black`

### 5. `{composition}` — 구도는?

**단일 캐릭터**일 때: 가운데 크게.
**2컷 대비**일 때: 가로 나란히.

단일 예시:

- `centered as one large illustration filling the frame with wide margins`
- `placed dead center at oversized scale dominating the canvas`

2컷 대비 예시:

- `placed side by side as two equal panels with even breathing room`
- `arranged as two panels left and right with a clear visual divide between them`

---

## ✏️ 적용 예시 8개

---

### 예시 1 — ☕ 커피 의존증 (번트오렌지+아이보리)

```
A humorous illustration of a tiny cartoon character desperately clinging to an oversized coffee cup twice their height, eyes wide with desperate gratitude, drawn in bold retro cartoon style with thick black outlines and exaggerated expressions, like a 1990s editorial illustration with burnt orange and off-white on a clean white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 300
```

![image.png](image.png)

---

### 예시 2 — 😴 알람 격파 (차콜+머스타드)

```
A humorous illustration of a cartoon character enthusiastically punching an alarm clock mid-swing with gleeful determination, still in pajamas with wild bedhead hair, drawn in chunky bold graphic with high-contrast fills and wildly exaggerated proportions, like a vintage punk zine illustration with charcoal black and muted mustard yellow on a clean white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 350
```

![image.png](image.png)

---

### 예시 3 — 🐱 고양이 왕좌 (차콜+테라코타)

```
A humorous illustration of a tiny cartoon human bowing deeply while serving gourmet food on a silver tray to a large imperious cat sitting on an ornate throne, the cat looking completely unimpressed with one paw raised dismissively, drawn in bold retro cartoon style with thick black outlines and exaggerated scale difference, like a 1990s editorial illustration with charcoal black and warm terracotta on a clean white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 300
```

![image.png](image.png)

---

### 예시 4 — 🦝 너구리 과자 수호자 (포레스트그린+크림)

```
A humorous illustration of a raccoon character wearing a tiny crown, sitting possessively on a pile of snacks and miscellaneous treasures with a deeply satisfied expression, arms spread wide to guard everything, drawn in soft rounded character design with large expressive eyes and subtle blush marks, in a modern wholesome cartoon style with forest green and warm cream on a clean white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 300
```

![image.png](image.png)

---

### 예시 5 — 🛋️ 소파에 녹아드는 집돌이 (네이비+페일옐로)

```
A humorous illustration of a cartoon character melting off a couch like a liquid puddle, completely boneless and limp with heavy-lidded blissful eyes, a remote control loosely in one hand, drawn in clean flat vector style with simple geometric shapes and deadpan expression, like a modern infographic character with deep navy and pale yellow on an off-white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 250
```

![image.png](image.png)

---

### 예시 6 — 😶 카피바라 무관심 (테라코타+아이보리)

```
A humorous illustration of a round capybara character sitting perfectly still in the center of absolute chaos — objects flying, things falling, a tiny fire in the background — wearing a completely calm and indifferent expression, drawn in chunky bold graphic with high-contrast fills and exaggerated surroundings, like a vintage punk zine illustration with warm terracotta and off-white on a clean white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 300
```

![image.png](image.png)

---

### 예시 7 — 🐕 강아지한테 끌려가는 집사 (버건디+크림)

```
A humorous illustration of a cartoon character being dragged horizontally across the floor by an enormous excited dog on a leash, the human's body stretched completely flat like a flag behind the sprinting dog, legs trailing in the air with a resigned but loving expression, drawn in bold retro cartoon style with thick black outlines and exaggerated proportions, like a 1990s editorial illustration with deep burgundy and warm cream on a clean white background, centered as one large illustration filling the frame with wide margins. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 1:1 --v 8 --style raw --s 350
```

![image.png](image.png)

---

### 예시 8 — 📅 금요일 vs 월요일 (2컷 / 버건디+페일핑크)

```
A humorous illustration of two side-by-side panels: left panel shows a cartoon character on Friday as a sparkling vibrant sun with jazz hands and a glowing halo, right panel shows the exact same character on Monday as a wilted drooping plant in a pot with empty hollow eyes and drooping leaves, drawn in chunky bold graphic with high-contrast fills and exaggerated expressions, like a vintage punk zine illustration with deep burgundy and pale pink on a clean white background, placed side by side as two equal panels with even breathing room. The joke reads entirely from the visual — no text, no speech bubbles. Flat vector style with solid fills and clean edges, rendered as print-ready graphic design. --ar 16:9 --v 8 --style raw --s 300
```

![image.png](image.png)

---

## 🔧 변주 팁

| 이걸 바꾸시면 | 효과 |
| --- | --- |
| `{meme_scene}` 만 | 같은 스타일·컬러로 **다른 공감 주제** 시리즈. 캐릭터 통일감 |
| 단일 → 2컷 전환 | `{meme_scene}` 을 `two side-by-side panels...` 로, `{composition}` 을 `placed side by side...` 로, `--ar` 을 `16:9` 로 바꾸면 끝 |
| `{art_style}` 만 | 같은 장면, 다른 그림체 (레트로→카와이→스케치) |
| `{color_tone}` 만 | 같은 캐릭터, 다른 무드 (머스타드→테라코타→네이비) |
| `{background}` 를 `matte black` 으로 | 다크 모드 굿즈 라인 |
| `--s 300→150` | 더 절제되고 깔끔한 느낌 |
| `--s 300→400` | 과장이 극대화되고 표정이 더 강해짐 |
| `--sref [URL]` 추가 | 여러 캐릭터를 같은 톤으로 통일할 때 |
| 예시 4처럼 동물 캐릭터로 전환 | 너구리·카피바라·오포섬은 텍스트 없이 가장 잘 팔리는 유형 |

---

## ⚠️ 핵심 팁 6가지

1. **"meme" "funny face" 단어 금지.** 저작권 밈 캐릭터·실제 사람 얼굴의 주범이에요.
2. **상황을 극단적으로 묘사하세요.** "slightly tired"보다 "melting off a couch like a liquid puddle"이 유머가 훨씬 강해요.
3. **컬러는 2~3색.** "pastel" 단어 피하세요 — "muted", "deep", "warm" 이 인쇄에서 훨씬 선명하게 나와요.
4. **카오틱 동물은 `--s 300~400`.** 너구리·카피바라·오포섬은 스타일라이즈 수치가 높을수록 캐릭터가 살아납니다.
5. **2컷 대비는 반드시 `--ar 16:9`.** `1:1`로 하면 두 캐릭터가 뭉개져요.
6. **배경은 `clean white`.** 배경 제거 도구로 투명화하면 모든 상품에 바로 쓸 수 있어요.

---

## ✅ 시리즈 만드는 추천 흐름

1. 예시 하나를 골라서 먼저 돌려보세요.
2. 마음에 들면 `{meme_scene}` 만 바꿔서 같은 스타일의 다른 공감 장면을 만드세요.
3. 첫 결과의 `-seed` 값을 복사해서 다음에 붙이면 캐릭터 톤이 통일돼요.
4. 3~4개 만든 후 `--sref [첫 결과 URL]` 추가하면 완벽한 공감 캐릭터 패키지!

> 💡 **상시판매형 추천 순서.** ① 카오틱 동물 (너구리·카피바라·오포섬) — 텍스트 없이 가장 잘 팔리는 유형. ② 반려동물 권력 역학 (고양이 왕좌·강아지 집사) — 견종·묘종으로 세분화하면 니치가 더 강해짐. ③ 에너지 의존 시리즈 (커피·알람·소파) — 공감 포인트 보편성 최강.
