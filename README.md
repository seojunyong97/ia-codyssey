# 🎬 날씨만 좋았어도

> **AI 기반 브랜드 광고 패키지 — 스토리보드(기획) 문서**

| 항목 | 내용 |
|------|------|
| **작품명** | 날씨만 좋았어도 |
| **공모전** | 제7회 기상청 달콤기후 공모전 (미래날씨 주제) |
| **제작자** | 서준용 |
| **제작 방식** | AI 생성형 도구 기반 영상 제작 |
| **길이 / 규격** | 약 43초 / 가로형 1920×1080 |

---

## 📁 파일 구성

| 파일 | 설명 |
|------|------|
| `weather.mp4` | 최종 영상 (16:9, 1920×1080) |
| `weather11.mp4` | 1:1 비율 버전 (플랫폼별 대응) |
| `report2.pdf` | 스토리보드 기획 문서 (PDF) |

---

## 1. 브랜드 아이덴티티

| 항목 | 내용 |
|------|------|
| **브랜드/캠페인** | 제7회 기상청 달콤기후 공모전 — 미래날씨 부문 |
| **타겟** | 10~30대 일반 대중 (기후 변화에 관심이 낮은 젊은 세대) |
| **톤앤매너** | 시네마틱 로맨스 / 웃기면서 슬픈 / Black Pro-Mist 필터 감성 (따뜻한 글로우) |
| **USP (차별점)** | "미래 기후 재앙"을 다큐/경고가 아닌 **"망한 첫 데이트"** 로맨스 코미디로 풀어, 감정적 공감을 통해 기후 경각심을 전달 |
| **핵심 메시지** | "지금 당연한 맑은 하루가, 미래에도 당연하려면 오늘의 선택이 필요하다." |
| **광고 목적** | 인지(Awareness) — 기후변화의 영향을 일상적 감정(첫 데이트)으로 체감시켜, "미래날씨"에 대한 관심과 대응 의지를 환기 |

---

## 2. 사용 도구 목록

| 카테고리 | 도구명 | 사용 목적 | 대체 도구 |
|----------|--------|-----------|-----------|
| 이미지 생성 | 나노바나나2 (Gemini 기반) | 씬별 키 비주얼 이미지 생성 (실사 스타일, 커플 캐릭터, 장소별 재난/맑음 페어) | Midjourney, DALL-E 3 |
| 이미지 확장/참조 | 프리픽 매그니픽 — Space 기능 | 인물 레퍼런스 이미지를 물려 일관된 캐릭터를 유지하며 씬 연결 생성 | Midjourney cref, IP-Adapter |
| 비디오 생성/변환 | 프리픽 매그니픽 — 클링 2.5/2.6 주로 활용 | 시작·끝 이미지 기반 영상 클립 생성 (4~5초/컷), 카메라 무빙 적용 | Pika, Kling, Luma |
| 오디오/음악 | Suno AI | 트랙 2개 제작: ①설렘~재난(어쿠스틱→드롭) ②회수(따뜻한 희망 스웰) | Udio, AIVA |
| 음성(TTS) | 클로바보이스 | 뉴스 앵커 나레이션 2문장 (오프닝+엔딩 수미상관) | ElevenLabs, 타입캐스트 |
| 편집 | Premiere Pro | 컷 편집, 자막, 트랜지션(디졸브), 오디오 레벨 조정 | - |

---

## 3. 씬별 스토리보드

> **[인물 고정 블록]** = "A good-looking young Korean couple, early-20s. MAN: clean handsome face wearing round glasses, soft natural perm short hair, trendy oversized shirt. WOMAN: pretty fresh face, light natural makeup, layered medium hair, trendy casual outfit (cropped cardigan with tote bag)."
>
> **[글로우 꼬리표]** = "Dreamy soft-focus cinematic look: glowing blooming highlights bleeding softly, hazy diffused mist over the image, gentle halation around bright areas, soft milky glow, lifted faded blacks, low contrast, soft pastel film tones, backlit misty glow, shot on vintage film. Photorealistic, natural skin texture, 16:9 horizontal, no text."

---

### 씬 0 | 홀로그램 뉴스 (오프닝)

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3~4초 |
| **목표 메시지** | 근미래 세계관 설정 + 뉴스 형식의 기후 위기 복선 (엔딩과 수미상관) |
| **화면 구성** | 일반적인 한국 거실, TV 자리에 반투명 홀로그램 뉴스 화면만 떠 있음. 인물 없음. 근미래(홀로그램 하나만 미래, 나머진 현재와 동일). |
| **내레이션** | VO(뉴스 앵커): "올해 들어 기상 이변이 계속되고 있습니다." |
| **사용 도구** | 이미지: 나노바나나2 / 비디오: 클링 2.6 / 오디오: 네이버 클로바더빙 (앵커 TTS) |
| **프롬프트** | `A normal modern Korean living room, clean and minimal, everything looks like present day EXCEPT a translucent floating holographic news screen hovering where a TV would normally be, showing a vague news anchor and weather icons. Only the hologram is futuristic, the rest is ordinary. No people. [글로우 꼬리표]` |
| **출력 결과** | 근미래 거실 + 홀로그램 뉴스 키비주얼 확보. 판타지 한 방울(홀로그램) 적용 성공. |
| **파일명** | `0씬.mp4` |

---

### 씬 1-C1 | 한강 데이트 — 풀샷

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3초 |
| **목표 메시지** | 행복한 데이트 분위기 설정 — 커플의 설렘을 각인 |
| **화면 구성** | 한강 공원 피크닉. 돗자리+도시락. 여자가 김밥을 하나 집어먹는 중. 풀샷. |
| **내레이션** | (없음 — 설렘 어쿠스틱 BGM만) |
| **사용 도구** | 이미지: 나노바나나2 + 프리픽 Space (인물 레퍼 고정) / 비디오: 매그내픽 |
| **프롬프트** | `[인물 고정 블록] The couple sitting on a picnic mat by the Han River, lunchbox of gimbap between them, the woman casually picking up a piece of gimbap and eating it, relaxed happy daytime date, blue sky. Wide shot. [글로우 꼬리표]` |
| **출력 결과** | 한강 피크닉 커플 키비주얼 확보. 블프 글로우 톤 적용됨. |
| **파일명** | `1씬1컷.mp4` |

---

### 씬 1-C2 | 한강 데이트 — 여자 오물오물

| 항목 | 내용 |
|------|------|
| **씬 길이** | 2초 |
| **목표 메시지** | 여자의 귀여운 모습 — 남자가 반할 대상을 관객에게도 전달 |
| **화면 구성** | 여자 클로즈업. 입 오물오물, 볼 빵빵, 만족 미소. |
| **사용 도구** | 이미지: 나노바나나2 + 프리픽 Space / 비디오: 매그내픽 |
| **프롬프트** | `Close-up of the same young Korean woman happily eating with her mouth closed, cheeks slightly full, content satisfied smile, soft daylight, Han River bokeh. [글로우 꼬리표]` |
| **출력 결과** | 귀여운 클로즈업 확보. |
| **파일명** | `1씬2컷.mp4` |

---

### 씬 1-C3 | 한강 데이트 — 반한 남자 클로즈업 ★감정 절정

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3초 |
| **목표 메시지** | 남자가 진심으로 반한 순간 — 이후 고백(2씬)의 동기 |
| **화면 구성** | 남자 클로즈업. 손에 아무것도 없이, 여자를 바라보며 흐뭇하게 반한 표정. |
| **사용 도구** | 이미지: 나노바나나2 + 프리픽 Space / 비디오: 매그내픽 |
| **프롬프트** | `Close-up of the same young Korean man (round glasses, soft perm) gazing at the woman with a soft enchanted smile, hands empty and resting naturally, clearly falling for her, tender affectionate eyes, warm soft daylight, Han River bokeh. [글로우 꼬리표]` |
| **출력 결과** | 감정이 담긴 남자 클로즈업 확보. 안경+파마 일관성 유지. |
| **파일명** | `1씬3컷.mp4` |

---

### 씬 2-C1 | 벚꽃길 — 어색하게 걷기 (풀샷)

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3초 |
| **목표 메시지** | 장소 전환 + 아직 손 안 잡은 어색한 거리 = 고백 전 긴장 |
| **화면 구성** | 벚꽃 만개 길. 나란히 걷지만 손은 안 잡고 사이에 어색한 간격. 풀샷. |
| **사용 도구** | 이미지: 나노바나나2 + 프리픽 Space / 비디오: 매그내픽 |
| **프롬프트** | `[인물 고정 블록] Walking down a cherry blossom path in full bloom, side by side but NOT holding hands, a slightly shy awkward gap between them, tender mood building, petals falling. Wide full shot, hands apart. [글로우 꼬리표]` |
| **출력 결과** | 벚꽃길+어색한 커플 풀샷 확보. 회수씬(3-R1) 대비 구도 확정. |
| **파일명** | `2씬1컷.mp4` |

---

### 씬 2-C2 | 벚꽃길 — 남자 결심 (클로즈업)

| 항목 | 내용 |
|------|------|
| **씬 길이** | 2초 |
| **목표 메시지** | 고백 의지 — 관객의 응원 유도 |
| **화면 구성** | 남자 익스트림 클로즈업. 결심 표정. 여자 안 보임. |
| **사용 도구** | 이미지: 나노바나나2 + 프리픽 Space / 비디오: 매그내픽 |
| **프롬프트** | `Extreme close-up of the same man's face only (round glasses, soft perm), walking and smiling softly to himself, eyes looking slightly downward, not looking at the camera, no other person visible, cherry blossom bokeh. [글로우 꼬리표]` |
| **출력 결과** | 남자 단독 클로즈업, 결심 표정 확보. |
| **파일명** | `2씬2컷.mp4` |

---

### 씬 2-C3 | 벚꽃길 — 떨리는 손 (클로즈업)

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3초 |
| **목표 메시지** | 숨긴 설렘이 손에서 새어나오는 순간 — 코미디+감정 교차점 |
| **화면 구성** | 손 익스트림 클로즈업. 여자 손 자연스럽게 늘어짐. 남자 손 떨리며 다가감. 걸으면서. |
| **사용 도구** | 이미지: 나노바나나2 / 비디오: 매그내픽 |
| **프롬프트** | `Extreme close-up of two hands while walking, the woman's hand hanging naturally and relaxed at her side unaware, the man's hand slowly and nervously reaching out toward hers, his fingers trembling slightly. Cherry blossom petals, warm daylight, shallow depth of field. [글로우 꼬리표]` |
| **출력 결과** | 떨리는 손+여자 손 대비 클로즈업 확보. |
| **파일명** | `2씬3컷.mp4` |

---

### 씬 2-C3.5 | 하늘 인서트 (불길한 전조)

| 항목 | 내용 |
|------|------|
| **씬 길이** | 2초 |
| **목표 메시지** | 재난의 복선 — "뭔가 올 것 같은" 불안감 |
| **화면 구성** | 하늘 앙각. 먹구름이 빠르게 밀려오며 빛 어두워짐. 구름만, 벚꽃 없이. |
| **사용 도구** | 이미지: 나노바나나2 / 비디오: 매그내픽 |
| **프롬프트** | `Low angle shot looking straight up at the sky, dark ominous clouds rapidly rolling in covering the blue sky, dramatic threatening cloud formation, the light dimming. Foreboding tense mood. [글로우 꼬리표]` |
| **출력 결과** | 먹구름 인서트 확보. 하늘+구름 집중. |
| **파일명** | `2씬3.5컷.mp4` |

---

### 씬 2-C4 | 우박 + 도망 (재난/절정) ★

| 항목 | 내용 |
|------|------|
| **씬 길이** | 4초 |
| **목표 메시지** | 날씨가 고백을 부숨 — 코미디+비극의 정점 |
| **화면 구성** | 우박 쏟아짐. 여자 가방 머리에 받치고 도망. 벚꽃 흩날림. |
| **사용 도구** | 이미지: 나노바나나2 / 비디오: 매그내픽 |
| **프롬프트** | `The couple on the cherry blossom path during a sudden hailstorm, ice pellets pouring down. The man still wearing round glasses, standing stunned and frozen. The woman running away holding her tote bag over her head. Petals scattering chaotically. Comedic panicked mood. [글로우 꼬리표]` |
| **출력 결과** | 우박+도망 장면 확보. 안경 유지됨. |
| **파일명** | `2씬4컷.mp4` |

---

### 전환 | 자막

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3초 |
| **목표 메시지** | 감정 전환점 — 코미디에서 메시지로. 관객에게 직접 질문. |
| **화면 구성** | 남자 멍한 컷 위 또는 검은 화면에 흰 자막 중앙 배치 |
| **카피** | "이 미래, 바뀔 수 있습니다." |
| **사용 도구** | 편집: Premiere (자막 삽입) |

---

### 회수 씬 — 벚꽃길 손잡기 성공 (맑음 버전) ★떡밥회수

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3초 |
| **목표 메시지** | 떡밥 회수 ① — 실패했던 손잡기가 맑은 날엔 성공. 카타르시스. |
| **화면 구성** | 2씬 C3과 같은 구도. 같은 벚꽃길인데 맑은 날. 둘이 손 꼭 잡고 걸음. |
| **사용 도구** | 이미지: 나노바나나2 + 프리픽 Space (재난 컷을 레퍼런스로 같은 구도 맑음 버전 생성) / 비디오: 매그내픽 |
| **프롬프트** | `[인물 고정 블록] Walking down the SAME cherry blossom path in full bloom, calm gentle breeze, petals softly falling, now HOLDING HANDS happily, warm sunlight, both glowing with joy, SAME composition and camera angle as the earlier blossom wide shot. [글로우 꼬리표]` |
| **출력 결과** | 재난 컷 대비 맑음 버전 확보. 구도 일치율 높음. |
| **파일명** | `2씬3컷화창.mp4` / `2씬3.5컷화창.mp4` |

---

### 씬 3 | 야경 뒷모습 + 엔딩 ★수미상관

| 항목 | 내용 |
|------|------|
| **씬 길이** | 4초 |
| **목표 메시지** | 떡밥 회수 ② — 맑은 밤이면 이렇게 아름다웠을 것 + 수미상관 뉴스 엔딩 |
| **화면 구성** | 야외 전망대. 둘의 뒷모습, 서울 야경 탁 트임. 포커스는 야경(커플은 소프트). 카메라가 야경 쪽으로 틸트. |
| **내레이션** | VO(뉴스 앵커): "오늘도 화창한 날씨가 계속됐는데요." |
| **사용 도구** | 이미지: 나노바나나2 / 비디오: 매그내픽 / 오디오: 클로바더빙 (앵커 TTS) |
| **프롬프트** | `Back view of the same couple at an outdoor mountaintop observation deck at night, seen from behind as small silhouettes, focus on the stunning clear sparkling Seoul city night view with starry sky, the couple slightly soft and out of focus, cityscape sharp and detailed. Wide cinematic night shot. [글로우 꼬리표]` |
| **출력 결과** | 야경 포커스 뒷모습 컷 확보. 패닝용 와이드 구도. |
| **파일명** | `3씬.mp4` |

---

### 엔딩 | 자막 + 마무리

| 항목 | 내용 |
|------|------|
| **씬 길이** | 3초 |
| **목표 메시지** | 브랜드(기상청/공모전) 인지 |
| **화면 구성** | 야경 위 자막 노출 + 공모전 엔딩 로고 |
| **사용 도구** | 편집: Premiere |

---

## 4. 프롬프트 수정 전/후 기록

### [케이스 1] 대상 씬: 1-C3 (반한 남자 클로즈업)

| 항목 | 내용 |
|------|------|
| **수정 전 의도** | 남자가 여자를 바라보며 반한 표정의 클로즈업 |
| **수정 전 프롬프트** | `Close-up of the man gazing at the woman with a soft enchanted smile, tender affectionate eyes, warm daylight, Han River bokeh. [글로우 꼬리표]` |
| **발생한 문제** | 남자가 김밥을 들고 있는 상태로 생성됨 — 이전 씬의 맥락이 잔류하여 도구가 김밥을 포함. 의도는 "바라보는 순간". |
| **수정 후 프롬프트** | `Close-up of the same young Korean man (round glasses, soft perm) gazing at the woman with a soft enchanted smile, **hands empty and resting naturally**, clearly falling for her, tender affectionate eyes, warm soft daylight, Han River bokeh. [글로우 꼬리표]` |
| **수정 이유** | "hands empty and resting naturally"를 명시 추가하여 도구가 소품(김밥)을 생성하지 않도록 네거티브 조건을 포지티브 문장으로 전환. 나노바나나2는 네거티브 프롬프트보다 포지티브 지시에 더 잘 반응함. |
| **결과 변화** | 김밥 제거됨. 빈 손으로 자연스럽게 바라보는 감정적 클로즈업 확보. |

### [케이스 2] 대상 씬: 전체 씬 공통 (Black Pro-Mist 필터 효과)

| 항목 | 내용 |
|------|------|
| **수정 전 의도** | Black Pro-Mist 필터 특유의 부드러운 광 번짐(halation/bloom) 효과 적용 |
| **수정 전 프롬프트** | `...shot on 35mm with a Black Pro-Mist filter — soft glowing highlights, gentle halation, dreamy diffused bloom, slightly lifted blacks, filmic color grade.` |
| **발생한 문제** | 나노바나나2가 "Black Pro-Mist filter"라는 장비 용어를 인식하지 못함 — 필터 효과가 전혀 반영되지 않은 선명한 이미지 출력. |
| **수정 후 프롬프트** | `Dreamy soft-focus cinematic look: glowing blooming highlights bleeding softly, hazy diffused mist over the image, gentle halation around bright areas, soft milky glow, lifted faded blacks, low contrast, soft pastel film tones, backlit misty glow, shot on vintage film.` |
| **수정 이유** | 장비명 대신 시각적 결과를 직접 묘사하는 방식으로 전환. AI 이미지 도구는 장비 이름보다 결과 묘사("glowing bloom, hazy mist")에 더 잘 반응. "backlit" 추가로 역광 빛 번짐 극대화. |
| **결과 변화** | 하이라이트 주변 글로우/블룸 생성, 전체 뽀얀 톤, 블랙이 살짝 들뜬 필름 감성 확보 (원본 효과의 약 70~80%). 나머지는 편집 글로우 이펙트로 보완. |

---

## 5. 최종 영상 파일 정보

| 항목 | 내용 |
|------|------|
| **파일명** | `weather.mp4` (16:9) / `weather11.mp4` (1:1) |
| **영상 길이** | 약 43초 |
| **해상도** | 1920 × 1080 (16:9) / 1080 × 1080 (1:1) |
| **프레임레이트** | 24fps (시네마틱 감성) |
| **코덱** | H.264 / AAC |
| **마지막 장치** | 자막 + 공모전 엔딩 + 사용 도구 표기 |

---

## 6. 제작 전략 및 의사결정 회고

### 파이프라인 설계

기획 의도(근미래 데이트 로코 + 기후 메시지) → 씬별 프롬프트 설계 → 나노바나나2로 키비주얼 이미지 생성 → 프리픽 Space로 인물 레퍼런스 물려 일관성 유지하며 전 씬 생성 → 이미지를 영상 변환(시작 or 끝 이미지 기반 4~5초 클립, 크레딧 대비 영상을 준수하게 뽑을 수 있는 클링 2.5/2.6 위주 사용) → Suno로 BGM 2트랙 제작 → 네이버 클로바더빙으로 앵커 TTS → Premiere에서 통합 편집(컷·자막·오디오 레벨).

### 인물 일관성 전략

AI 실사 영상의 최대 난점은 컷마다 인물이 달라 보이는 문제. 일관성을 잘 해결한다는 나노바나나2로 제작.

1. 인물 고정 묘사 블록(안경·퍼머·오버핏 셔츠 / 레이어드 헤어·크롭가디건)을 매 프롬프트에 통일 적용.
2. 프리픽 Space로 첫 컷 확정 인물 이미지를 레퍼런스로 고정하여 후속 씬 생성.
3. 의상·헤어 절대 변경 안 함 (데이트 하루 분량이라 설정상 자연스러움).

### 재난/맑음 페어 생성 전략 (떡밥 회수 핵심)

핵심 장치는 '같은 장소, 같은 구도인데 날씨만 다른' 재난 ↔ 맑음 페어 구조. 회수 컷 생성 시 재난 컷 이미지를 레퍼런스로 물려넣고 "SAME composition and camera angle"을 명시하여 구도 일치율을 확보. 이를 통해 관객이 직관적으로 "같은 곳인데 날씨만 바뀌었구나"라고 인지하게 하여 회수의 감정을 극대화.

### 음악 전략 (감정 곡선)

Suno AI로 트랙 2개를 별도 생성하여 감정선을 제어.

- **트랙 1** (0씬~우박): 따뜻한 어쿠스틱 → 긴장 빌드 → 우박에서 뚝 끊김.
- **트랙 2** (회수~엔딩): 잔잔한 피아노 → 스트링 스웰 → 따뜻한 여운.
- 자막 구간에서 2~3초간 무음을 유지하는 '정적'이 감정 전환의 핵심 포인트(Kick)로 작용. 우박까지 갑자기 정적이 흐른 뒤 트랙2가 진입하면서 시청각적 카타르시스를 제공.

### 수미상관 설계

네이버 클로바더빙을 활용해 오프닝 앵커 나레이션("올해 들어 기상 이변이 계속되고 있습니다.")과 엔딩 앵커 나레이션("오늘 화창한 날씨가 계속됐는데요.")을 수미상관으로 배치. 동일한 형식(뉴스 보고)과 문장 구조("~계속")를 취하되 정반대의 내용(이변 ↔ 화창)을 담아, 처음에는 단순 배경 소음처럼 들리던 뉴스가 마지막에는 희망적인 메시지로 다가오는 극적 반전 효과를 극대화.

---

### 보너스 — 플랫폼별 비율 대응

동일 스토리보드로 2가지 비율 버전 제작 완료:
- `weather.mp4` — **16:9** (1920×1080, 유튜브/가로형)
- `weather11.mp4` — **1:1** (1080×1080, 인스타 피드/정사각)
