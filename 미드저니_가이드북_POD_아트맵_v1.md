> **도시 지도를 기반으로 한 미니멀 아트맵 포스터**를 만드는 프롬프트입니다.
> 컬러 팔레트·도시·구도를 바꿔 무한한 시리즈를 만들 수 있어요.
> 포스터·캔버스·폰케이스·머그컵 등 전 POD 상품에 바로 쓸 수 있어요.

---

## 📌 이 프롬프트는 어떤 용도인가요?

미니멀한 도시 지도 일러스트에 도시명·좌표·국가를 넣은 **아트맵 포스터** 디자인을 만드는 프롬프트예요.

이런 데 쓸 수 있어요:

- POD 포스터·캔버스 프린트 메인 이미지
- Redbubble / Etsy / 마플샵 여행 기념 굿즈
- 커플·신혼 기념 커스텀 포스터
- 폰케이스·노트커버 디자인 소스

> ⚠️ **미드저니는 텍스트를 정확히 렌더링하지 못해요.** 도시명·좌표·국가 텍스트는 미드저니 이후 **Canva / Photoshop / Figma** 에서 별도로 추가하세요. 이 가이드의 `{city}` 변수는 지도 이미지 생성용이며, 텍스트는 후처리 단계에서 넣어요.

---

## 🚀 빠른 시작

1. 아래 8가지 컬러 팔레트 중 하나를 고르세요.
2. 원하는 도시를 정하세요.
3. **"완성 프롬프트"** 를 통째로 복사하세요.
4. [alpha.midjourney.com](https://alpha.midjourney.com/) 에 붙여넣고 Enter.
5. 결과 이미지를 Canva에 올리고 도시명·좌표·국가를 추가하세요.

---

## 📐 마스터 프롬프트 본문

```
A minimalist flat vector city map art print of {city}, {color_palette}, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, {water_treatment}, {composition}. Print-ready, no text. --ar 2:3 --s 150
```

---

## ⚙️ 옵션 파라미터

| 파라미터 | 권장값 | 메모 |
| --- | --- | --- |
| `--ar` | `2:3` | 세로 포스터 비율 (기본 추천) |
| `--ar` | `1:1` | 정사각형 (폰케이스·머그컵) |
| `--s` | `100`~`150` | 낮을수록 깔끔한 플랫 벡터 느낌 |
| `--style raw` | 선택 추가 | 더 그래픽적이고 딱딱한 플랫 스타일 원할 때 |

---

## 📌 변수 4개 — 모두 필수

### 1. `{city}` — 어떤 도시 지도인가요?

도시명을 영어로 입력하세요. 유명 도시일수록 실제 거리망에 가깝게 생성돼요.

한국:

- `Seoul, South Korea`
- `Busan, South Korea`
- `Jeju Island, South Korea`

유럽:

- `Paris, France`
- `Vienna, Austria`
- `Barcelona, Spain`
- `Amsterdam, Netherlands`

북미:

- `New York City, USA`
- `Brooklyn, New York`
- `New Orleans, USA`

아시아:

- `Tokyo, Japan`
- `Kyoto, Japan`
- `Manila, Philippines`

> 💡 **도시 이름은 지도 패턴 생성에만 영향을 줘요.** 미드저니가 실제 지도를 완벽히 재현하진 않아요. 결과물은 해당 도시 분위기의 아트 일러스트예요. 도시명 텍스트는 Canva에서 따로 넣어주세요.

### 2. `{color_palette}` — 컬러 테마는?

| 팔레트 이름 | 프롬프트 값 |
| --- | --- |
| 차콜+스카이블루 | `charcoal dark grey streets with sky blue water accent, cream white background` |
| 더스티로즈 | `dusty rose and blush pink tones, warm beige background, muted street lines` |
| 머스타드+차콜 | `bold mustard yellow fills and dark charcoal streets, white background, high contrast` |
| 크림+세이지 | `soft antique cream and muted sage green tones, warm ivory background` |
| 포레스트그린 | `deep forest green background with off-white street lines, minimal high contrast` |
| 로즈+민트 | `dusty rose streets and mint sage water, soft pastel palette, cream background` |
| 네이비+골드 | `deep navy blue background with gold accent streets, elegant dark background` |
| 블랙+레드 | `bold black map with red accent highlights, stark white background, graphic editorial` |

### 3. `{water_treatment}` — 강·바다·호수 처리는?

- `rivers and water bodies in a lighter tonal accent` *(기본 하천 강조)*
- `coastal water as a solid flat color shape, sharp city boundary edge` *(해안 도시)*
- `no water bodies visible, purely urban street grid` *(내륙 도시)*
- `large river as a bold diagonal shape cutting through the city center` *(강변 도시)*

### 4. `{composition}` — 구도·여백은?

- `map occupying the upper 70% of the frame, generous white space below` *(하단 텍스트 공간 확보 — 기본 추천)*
- `full frame map filling the entire image edge to edge` *(꽉 찬 맵)*
- `map centered with a clean white margin on all sides` *(균등 여백)*
- `tight close-up on the dense urban core, cropped composition` *(도심 클로즈업)*

---

## 🖋️ 후처리 텍스트 변수 (Canva / Photoshop)

미드저니로 지도 이미지 생성 후, 디자인 툴에서 아래 텍스트를 추가하세요.

| 변수 | 예시 값 | 스타일 가이드 |
| --- | --- | --- |
| `{CITY_NAME}` | SEOUL · PARIS · NEW YORK | 산세리프 대문자, 자간 넓게 |
| `{COORDINATES}` | 37.56°N / 126.97°E | 얇은 세리프 또는 모노스페이스 |
| `{COUNTRY}` | SOUTH KOREA · FRANCE | 캡스락 스몰텍스트 |

> 💡 **Canva 추천 폰트 조합.** 도시명: Montserrat Bold / 좌표: Raleway Light / 국가: Montserrat Regular

---

## ✏️ 적용 예시 8개

---

### 예시 1 — 🗺️ 서울 — 차콜+스카이블루

```
A minimalist flat vector city map art print of Seoul, South Korea, charcoal dark grey streets with sky blue water accent, cream white background, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, rivers and water bodies in a lighter tonal accent, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** SEOUL / 37.56°N · 126.97°E / SOUTH KOREA

![image.png](image.png)

---

### 예시 2 — 🗺️ 파리 — 더스티로즈

```
A minimalist flat vector city map art print of Paris, France, dusty rose and blush pink tones, warm beige background, muted street lines, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, rivers and water bodies in a lighter tonal accent, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** PARIS / 48.85°N · 2.35°E / FRANCE

![image.png](image.png)

---

### 예시 3 — 🗺️ 브루클린 — 머스타드+차콜

```
A minimalist flat vector city map art print of Brooklyn, New York, bold mustard yellow fills and dark charcoal streets, white background, high contrast, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, coastal water as a solid flat color shape, sharp city boundary edge, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** BROOKLYN / 40.65°N · 73.95°W / NEW YORK · UNITED STATES

![image.png](image.png)

---

### 예시 4 — 🗺️ 바르셀로나 — 크림+세이지

```
A minimalist flat vector city map art print of Barcelona, Spain, soft antique cream and muted sage green tones, warm ivory background, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, coastal water as a solid flat color shape, sharp city boundary edge, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** BARCELONA / 41.38°N · 2.17°E / SPAIN

![image.png](image.png)

---

### 예시 5 — 🗺️ 마닐라 — 포레스트그린

```
A minimalist flat vector city map art print of Manila, Philippines, deep forest green background with off-white street lines, minimal high contrast, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, coastal water as a solid flat color shape, sharp city boundary edge, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** MANILA / 14.60°N · 120.98°E / PHILIPPINES

![image.png](image.png)

---

### 예시 6 — 🗺️ 뉴올리언스 — 로즈+민트

```
A minimalist flat vector city map art print of New Orleans, USA, dusty rose streets and mint sage water, soft pastel palette, cream background, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, large river as a bold diagonal shape cutting through the city center, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** NEW ORLEANS / 29.95°N · 90.07°W / LOUISIANA · UNITED STATES

![image.png](image.png)

---

### 예시 7 — 🗺️ 도쿄 — 네이비+골드

```
A minimalist flat vector city map art print of Tokyo, Japan, deep navy blue background with gold accent streets, elegant dark background, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, rivers and water bodies in a lighter tonal accent, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** TOKYO / 35.69°N · 139.69°E / JAPAN

![image.png](image.png)

---

### 예시 8 — 🗺️ 부산 — 블랙+레드

```
A minimalist flat vector city map art print of Busan, South Korea, bold black map with red accent highlights, stark white background, graphic editorial, clean geometric street grid network, top-down aerial view, flat color fills, no 3D, no shadows, graphic design quality, coastal water as a solid flat color shape, sharp city boundary edge, map occupying the upper 70% of the frame, generous white space below. Print-ready, no text. --ar 2:3 --s 150
```

**후처리 텍스트:** BUSAN / 35.10°N · 129.03°E / SOUTH KOREA

![image.png](image.png)

---

## 🔧 변주 팁

| 이걸 바꾸시면 | 효과 |
| --- | --- |
| `{city}` 만 | 같은 컬러 팔레트로 전 세계 도시 시리즈 |
| `{color_palette}` 만 | 같은 도시를 여러 컬러 버전으로 |
| `--ar 2:3 → 1:1` | 폰케이스·머그컵용 정사각형 비율 |
| `--s 150 → 100` | 더 단순하고 깔끔한 플랫 벡터 |
| `--style raw` 추가 | 더 그래픽적이고 인쇄물 느낌 강화 |
| `composition` 을 `full frame` 으로 | 텍스트 없는 순수 맵 패턴 (패턴 상품용) |

---

## ⚠️ 핵심 팁 5가지

1. **`--s` 는 낮게 유지하세요.** 150 이하가 플랫 벡터 지도에 최적이에요. 높이면 너무 복잡하고 지저분해져요.
2. **실제 지도와 완벽히 일치하지 않아요.** 미드저니의 결과는 아트 해석이에요. 정확한 지도가 필요하면 OpenStreetMap 기반 툴을 따로 사용하세요.
3. **텍스트는 반드시 후처리로.** 미드저니에 도시명 텍스트를 넣으면 깨져요. Canva에서 따로 추가하세요.
4. **컬러는 2~3색 이내로.** 많은 색을 지정하면 지저분해져요. 배경색 + 메인색 + 강조색 조합을 지키세요.
5. **`composition` 을 `upper 70%` 로 설정하면** 하단에 자연스러운 여백이 생겨 텍스트 공간이 확보돼요.

---

## ✅ 시리즈 만드는 추천 흐름

1. 컬러 팔레트 하나를 고정하세요.
2. 도시만 바꾸며 시리즈를 찍으세요. (서울·부산·제주 한국 3부작 등)
3. Canva 템플릿 하나 만들어두면 텍스트만 교체하면 돼요.
4. 인기 도시부터: 뉴욕·파리·런던·서울·도쿄 5종이 베스트셀러예요.

> 💡 **베스트셀러 조합.** ① 차콜+스카이블루 — 남성·미니멀 취향 강함. ② 더스티로즈 — 인테리어·선물용 강함. ③ 포레스트그린 — 프리미엄 고급 느낌. ④ 머스타드+차콜 — 젊고 그래픽적, SNS 노출 강함.
