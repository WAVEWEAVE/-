> **동물이 인간 일상을 사는 유머 일러스트**를 만드는 프롬프트입니다. 단일 캐릭터도, 2컷 대비 구도도 OK!
> T셔츠·에코백·머그컵 등 POD 상품에 바로 쓸 수 있어요.
> 빈티지 펜화 또는 치비 카와이, 두 가지 그림체를 제공합니다.

---

## 📌 이 프롬프트는 어떤 용도인가요?

**동물 캐릭터가 인간의 일상을 수행하는** 공감형 유머 일러스트를 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- POD T셔츠·에코백·머그컵 메인 일러스트
- Redbubble / Etsy / 마플샵 업로드 소스
- 텍스트 없이 그림만으로 완성되는 디자인
- 동물 캐릭터 시리즈 굿즈

> ⚠️ **"meme" "cartoon animal" 단어를 쓰지 마세요.** "cartoon animal"은 단순한 어린이 만화 캐릭터를 끌어와요. 이 프롬프트는 `illustration of a [동물]` 로 시작해서 구체적인 동물과 행동을 묘사합니다.

---

## 🚀 빠른 시작

1. **스타일 A (빈티지 펜화)** 또는 **스타일 B (치비 카와이)** 중 하나를 고르세요.
2. 아래 예시 중 마음에 드는 걸 고르세요.
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.

---

## 📐 마스터 프롬프트 본문

```
A humorous illustration of {animal_scene}, drawn in {art_style} with {color_tone} on a {background} background, {composition}. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 1:1 --s 250
```

---

## ⚙️ 옵션 파라미터

| 파라미터 | 스타일 A (빈티지) | 스타일 B (치비) | 메모 |
| --- | --- | --- | --- |
| `--ar` | `1:1` / `16:9` 2컷 | `1:1` 권장 | |
| `--style` | `raw` 추가 | 생략 | 빈티지는 raw 필수 |
| `--s` | `200`~`300` | `150`~`200` | |

> 💡 **스타일 B를 쓸 때** `--niji 6` 파라미터를 추가하면 치비 비례와 부드러운 채색이 더 잘 나옵니다.

---

## 📌 변수 5개 — 모두 필수

### 1. `{animal_scene}` — 어떤 동물이 어떤 인간 일상을?

**동물 선택:** 고양이·개구리·너구리·오리·병아리·카피바라·곰·까마귀·토끼
**인간 행동:** 라면 먹기·통근·공부·재택근무·카페·장보기·헬스·편의점

단일 캐릭터 예시:

- `a fat round cat wrapped in a green blanket, hunched over a steaming bowl of ramen noodles, noodles dripping everywhere, looking deeply content`
- `a frog wearing a tall witch hat, riding an electric scooter with one hand casually in its pocket, utterly unbothered`
- `a raccoon sitting at a messy desk surrounded by stacked books, holding a pencil and looking overwhelmed`
- `a small chick typing urgently on an open laptop, leaning in dangerously close to the screen`
- `a capybara in a business suit sitting in a meeting room, staring blankly at a whiteboard with empty eyes`
- `a bear pushing an overflowing grocery cart, squinting in confusion at a shopping list held upside down`
- `a rabbit standing in a convenience store at 2am, staring blankly at instant noodle options under bright fluorescent light`
- `a crow in a delivery uniform on a bicycle at full speed, packages falling out of every bag`

2컷 대비 예시:

- `two panels: left shows a cat alert and sparkling holding coffee, right shows the same cat completely melted and hollow-eyed without it`
- `two panels: left shows a frog cheerfully heading to work on Monday, right shows the same frog dragging its feet on Friday afternoon`

> 💡 **디테일이 생명입니다.** "cat eating ramen"보다 "fat round cat wrapped in a blanket, hunched over a steaming bowl, noodles dripping everywhere"가 훨씬 풍성하게 나옵니다.

### 2. `{art_style}` — 스타일 A 또는 B 중 선택

**스타일 A — 빈티지 펜화** (개구리 스쿠터 이미지 계열)

```
fine expressive pen and ink linework with subtle cross-hatching for depth, muted earthy color palette, whimsical vintage folk illustration quality, like an old naturalist field guide or antique children's storybook drawing, slightly textured hand-drawn feel
```

**스타일 B — 치비 카와이** (고양이 라면 이미지 계열)

```
chibi kawaii illustration with extremely round plump character proportions, clean smooth outlines, soft flat color fills with gentle highlights, big expressive sparkly eyes, warm vibrant color palette, cozy comfort aesthetic, like a modern Korean character IP merchandise illustration
```

> 💡 **스타일 선택 기준**
> | | 스타일 A 빈티지 펜화 | 스타일 B 치비 카와이 |
> |---|---|---|
> | 무드 | 위트있고 고풍스러운 | 아늑하고 귀여운 |
> | 어울리는 상품 | T셔츠·에코백·포스터 | 머그컵·폰케이스·쿠션 |
> | 타겟 | 고블린코어·코티지코어 | 캐릭터 굿즈·카와이 |
> | 추가 파라미터 | `--style raw --s 250` | `--s 150` 또는 `--niji 6` |

### 3. `{color_tone}` — 컬러는?

**스타일 A (빈티지)** — 머티드 어스톤:

- `muted sage green and warm sepia`
- `dusty olive and aged cream`
- `faded forest green and warm brown`
- `soft slate blue and warm ivory`

**스타일 B (치비)** — 따뜻하고 채도 있는 2~3색:

- `warm tangerine orange and soft teal with cream`
- `golden yellow and mint green`
- `soft coral and pale sky blue`
- `warm peach and dusty sage green`

> 💡 **스타일 A에서 "bright" "vibrant" 단어를 피하세요.** 빈티지 느낌이 사라져요. "muted", "dusty", "faded", "aged"가 핵심입니다.

### 4. `{background}` — 배경은?

단색이 가장 안전. 투명을 원하면 `clean white` 후 배경 제거 도구 쓰세요.

- `clean white`
- `aged cream` *(스타일 A에 잘 어울림)*
- `warm off-white`
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

### 예시 1 — 🐱 고양이 라면 먹방 — 스타일 B 치비 (오렌지+틸)

```
A humorous illustration of a fat round cat wrapped in a soft green blanket, hunched over a steaming bowl of ramen noodles with a blissful expression, noodles dripping off its face and onto the table, drawn in chibi kawaii illustration with extremely round plump character proportions, clean smooth outlines, soft flat color fills with gentle highlights, big expressive sparkly eyes, warm vibrant color palette, cozy comfort aesthetic, like a modern Korean character IP merchandise illustration with warm tangerine orange and soft teal with cream on a clean white background, centered as one large illustration filling the frame with wide margins. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 2 — 🐸 개구리 통근 스쿠터 — 스타일 A 빈티지 (세이지+세피아)

```
A humorous illustration of a frog wearing a tall witch hat, riding an electric scooter with one hand casually in its pocket, looking utterly unbothered and aloof, drawn in fine expressive pen and ink linework with subtle cross-hatching for depth, muted earthy color palette, whimsical vintage folk illustration quality, like an old naturalist field guide or antique children's storybook drawing, slightly textured hand-drawn feel with muted sage green and warm sepia on an aged cream background, centered as one large illustration filling the frame with wide margins. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 1:1 --style raw --s 250
```

![image.png](image.png)

---

### 예시 3 — 🦝 너구리 공부 — 스타일 B 치비 (골든옐로+민트)

```
A humorous illustration of a round chubby raccoon sitting at a messy desk completely surrounded by towering stacked books, gripping a pencil with a wide-eyed overwhelmed expression, eraser shavings everywhere, drawn in chibi kawaii illustration with extremely round plump character proportions, clean smooth outlines, soft flat color fills with gentle highlights, big expressive sparkly eyes, warm vibrant color palette, cozy comfort aesthetic, like a modern Korean character IP merchandise illustration with golden yellow and mint green on a clean white background, centered as one large illustration filling the frame with wide margins. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 4 — 🐥 병아리 재택근무 — 스타일 B 치비 (피치+세이지)

```
A humorous illustration of a tiny round chick hunched over an open laptop, nose nearly touching the screen with intense focus, tiny wings barely reaching the keyboard, coffee cup beside it, drawn in chibi kawaii illustration with extremely round plump character proportions, clean smooth outlines, soft flat color fills with gentle highlights, big expressive sparkly eyes, warm vibrant color palette, cozy comfort aesthetic, like a modern Korean character IP merchandise illustration with warm peach and dusty sage green on a clean white background, centered as one large illustration filling the frame with wide margins. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 5 — 🦆 오리 카페 — 스타일 A 빈티지 (올리브+브라운)

```
A humorous illustration of a duck in a barista apron standing at an espresso machine with a look of absolute devotion, one wing resting on the machine as if communing with it, steam swirling dramatically, drawn in fine expressive pen and ink linework with subtle cross-hatching for depth, muted earthy color palette, whimsical vintage folk illustration quality, like an old naturalist field guide or antique children's storybook drawing, slightly textured hand-drawn feel with dusty olive and warm brown on an aged cream background, centered as one large illustration filling the frame with wide margins. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 1:1 --style raw --s 250
```

![image.png](image.png)

---

### 예시 6 — 🐰 토끼 새벽 편의점 — 스타일 B 치비 (코랄+스카이블루)

```
A humorous illustration of a round fluffy rabbit standing alone in a convenience store at 2am, staring blankly at a wall of instant noodle options under harsh fluorescent light, one paw raised as if unable to decide, drawn in chibi kawaii illustration with extremely round plump character proportions, clean smooth outlines, soft flat color fills with gentle highlights, big expressive sparkly eyes, warm vibrant color palette, cozy comfort aesthetic, like a modern Korean character IP merchandise illustration with soft coral and pale sky blue on a clean white background, centered as one large illustration filling the frame with wide margins. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 1:1 --s 150
```

![image.png](image.png)

---

### 예시 7 — 🐸 개구리 커피 전후 (2컷) — 스타일 A 빈티지 (세이지+세피아)

```
A humorous illustration of two side-by-side panels: left panel shows a frog alert and sparkling with joy clutching a coffee cup with both hands, right panel shows the exact same frog completely wilted and deflated without it, eyes hollow and posture collapsed, drawn in fine expressive pen and ink linework with subtle cross-hatching for depth, muted earthy color palette, whimsical vintage folk illustration quality, like an old naturalist field guide or antique children's storybook drawing, slightly textured hand-drawn feel with muted sage green and warm sepia on an aged cream background, placed side by side as two equal panels with even breathing room. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 16:9 --style raw --s 250
```

![image.png](image.png)

---

### 예시 8 — 🐱 고양이 월요일 전후 (2컷) — 스타일 B 치비 (오렌지+틸)

```
A humorous illustration of two side-by-side panels: left panel shows a round fluffy cat on Friday evening sparkling with joy doing a happy dance, right panel shows the exact same cat on Monday morning as a completely deflated puddle on the floor, barely lifting its face, drawn in chibi kawaii illustration with extremely round plump character proportions, clean smooth outlines, soft flat color fills with gentle highlights, big expressive sparkly eyes, warm vibrant color palette, like a modern Korean character IP merchandise illustration with warm tangerine orange and soft teal on a clean white background, placed side by side as two equal panels with even breathing room. The humor reads entirely from the visual — no text, no speech bubbles. Print-ready illustration with clean edges, rendered as graphic design. --ar 16:9 --s 150
```

![image.png](image.png)

---

## 🔧 변주 팁

| 이걸 바꾸시면 | 효과 |
| --- | --- |
| `{animal_scene}` 의 동물만 | 같은 행동을 다른 동물로. 시리즈 통일감 |
| `{animal_scene}` 의 행동만 | 같은 동물이 다른 상황. 캐릭터 IP 구축 |
| 스타일 A ↔ 스타일 B 전환 | 같은 장면, 고풍스러운 느낌 ↔ 아늑한 느낌 |
| `{color_tone}` 만 | 같은 캐릭터, 다른 시즌·무드 |
| `{background}` 를 `matte black` 으로 | 다크 모드 굿즈 라인 |
| 스타일 B에 `--niji 6` 추가 | 치비 비례와 부드러운 채색이 더 강하게 나옴 |
| `--s 150→250` (스타일 B) | 캐릭터 개성과 표정이 더 강해짐 |
| `--sref [URL]` 추가 | 여러 장면을 같은 동물·톤으로 통일 |
| 예시 7·8처럼 2컷 대비 | `--ar 16:9` + `two side-by-side panels` 구도로 |

---

## ⚠️ 핵심 팁 6가지

1. **행동 디테일이 생명입니다.** "cat eating ramen"보다 "fat round cat wrapped in a blanket, noodles dripping everywhere"가 훨씬 풍성하게 나와요.
2. **스타일 A에는 `--style raw` 필수.** 없으면 빈티지 질감이 사라져요.
3. **스타일 A 색상은 "muted" "dusty" "faded".** "bright" "vibrant"는 빈티지 느낌을 망쳐요.
4. **스타일 B에는 `--style raw` 쓰지 마세요.** 치비 특유의 부드러운 채색이 딱딱해져요.
5. **2컷 대비는 반드시 `--ar 16:9`.** `1:1`로 하면 두 장면이 뭉개져요.
6. **배경은 `clean white` 또는 `aged cream`.** 배경 제거 후 모든 상품에 바로 쓸 수 있어요.

---

## ✅ 시리즈 만드는 추천 흐름

1. 동물 하나를 고정하세요. (예: 고양이 또는 개구리)
2. 스타일 A 또는 B를 정하세요.
3. 행동만 바꿔서 4~5개 시리즈를 만드세요. (라면→카페→재택→편의점)
4. 첫 결과의 `-seed` 값을 다음에 붙이면 동물 비례·톤이 통일돼요.
5. `--sref [첫 결과 URL]` 추가하면 완벽한 동물 캐릭터 패키지!

> 💡 **상시판매형 추천 조합.** 고양이·토끼 + 스타일 B 치비 → 아늑한 일상 공감 굿즈에 강함. 개구리·오리 + 스타일 A 빈티지 → 고블린코어·코티지코어 니치에 강함.
