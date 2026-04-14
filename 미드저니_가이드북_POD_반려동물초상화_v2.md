> **반려동물을 주인공으로 한 POD 초상화 일러스트**를 만드는 프롬프트입니다.
> 얼굴 임베드 합성부터 드라마틱 신비까지, 4가지 스타일을 제공합니다.
> T셔츠·머그컵·캔버스 포스터·폰케이스 등 전 POD 상품에 바로 쓸 수 있어요.

---

## 📌 이 프롬프트는 어떤 용도인가요?

실제 동물처럼 보이되 **상황이 웃기거나 드라마틱한** 반려동물 초상화를 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- POD T셔츠·머그컵·캔버스 포스터 메인 이미지
- Redbubble / Etsy / 마플샵 업로드 소스
- 반려동물 굿즈 시리즈 소스
- 선물용 커스텀 포스터 디자인

> ⚠️ **"my cat" "my dog" 단어를 쓰지 마세요.** 미드저니는 텍스트만으로 실제 반려동물을 불러올 수 없어요. 대신 품종·털색·특징을 구체적으로 묘사하세요. `a chubby orange tabby cat with half-closed sleepy eyes` 처럼요.

---

## 🚀 빠른 시작

1. 아래 4가지 스타일 중 하나를 고르세요.
2. 원하는 예시를 고르세요. (스타일당 2개, 총 8개)
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

## 📐 마스터 프롬프트 본문

```
A portrait of {pet_subject}, {scenario}, rendered in {style_direction}, {color_mood}, {composition}. Print-ready, no text. --ar 1:1 --s 200
```

---

## ⚙️ 옵션 파라미터

| 파라미터 | 스타일 1·2 (포토리얼) | 스타일 3 (빈티지) | 스타일 4 (신비) | 메모 |
| --- | --- | --- | --- | --- |
| `--ar` | `1:1` / `4:5` | `1:1` / `2:3` | `1:1` / `4:5` | |
| `--style` | 생략 | `raw` 추가 | 생략 | |
| `--s` | `150`~`200` | `200`~`300` | `150`~`250` | |

---

## 📌 변수 5개 — 모두 필수

### 1. `{pet_subject}` — 어떤 반려동물인가요?

품종·털색·체형·표정을 구체적으로 묘사할수록 실제 반려동물처럼 나와요.

고양이 예시:

- `a chubby orange tabby cat with half-closed sleepy eyes and a round loaf-shaped body`
- `a fluffy grey Scottish Fold cat with huge round eyes and tiny folded ears`
- `a sleek black cat with bright yellow eyes and a long slender body`
- `three cats together: a grey cat, a white cat, and a tabby cat wearing a small chef's hat`

강아지 예시:

- `a fluffy golden Cockapoo puppy with curly fur and round dark eyes`
- `a wrinkly Shiba Inu with a smug expression and thick rust-colored coat`
- `a tiny Chihuahua with enormous bat ears and a trembling dramatic expression`
- `a large fluffy Samoyed with a perpetual smile and thick white fur`

> 💡 **품종 이름을 넣으세요.** "dog"보다 "Cockapoo", "Shiba Inu"가 훨씬 정확하게 나옵니다. 특징 디테일(털색, 눈색, 체형)을 추가하면 더 개성 있게 나와요.

### 2. `{scenario}` — 어떤 상황인가요?

**스타일 1 (얼굴 임베드)** — 동물 얼굴이 음식 안에 박혀있는:

- `with face embedded inside a slice of white toast bread, face filling the bread shape naturally, clean white background`
- `with face peeking out from inside a glazed pink donut, the donut ring frames the face like a portrait`
- `with face merged into a round white mochi, soft mochi surface surrounding the face, clean white background`
- `with face embedded in a golden croissant, flaky pastry layers framing the face on all sides`

**스타일 2 (쿨 라이프스타일)** — 반려동물이 쿨한 소품과 함께:

- `sitting on urban steps holding an oversized iced coffee drink with both paws, wearing small round sunglasses`
- `riding a skateboard down a city street, tiny cap backwards, looking effortlessly cool`
- `lounging poolside in a tiny sun hat, one paw dangling into the water`

**스타일 3 (빈티지 장르)** — 복고 장르 속 등장:

- `being abducted by a UFO beam in a desert landscape, arms raised dramatically`
- `riding a horse across the Wild West frontier, wearing a cowboy hat, dust kicking up behind`
- `posing as a 1920s noir detective in a rainy alleyway, tiny fedora and trenchcoat`

**스타일 4 (드라마틱 신비)** — 달·우주·신비 배경:

- `posed dramatically against an enormous full moon, mystical star glow surrounding them`
- `floating in deep space surrounded by galaxies and nebulae, looking utterly unbothered`
- `emerging from dark mist under a full moon with celestial sparkle effects all around`

### 3. `{style_direction}` — 4가지 스타일 중 선택

**스타일 1 — 얼굴 임베드** (고양이 식빵 계열)

```
a photorealistic composite of the pet's face seamlessly embedded inside a food item, the face peeks through the food surface naturally, the food acts as a frame around the face, soft studio lighting, clean white background, surreal yet cute, hyper-detailed fur and food texture
```

**스타일 2 — 쿨 라이프스타일** (강아지 선글라스 계열)

```
a cinematic lifestyle photograph, shallow depth of field bokeh background, warm golden hour lighting, DSLR portrait quality, hyper-realistic fur detail
```

**스타일 3 — 빈티지 장르** (고양이 UFO 계열)

```
a vintage genre print illustration, aged sepia and warm brown tones, retro ink print quality, like a 1950s vintage travel poster lithograph
```

**스타일 4 — 드라마틱 신비** (고양이 달 계열)

```
a dramatic mystical composite portrait, volumetric moonlight and star bokeh, cinematic epic lighting, sparkle and celestial glow effects, like a parody of Three Wolf Moon
```

> 💡 **스타일 선택 기준**
> | | 스타일 1 얼굴 임베드 | 스타일 2 라이프스타일 | 스타일 3 빈티지 | 스타일 4 신비 |
> |---|---|---|---|---|
> | 무드 | 귀엽고 초현실적 | 쿨하고 도시적 | 위트있고 복고적 | 드라마틱하고 캠피 |
> | 어울리는 상품 | 스티커·머그컵·쿠션 | T셔츠·폰케이스 | 포스터·에코백 | T셔츠·포스터 |

### 4. `{color_mood}` — 색감·분위기는?

**스타일 1·2 (포토리얼)** — 조명과 배경 톤:

- `warm golden tones with soft studio lighting`
- `cool urban evening light with city bokeh`
- `bright clean white studio lighting`
- `warm sunset tones, soft orange glow`

**스타일 3 (빈티지)** — 레트로 색감:

- `monochromatic sepia and warm brown`
- `faded olive and aged cream tones`
- `muted slate blue and warm ivory`

**스타일 4 (신비)** — 드라마틱 색감:

- `deep midnight blue and silver moonlight`
- `rich purple and gold celestial tones`
- `dark teal and ethereal white glow`

### 5. `{composition}` — 구도는?

- `centered as one large portrait filling the frame` *(단일 캐릭터 기본)*
- `full body shown against a clean background` *(전신)*
- `close-up portrait from chest up, facing slightly to the side` *(상반신 클로즈업)*
- `three subjects arranged in a horizontal row, center subject slightly larger` *(다중 캐릭터)*
- `wide establishing shot showing the full scene and background` *(풍경 포함)*

---

## ✏️ 적용 예시 8개

---

### 예시 1 — 🍞 고양이 식빵 임베드 — 스타일 1 (웜골드)

```
A portrait of a chubby orange tabby cat with half-closed sleepy eyes and a round loaf-shaped body, with face embedded inside a slice of white toast bread, face filling the bread shape naturally, clean white background, rendered in a photorealistic composite of the pet's face seamlessly embedded inside a food item, the face peeks through the food surface naturally, the food acts as a frame around the face, soft studio lighting, clean white background, surreal yet cute, hyper-detailed fur and food texture, warm golden tones with soft studio lighting, centered as one large portrait filling the frame. Print-ready, no text. --ar 1:1 --s 200
```

![image.png](image.png)

---

### 예시 2 — 🍩 강아지 도넛 임베드 — 스타일 1 (클린 화이트)

```
A portrait of a fluffy golden Cockapoo puppy with curly fur and round dark eyes, with face peeking out from inside a glazed pink donut, the donut ring frames the face like a portrait, rendered in a photorealistic composite of the pet's face seamlessly embedded inside a food item, the face peeks through the food surface naturally, the food acts as a frame around the face, soft studio lighting, clean white background, surreal yet cute, hyper-detailed fur and food texture, bright clean white studio lighting, centered as one large portrait filling the frame. Print-ready, no text. --ar 1:1 --s 200
```

![image.png](image.png)

---

### 예시 3 — 😎 강아지 아이스커피 — 스타일 2 (골든아워)

```
A portrait of a fluffy golden Cockapoo puppy with curly fur and round dark eyes, sitting on urban steps holding an oversized iced coffee drink with both paws, wearing small round sunglasses, rendered in a cinematic lifestyle photograph, shallow depth of field bokeh background, warm golden hour lighting, DSLR portrait quality, hyper-realistic fur detail, warm sunset tones with soft orange city glow, centered as one large portrait filling the frame. Print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 4 — 🛹 고양이 스케이트보드 — 스타일 2 (쿨 어반)

```
A portrait of a sleek black cat with bright yellow eyes, riding a skateboard down a city street, tiny cap worn backwards, looking effortlessly cool, rendered in a cinematic lifestyle photograph, shallow depth of field bokeh background, cool urban evening light with city bokeh, DSLR portrait quality, hyper-realistic fur detail, cool urban evening light with city bokeh in the background, centered as one large portrait filling the frame. Print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 5 — 🛸 고양이 UFO 납치 — 스타일 3 (세피아)

```
A portrait of a tabby cat with wide startled eyes, being abducted by a UFO beam in a vast desert landscape, arms raised dramatically skyward, cacti and flat horizon in the distance, rendered in a vintage genre print illustration, aged sepia and warm brown tones, retro ink print quality, like a 1950s vintage travel poster lithograph, monochromatic sepia and warm brown, wide establishing shot showing the full scene and background. Print-ready, no text. --ar 1:1 --style raw --s 250
```

![image.png](image.png)

---

### 예시 6 — 🤠 강아지 카우보이 — 스타일 3 (더스티올리브)

```
A portrait of a wrinkly Shiba Inu with a smug expression and thick rust-colored coat, riding a horse across the Wild West frontier, wearing a cowboy hat, dust kicking up dramatically behind, rendered in a vintage genre print illustration, aged sepia and warm brown tones, retro ink print quality, like a 1950s vintage travel poster lithograph, faded olive and aged cream tones, wide establishing shot showing the full scene and background. Print-ready, no text. --ar 1:1 --style raw --s 250
```

![image.png](image.png)

---

### 예시 7 — 🌕 고양이 3마리 달 — 스타일 4 (미드나잇블루)

```
A portrait of three cats together: a grey cat, a white cat, and a tabby cat wearing a small chef's hat, posed dramatically against an enormous full moon, mystical star glow surrounding them, each cat staring in a different direction with intense expressions, rendered in a dramatic mystical composite portrait, volumetric moonlight and star bokeh, cinematic epic lighting, sparkle and celestial glow effects, like a parody of Three Wolf Moon, deep midnight blue and silver moonlight, three subjects arranged in a horizontal row with the center subject slightly larger. Print-ready, no text. --ar 1:1 --s 200
```

![image.png](image.png)

---

### 예시 8 — 🌌 고양이 우주 유영 — 스타일 4 (딥퍼플+골드)

```
A portrait of a fluffy grey Scottish Fold cat with huge round eyes and tiny folded ears, floating serenely in deep space surrounded by galaxies and nebulae, paws outstretched, looking utterly unbothered by the cosmos, rendered in a dramatic mystical composite portrait, volumetric moonlight and star bokeh, cinematic epic lighting, sparkle and celestial glow effects, like a parody of Three Wolf Moon, rich purple and gold celestial tones, centered as one large portrait filling the frame. Print-ready, no text. --ar 1:1 --s 200
```

![image.png](image.png)

---

## 🔧 변주 팁

| 이걸 바꾸시면 | 효과 |
| --- | --- |
| `{pet_subject}` 의 품종만 | 같은 컨셉·스타일로 다른 품종 시리즈 |
| `{scenario}` 의 음식만 (스타일 1) | 식빵→도넛→모찌→크루아상 얼굴 임베드 시리즈 |
| `{scenario}` 의 장르만 (스타일 3) | UFO→서부극→누아르→해적 장르 시리즈 |
| 단일 → 다중 전환 | `{pet_subject}` 에 여러 동물 추가, `{composition}` 을 `horizontal row` 로 |
| `--ar 1:1 → 4:5` | 인스타그램 포트레이트 비율 |
| `--ar 1:1 → 2:3` | 포스터·아트프린트 비율 |
| `--s 200→300` (스타일 3) | 빈티지 질감과 인쇄 느낌이 더 강해짐 |
| `--sref [URL]` 추가 | 여러 품종을 같은 스타일·톤으로 통일 |

---

## ⚠️ 핵심 팁 6가지

1. **품종 이름 + 특징 디테일을 함께 쓰세요.** "dog"보다 "fluffy golden Cockapoo with curly fur and round dark eyes"가 훨씬 정확하게 나와요.
2. **스타일 1에는 `clean white background` 필수.** 배경이 복잡하면 얼굴 임베드 효과가 약해져요.
3. **스타일 3에는 `--style raw` 필수.** 없으면 빈티지 인쇄 질감이 사라져요.
4. **스타일 1·2에는 `--style raw` 쓰지 마세요.** 포토리얼 품질이 딱딱해져요.
5. **다중 캐릭터(예시 7)는 수를 3개 이내로.** 4개 이상은 얼굴이 뭉개져요.
6. **`--s` 는 스타일마다 최적값이 달라요.** 포토리얼 150~200 / 빈티지 250~300.

---

## ✅ 시리즈 만드는 추천 흐름

1. 품종 하나를 고정하고 스타일을 정하세요.
2. 예시 하나를 먼저 돌려보세요.
3. `{scenario}` 만 바꿔서 같은 품종의 다른 상황 시리즈를 만드세요.
4. 첫 결과의 `-seed` 값을 복사해서 다음에 붙이면 동물 외형이 통일돼요.
5. `--sref [첫 결과 URL]` 추가하면 스타일이 고정된 완벽한 초상화 패키지!

> 💡 **상시판매형 추천 조합.** ① 스타일 1 얼굴 임베드 → 스티커·머그컵에 강함. ② 스타일 3 빈티지 장르 → 포스터·에코백에 강함. ③ 스타일 4 드라마틱 신비 → T셔츠 베스트셀러 계열.
