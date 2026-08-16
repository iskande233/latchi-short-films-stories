# SUPER DZIRI — DOLA/SEEDANCE 2.5 — MASTER PRODUCTION PACK

> **24 فيديو × 10 ثواني = 4 دقائق** — فيلم جزائري واحد متصل.
> **كل مشهد:** الصور (START/END) + Image Prompts + Video Prompt + حوار + صوت + Ending State + ربط بالمشهد الجاي.
> **الصور:** في مجلد `images/` بالتسمية `SDZ_XX_START/END`.

---

## 📋 Character Bible (ثابت — لا تغير أبداً)

### 🧑 أنيس بن يوسف (المواطن)
```
Photorealistic young Algerian man, Anis Benyoucef, 25, 178cm, slim athletic,
short black wavy hair, thin dark eyebrows, dark brown eyes, light stubble on
jawline, medium olive-tan skin, small scar on left eyebrow. Light grey t-shirt,
blue jeans, dark sneakers. NO mask, NO suit. Same face/proportions in every
civilian scene.
```

### 🕷️ سوبر ذزيري (البطل)
```
Photorealistic original Algerian superhero, same 25yo athletic body as Anis.
Clean DARK EMERALD GREEN full-body suit, subtle RED AND WHITE trim on sleeves
and belt, small GOLDEN STAR AND CRESCENT emblem centered on chest. Simple
full-face mask, WHITE lens-shaped eyes, small RED crescent on forehead.
No web patterns, no ornaments, no Spider-Man resemblance. Same exact suit/mask
in every superhero scene.
```

### 👵 خالتي زهرة | 👮 قويدر | 🧑 الحرامي | 🚖 سي الطاهر
```
(انظر ملف الإنتاج FINAL — نفس الأوصاف الثابتة)
```

---

## 🚫 Master Negative Prompt
```
cartoon, anime, illustration, CGI, 3D render, plastic skin, game graphics,
changing face, identity drift, changing clothes, changing costume, changing mask,
changing emblem, extra fingers, missing fingers, deformed hands, extra limbs,
duplicate characters, warped face, warped mouth, broken teeth, unnatural lip
sync, random dialogue, random subtitles, text, watermark, logo, Spider-Man,
Marvel, web pattern, exaggerated muscles, teleporting camera, impossible physics,
sudden location change, inconsistent lighting, inconsistent time of day
```

---

## 🎬 Video Prompt — الصيغة الإجبارية (صورتان)
```
REFERENCE IMAGE ASSIGNMENT:
IMAGE 1 = START FRAME.  IMAGE 2 = END FRAME.
The first uploaded image is the exact visual starting state.
The second uploaded image is the exact visual ending state.
Create ONE continuous 10-second photorealistic live-action shot.
The video must physically and naturally travel from IMAGE 1 to IMAGE 2.
Do not jump directly. Do not blend. Do not morph. Do not teleport.
Do not change the character identity.
TIMELINE:
0-2s: initial movement.
2-5s: main physical transition.
5-8s: main action and/or short dialogue.
8-10s: arrive at the exact visual state of IMAGE 2.
CAMERA: realistic movement. CHARACTER CONTINUITY: exact identity.
ENVIRONMENT CONTINUITY: same place/lighting/time.
DIALOGUE: exact Algerian Darija with named speaker.
AUDIO: ambience + footsteps + dialogue.
ENDING STATE: exactly what is visible at the end.
NEXT SCENE CONNECTION: how the next video begins from this ending.
```

---

## 🗺️ Continuity Map (الصور المشتركة)

| Video | Image 1 (START) | Image 2 (END) | Transition |
|---|---|---|---|
| 01 | SDZ_01_START_Anis_EnteringMarket | SDZ_01_END_Anis_TomatoStall | continuous |
| 02 | = 01_END (shared) | SDZ_02_END_Anis_Bite | continuous |
| 03 | = 02_END (shared) | SDZ_03_END_Anis_WallClimb | continuous |
| 04 | = 03_END (shared) | SDZ_04_END_Anis_ThreadFail | continuous |
| 05 | — (one image) | SDZ_05_Thief_Snatches_Zahra_Bag | CUT (time) |
| 06 | = 05 (shared) | SDZ_06_END_Thief_AlleyEntrance | continuous |
| 07 | = 06_END (shared) | SDZ_07_END_SuperDziri_StopsThief | continuous |
| 08 | — (one image) | SDZ_08_Zahra_GetsBag_Back | CUT (place) |
| 09 | — (one image) | SDZ_09_Taxi_Anis_SiTahar | CUT (time/place) |
| 10 | SDZ_10_START_Anis_HiddenAlley | SDZ_10_END_SuperDziri_Ready | continuous |
| 11 | = 10_END (shared) | SDZ_11_END_SuperDziri_FirstAppearance | continuous |
| 12 | — (one image) | SDZ_12_Anis_Zahra_Baladiya | CUT (time/place) |
| 13 | — (one image) | SDZ_13_SuperDziri_Rooftop_Sunset | CUT (time) |
| 14 | — (one image) | SDZ_14_Anis_Neighborhood_Morning | CUT (next day) |
| 15 | — (one image) | SDZ_15_Anis_SiTahar_Selfie | CUT (time) |
| 16 | — (one image) | SDZ_16_Anis_BakeryQueue | CUT (time) |
| 17 | SDZ_17_START_Anis_MarketFakeShoes | SDZ_17_END_Anis_LeavingStall | continuous |
| 18 | SDZ_18_START_Anis_RooftopBag | SDZ_18_END_SuperDziri_RooftopReady | continuous |
| 19 | = 18_END (shared) | SDZ_19_END_SuperDziri_FakeShoeStall | continuous |
| 20 | — (one image) | SDZ_20_SuperDziri_Kouider | CUT (time) |
| 21 | — (one image) | SDZ_21_SuperDziri_StopsFight | CUT (time) |
| 22 | SDZ_22_START_SuperDziri_Chase | SDZ_22_END_AlleyCorner | continuous |
| 23 | = 22_END (shared MATCH CUT) | SDZ_23_END_SuperDziri_WithChildren | MATCH CUT |
| 24A | — (one image) | SDZ_24A_Car_Thief | CUT (time) |
| 24B | — (one image) | SDZ_24B_SuperDziri_Zahra_Tea | CUT (place) |
| 24C | SDZ_24C_START_Kouider_Handshake | SDZ_24C_END_Rooftop_Sunset | continuous → final |

**الصور المشتركة (لا تنشئ نسخة ثانية):**
```
SDZ_01_END = SDZ_02_START
SDZ_02_END = SDZ_03_START (نفس أنيس بعد اللدغة)
SDZ_03_END = SDZ_04_START
SDZ_05 = SDZ_06_START
SDZ_06_END = SDZ_07_START
SDZ_10_END = SDZ_11_START
SDZ_18_END = SDZ_19_START
SDZ_22_END = SDZ_23_START (MATCH CUT)
```

---

## 🎬 المشاهد (01 → 24) بالتفصيل الكامل

### SCENE 01 — دخول السوق → الوصول إلى بائع الخضار

**الزمن:** —

**الصور:** SDZ_01_START_Anis_EnteringMarket.png, SDZ_01_END_Anis_TomatoStall.png


---

### SCENE 02 — عند الطماطم → اللدغة

**الزمن:** —

**الصور:** SDZ_02_END_Anis_SpiderBite.png, SDZ_01_END_Anis_TomatoStall.png


---

### SCENE 03 — آثار القوة / تجربة الالتصاق

**الزمن:** —

**الصور:** SDZ_02_END_Anis_SpiderBite.png, SDZ_03_END_Anis_WallClimb.png


---

### SCENE 04 — تجربة الخيط / الفشل الكوميدي

**الزمن:** —

**الصور:** SDZ_03_END_Anis_WallClimb.png, SDZ_04_END_Anis_ThreadFail.png


---

### SCENE 05 — سرقة حقيبة زهرة

**الزمن:** —

**الصور:** SDZ_05_Thief_Snatches_Zahra_Bag.png


---

### SCENE 06 — المطاردة إلى الزقاق

**الزمن:** —

**الصور:** SDZ_06_END_Thief_AlleyEntrance.png, SDZ_05_Thief_Snatches_Zahra_Bag.png


---

### SCENE 07 — سوبر ذزيري يمسك الحرامي

**الزمن:** —

**الصور:** SDZ_06_END_Thief_AlleyEntrance.png, SDZ_07_END_SuperDziri_StopsThief.png


---

### SCENE 08 — رجوع الحقيبة

**الزمن:** —

**الصور:** SDZ_08_Zahra_GetsBag_Back.png


---

### SCENE 09 — التاكسي والحياة العادية

**الزمن:** —

**الصور:** SDZ_09_Taxi_Anis_SiTahar.png


---

### SCENE 10 — التحول إلى سوبر ذزيري

**الزمن:** —

**الصور:** SDZ_10_END_SuperDziri_Ready.png, SDZ_10_START_Anis_HiddenAlley.png


---

### SCENE 11 — أول ظهور في الحومة

**الزمن:** —

**الصور:** SDZ_10_END_SuperDziri_Ready.png, SDZ_11_END_SuperDziri_FirstAppearance.png


---

### SCENE 12 — البلدية

**الزمن:** —

**الصور:** SDZ_12_Anis_Zahra_Baladiya.png


---

### SCENE 13 — نهاية اليوم الأول فوق السطح

**الزمن:** —

**الصور:** SDZ_13_SuperDziri_Rooftop_Sunset.png


---

### SCENE 14 — صباح اليوم التالي / الحي يتكلم

**الزمن:** —

**الصور:** SDZ_14_Anis_Neighborhood_Morning.png


---

### SCENE 15 — سيلفي مع سي الطاهر

**الزمن:** —

**الصور:** SDZ_15_Anis_SiTahar_Selfie.png


---

### SCENE 16 — طابور المخبزة

**الزمن:** —

**الصور:** SDZ_16_Anis_BakeryQueue.png


---

### SCENE 17 — اكتشاف المنتجات المقلدة

**الزمن:** —

**الصور:** SDZ_17_START_Anis_MarketFakeShoes.png, SDZ_17_END_Anis_LeavingStall.png


---

### SCENE 18 — التحول الثاني

**الزمن:** —

**الصور:** SDZ_18_START_Anis_RooftopBag.png, SDZ_18_END_SuperDziri_RooftopReady.png


---

### SCENE 19 — كشف المقلدة

**الزمن:** —

**الصور:** SDZ_18_END_SuperDziri_RooftopReady.png, SDZ_19_END_SuperDziri_FakeShoeStall.png


---

### SCENE 20 — مساعدة قويدر

**الزمن:** —

**الصور:** SDZ_20_SuperDziri_Kouider.png


---

### SCENE 21 — فض الشجار

**الزمن:** —

**الصور:** SDZ_21_SuperDziri_StopsFight.png


---

### SCENE 22 — مطاردة قويدر → Match Cut إلى الأطفال

**الزمن:** —

**الصور:** SDZ_22_END_AlleyCorner.png, SDZ_22_START_SuperDziri_Chase.png


---

### SCENE 23 — Match Cut: الأطفال

**الزمن:** —

**الصور:** SDZ_22_END_AlleyCorner.png, SDZ_23_END_SuperDziri_WithChildren.png


---

### SCENE 24 — سرقة السيارة → الشاي → التصالح → النهاية

**الزمن:** —

**الصور:** SDZ_06_END_Thief_AlleyEntrance.png, SDZ_24C_END_Rooftop_Sunset.png, SDZ_24B_SuperDziri_Zahra_Tea.png, SDZ_24A_Car_Thief.png, SDZ_22_END_AlleyCorner.png, SDZ_24C_START_Kouider_Handshake.png, SDZ_10_END_SuperDziri_Ready.png, SDZ_01_END_Anis_TomatoStall.png, SDZ_18_END_SuperDziri_RooftopReady.png


---


---

## ✅ Final Production Checklist

- [ ] الصور كلها مولّدة ومسمّاة SDZ_XX_START/END
- [ ] كل مشهد عنده Video Prompt كامل (IMAGE 1/2 + حركة + حوار + صوت + نهاية)
- [ ] الصور المشتركة مستعملة (نفس الملف بين مشهدين)
- [ ] الـ Negative Prompt مطبق
- [ ] الدارجة 100% + Lip-sync
- [ ] اختبار واحد من كل نوع (مشي، حوار، تحول، مطاردة، Match Cut)
- [ ] المونتاج: Cut للمنتقلات الزمنية، Match Cut للـ 22→23

**الهدف:** 24 فيديو يبانوا فيلم واحد مصوّر بالكاميرا — ماشي 24 توليد منفصل.

© LATCHI AI — 🎬 100% جزائري 🇩🇿
