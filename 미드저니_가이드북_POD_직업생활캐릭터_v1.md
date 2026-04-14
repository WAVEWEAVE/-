> **직업·생활 공감 장면을 귀여운 캐릭터로 표현한 POD 일러스트**를 만드는 프롬프트입니다.
> "이거 나잖아" 공감을 자아내는 치비 캐릭터 스타일로, 머그컵·T셔츠·폰케이스에 강해요.
> 말풍선 `...` 은 감정 표현 도구로 쓸 수 있어요 — 텍스트 없이도 충분히 재밌어요.

---

## 📌 이 프롬프트는 어떤 용도인가요?

직업·생활 속 **공감되는 순간**을 귀엽고 단순한 치비 캐릭터로 포착하는 프롬프트예요.

이런 데 쓸 수 있어요:

- POD 머그컵·T셔츠·폰케이스 메인 이미지
- Redbubble / Etsy / 마플샵 직업별 굿즈 시리즈
- 직업·취미·생활 패턴 스티커 시트
- "이거 나잖아" 선물용 커스텀 굿즈

> ⚠️ **말풍선 안 텍스트는 미드저니가 깨뜨려요.** `...` 처럼 점 세 개 정도는 괜찮지만 단어나 문장은 쓰지 마세요. 텍스트가 필요하면 Canva에서 말풍선 위에 따로 올리세요.

---

## 🚀 빠른 시작

1. 아래 2가지 스타일 중 하나를 고르세요.
2. 원하는 예시를 고르세요. (스타일당 4개, 총 8개)
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

## 📐 마스터 프롬프트 본문

```
A {character}, {occupation_scene}, {art_style}, {color_palette}, {composition}. Clean white background, print-ready, no text. --ar 1:1 --s 200
```

---

## ⚙️ 옵션 파라미터

| 파라미터 | 스타일 A (LINE 스티커) | 스타일 B (치비 굿즈) | 메모 |
| --- | --- | --- | --- |
| `--ar` | `1:1` | `1:1` / `4:5` | |
| `--s` | `150` | `200`~`250` | |
| `--niji 6` | 선택 추가 | 권장 추가 | 일본 애니 감성 강화 |

---

## 📌 변수 5개 — 모두 필수

### 1. `{character}` — 어떤 캐릭터인가요?

귀여운 동물·생명체면 뭐든 돼요. 캐릭터가 직업을 수행하는 게 포인트예요.

- `a chubby grey shark with tiny stubby fins`
- `a round white polar bear with small black eyes`
- `a sleepy orange tabby cat with half-closed eyes`
- `a tiny fluffy penguin with a round belly`
- `a plump golden hamster with chubby cheeks`
- `a small green frog with big round eyes`
- `a soft lavender bunny with floppy ears`
- `a sleepy brown bear cub`

> 💡 **캐릭터는 고정하고 상황만 바꾸세요.** 같은 캐릭터로 여러 직업/상황 시리즈를 만들면 굿즈 라인업이 돼요.

### 2. `{occupation_scene}` — 어떤 상황인가요?

**직장·오피스:**

- `slumped face-first over a keyboard, a small speech bubble showing "..."` *(야근 탈진)*
- `staring blankly at a glowing monitor, dark circles under eyes, coffee cup nearby` *(야근 모드)*
- `sitting in a tiny office chair looking exhausted, surrounded by stacked paperwork` *(서류 폭탄)*
- `holding an oversized coffee cup with both hands, eyes half-open` *(출근 생존 커피)*

**크리에이터·디자이너:**

- `drawing on a tablet with intense focus, multiple reference images pinned around` *(작업 집중)*
- `staring at three monitors with a chaotic desktop, slightly overwhelmed expression` *(멀티태스킹 지옥)*
- `holding a color palette and brush, paint smudges everywhere, proud expression` *(그림 작업)*

**의료·서비스:**

- `wearing a tiny stethoscope and white coat, holding a clipboard with a tired smile` *(의사·간호사)*
- `standing behind a tiny coffee machine, handing over a cup with a warm smile` *(바리스타)*
- `wearing a tiny chef hat, stirring a pot while tasting, one eye closed` *(셰프)*

**교육·학생:**

- `pointing at a tiny blackboard with a stick, looking enthusiastic` *(선생님)*
- `surrounded by towering stacks of books, reading with a flashlight late at night` *(시험 벼락치기)*

**개인 생활:**

- `lying on a sofa under a blanket, smartphone in hand, snacks nearby` *(퇴근 후 소파 모드)*
- `half-heartedly lifting a tiny dumbbell at the gym, exhausted expression` *(헬스장 억지 운동)*
- `in pajamas, alarm going off, refusing to get up, one eye barely open` *(월요일 아침)*
- `sitting cross-legged with a laptop at a cozy cafe, matcha latte on the table` *(카공족)*

### 3. `{art_style}` — 2가지 스타일 중 선택

**스타일 A — LINE 스티커** (상어 키보드 계열)

```
simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute
```

**스타일 B — 치비 굿즈** (디테일 있는 굿즈 계열)

```
chibi kawaii character illustration, clean smooth outlines, soft flat color fills with gentle cel-shading highlights, big round expressive eyes, warm vibrant color palette, cozy comfort aesthetic, like a modern Korean character IP merchandise illustration, slightly more detailed than a sticker
```

> 💡 **스타일 선택 기준**
> | | 스타일 A LINE 스티커 | 스타일 B 치비 굿즈 |
> |---|---|---|
> | 느낌 | 단순하고 귀엽고 즉각적 | 디테일하고 따뜻하고 굿즈스러운 |
> | 어울리는 상품 | 스티커·폰케이스·머그컵 | T셔츠·에코백·쿠션 |
> | `--niji 6` | 선택 | 권장 |

### 4. `{color_palette}` — 색감은?

**스타일 A** — 최소한의 색:

- `two-color palette, light grey and white with black outline accents`
- `soft pastel blue and white, minimal warm grey accents`
- `warm cream and brown tones, simple cozy palette`

**스타일 B** — 따뜻하고 생동감 있는 색:

- `warm coral and cream, soft yellow highlights`
- `mint green and soft white, gentle pastel tones`
- `lavender and warm ivory, cozy pastel palette`
- `soft sky blue and warm peach, friendly warm tones`

### 5. `{composition}` — 구도는?

- `single character centered, full body shown, lots of white space around` *(단일 캐릭터 — 기본)*
- `character slightly off-center, props and objects naturally arranged around` *(소품 포함)*
- `close-up from waist up, face and hands clearly visible` *(상반신 클로즈업)*
- `character from a slight front-angle, dynamic pose` *(약간 각도 있는 구도)*

---

## ✏️ 적용 예시 8개

---

### 예시 1 — 💻 상어 야근 탈진 — 스타일 A

```
A chubby grey shark with tiny stubby fins, slumped face-first over a keyboard, a small speech bubble showing "...", simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, two-color palette, light grey and white with black outline accents, single character centered, full body shown, lots of white space around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 2 — ☕ 곰 출근 생존 커피 — 스타일 A

```
A sleepy brown bear cub, holding an oversized coffee cup with both hands, eyes half-open, steam rising from the cup, simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, warm cream and brown tones, simple cozy palette, single character centered, full body shown, lots of white space around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 3 — 🛋️ 고양이 퇴근 후 소파 — 스타일 A

```
A sleepy orange tabby cat with half-closed eyes, lying on a sofa under a blanket, smartphone in hand, snacks nearby, completely relaxed expression, simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, soft pastel blue and white, minimal warm grey accents, single character centered, full body shown, lots of white space around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 4 — 📅 펭귄 월요일 아침 — 스타일 A

```
A tiny fluffy penguin with a round belly, in pajamas, alarm going off beside them, refusing to get up, one eye barely open, simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, soft pastel blue and white, minimal warm grey accents, single character centered, full body shown, lots of white space around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 5 — 🩺 토끼 의사 — 스타일 A

```
A soft lavender bunny with floppy ears, wearing a tiny stethoscope and white coat, holding a clipboard with a tired smile, simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, two-color palette, light purple and white with black outline accents, single character centered, full body shown, lots of white space around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 6 — 🎨 햄스터 디자이너 — 스타일 A

```
A plump golden hamster with chubby cheeks, drawing on a tablet with intense focus, multiple tiny reference images pinned around, tongue slightly out in concentration, simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, warm cream and brown tones, simple cozy palette, character slightly off-center, props and objects naturally arranged around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 7 — 💪 개구리 억지 헬스 — 스타일 A

```
A small green frog with big round eyes, half-heartedly lifting a tiny dumbbell at the gym, exhausted expression, sweat drops flying, simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, two-color palette, mint green and white with black outline accents, single character centered, full body shown, lots of white space around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 8 — ☕ 고양이 카공족 — 스타일 A

```
A sleepy orange tabby cat with half-closed eyes, sitting cross-legged with a tiny laptop at a cozy cafe, matcha latte on the table, cozy focused expression, simple chibi kawaii sticker illustration, minimal clean linework, extremely soft rounded body shapes, flat color fills with very limited palette, small dot eyes, no complex details, white background, like a LINE Friends or KakaoTalk emoticon sticker, highly relatable and cute, soft pastel blue and white, minimal warm grey accents, character slightly off-center, props and objects naturally arranged around. Clean white background, print-ready, no text. --ar 1:1 --s 150
```

![image.png](image.png)

---

## 🔧 변주 팁

| 이걸 바꾸시면 | 효과 |
| --- | --- |
| `{character}` 고정 + `{occupation_scene}` 만 변경 | 같은 캐릭터 직업 시리즈 (굿즈 라인업) |
| `{occupation_scene}` 고정 + `{character}` 변경 | 같은 상황 다른 동물 시리즈 |
| 스타일 A → B 전환 | 같은 장면 더 디테일한 굿즈 버전으로 |
| `--ar 1:1 → 4:5` | 인스타그램·폰케이스 비율 |
| `--niji 6` 추가 | 더 밝고 일본 애니 감성 강화 |
| `speech bubble showing "..."` 추가 | 감정 강조, 스티커 느낌 강화 |

---

## ⚠️ 핵심 팁 5가지

1. **캐릭터 하나 고정이 핵심이에요.** 같은 캐릭터로 직업·상황 시리즈 찍으면 자연스러운 굿즈 라인이 돼요.
2. **스타일 A는 `--s 150` 이하.** 높이면 선이 복잡해지고 스티커 느낌이 사라져요.
3. **스타일 B에 `--niji 6` 을 붙이면** 캐릭터 눈이 더 크고 선명해져요. 치비 굿즈 느낌이 훨씬 강해져요.
4. **말풍선 `...` 은 OK.** 하지만 단어·문장은 미드저니가 깨뜨려요. 텍스트가 필요하면 Canva에서 따로 넣으세요.
5. **소품을 구체적으로 묘사하세요.** `keyboard`, `tiny stethoscope`, `oversized coffee cup` 처럼 소품 디테일이 공감 포인트를 만들어줘요.

---

## ✅ 시리즈 만드는 추천 흐름

1. 캐릭터 하나를 정하세요. (상어, 곰, 고양이 등)
2. 첫 번째 상황 프롬프트로 스타일을 확인하세요.
3. 마음에 들면 `--seed [번호]` 를 고정하고 `{occupation_scene}` 만 바꾸세요.
4. 5~10개 시리즈로 묶어서 스티커 시트·굿즈 세트로 판매하세요.

> 💡 **상시판매형 추천 조합.** ① 야근·커피·월요병 3종 세트 — 직장인 공감 최강. ② 직업별 캐릭터 시리즈 (의사·선생님·바리스타) — 직업 선물용. ③ 운동·다이어트·카페 생활 시리즈 — MZ 라이프스타일.
