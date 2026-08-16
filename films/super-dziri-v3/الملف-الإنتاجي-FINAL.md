# 🕷️ سوبر ذزيري — SEEDANCE 2.5
## ملف الإنتاج النهائي — 24 مشهد × 10 ثواني
### Image-to-Video / Two-Image Continuity / Algerian Darija Lip-Sync

> **مهم:** هذا الملف هو نسخة إنتاجية مبنية على ملف الفيلم الأصلي المرفوع، مع إعادة صياغة أوصاف الحركة والانتقالات لتناسب فيديوهات 10 ثوانٍ. الشخصيات وأحداث القصة الأساسية مأخوذة من الملف الأصلي. fileciteturn7file0L10-L32

---

# 0) كيف تستعمل هذا الملف

كل مشهد عنده:
- **START IMAGE** = الصورة التي تمثل بداية الفيديو.
- **END IMAGE** = الصورة التي تمثل نهاية الفيديو، عندما تكون مفيدة.
- إذا كان المشهد يحتاج صورة واحدة فقط، Seedance يحرك الحالة الموجودة في الصورة.
- إذا كان عندك صورتان، ارفع **الصورة الأولى كمرجع بداية والصورة الثانية كمرجع نهاية** إذا كانت واجهة Seedance تدعم صورتين.
- **لا تعطي Seedance صورة المشهد التالي وتطلب منه التخمين فقط.** البرومبت يحدد المسار الحركي بين الصورتين.

### تسمية الملفات

استعمل أسماء الملفات حرفيًا بهذا الشكل:

```text
SDZ_01_START_Anis_Market.png
SDZ_01_END_Anis_TomatoStall.png
SDZ_02_START_Anis_TomatoStall.png
SDZ_02_END_Anis_Bite.png
...
```

**إذا كانت صورة النهاية لمشهد هي نفسها بداية المشهد التالي، لا تنشئ صورة جديدة. استعمل نفس الملف.**

---

# 1) MASTER CHARACTER LOCK

هذه الأوصاف لا تتغير بين المشاهد.

## أنيس بن يوسف — ANIS_BENYOUCEF

```text
Photorealistic young Algerian man, Anis Benyoucef, 25 years old, 178 cm tall,
slim athletic build, short black wavy hair, thin dark eyebrows, expressive dark
brown eyes, light stubble beard covering the jawline, medium olive-tan skin,
small scar on his left eyebrow. Ordinary clothes: light grey t-shirt, blue jeans,
simple dark sneakers. NO mask, NO superhero suit in civilian scenes.
```

## سوبر ذزيري — SUPER_DZIRI

```text
Photorealistic original Algerian superhero, Super Dziri, same physical identity
and proportions as Anis Benyoucef, slim athletic build. Clean DARK EMERALD GREEN
full-body suit, subtle RED and WHITE trim on sleeves and belt, small GOLDEN STAR
AND CRESCENT emblem on chest, simple full-face mask with WHITE lens-shaped eyes,
small RED crescent on forehead. No web pattern, no spider logo, no extra armor,
no ornaments. Original Algerian character, NOT Spider-Man. Exactly the same suit,
mask, emblem, colors and proportions in every superhero image.
```

## خالتي زهرة — AUNT_ZAHRA

```text
Photorealistic elderly Algerian woman, Aunt Zahra, 72 years old, short and
slightly hunched, deep wrinkles, warm brown eyes, grey hair in a bun under a
traditional white haik head covering, dark blue traditional karakou-style dress
with gold embroidery, worn brown leather handbag. Same appearance in every scene.
```

## قويدر — OFFICER_KOUIDER

```text
Photorealistic Algerian police officer, Kouider, 40 years old, medium height,
stocky build, short grey-flecked black hair, thick moustache, stern but kind face,
light brown skin, dark blue Algerian police uniform with badge and cap. Same
appearance in every scene.
```

## حرامي السوق — MARKET_THIEF

```text
Photorealistic thin Algerian man, market thief, 30 years old, thin build, shifty
narrow eyes, short messy black hair, thin goatee, light brown skin, dark grey
hooded jacket, black jeans. Same appearance in every scene.
```

## سي الطاهر — SI_TAHAR

```text
Photorealistic Algerian taxi driver, Si Tahar, 50 years old, medium build,
grey moustache, weathered friendly face with laugh lines, light brown skin,
beige shirt, dark trousers. Drives the same white and yellow Algerian taxi.
```

---

# 2) MASTER VISUAL LOCK

أضف هذا النص في بداية كل Video Prompt:

```text
10-second photorealistic live-action Algerian cinematic video.
Use the supplied reference image(s) as strict visual anchors.

Preserve exact character identity, face, skin tone, hairstyle, body proportions,
clothing, costume, mask, emblem, props, environment, architecture, weather,
time of day and lighting.

Do NOT redesign the characters.
Do NOT change clothing.
Do NOT change the superhero suit.
Do NOT change the mask.
Do NOT change the chest emblem.
Do NOT change the location unless explicitly instructed.
Do NOT teleport.
Do NOT morph.
Do NOT create duplicate people.
Do NOT add random objects.
Do NOT change the character's age.
Maintain realistic human anatomy, realistic physics and natural body mechanics.
```

---

# 3) MASTER DIALOGUE / DARIJA LOCK

كل الحوار في الفيلم يجب أن يكون **Algerian Darija**, وليس فصحى.

```text
DIALOGUE LANGUAGE:
Authentic natural Algerian Darija, casual everyday Algerian speech.

PRONUNCIATION:
Use natural Algerian pronunciation, connected speech, local rhythm and
realistic conversational intonation. Do not use Modern Standard Arabic diction.
Do not translate the dialogue. Do not paraphrase it. Do not add words.

SPEAKER CONTROL:
Only the named speaker talks.
Other characters keep their mouths closed unless explicitly assigned dialogue.

LIP SYNC:
The speaker's mouth movements must match the exact spoken words.
No random mouth movement.
No invented dialogue.
No subtitles unless explicitly requested.
No narrator unless explicitly requested.

TIMING:
Dialogue must fit naturally inside the specified seconds.
Do not rush the sentence.
Do not stretch syllables unnaturally.
Use short conversational pauses and realistic Algerian intonation.
```

> **ملاحظة إنتاجية:** 10 ثوانٍ لا تعني أن الشخصية لازم تتكلم طوال الـ10 ثواني. الأفضل ترك 1–3 ثوانٍ للحركة قبل/بعد الحوار حتى لا يفسد الـlip-sync.

---

# 4) MASTER NEGATIVE PROMPT

```text
cartoon, anime, illustration, CGI, 3D render, plastic skin, game graphics,
identity drift, face change, age change, clothing change, costume change,
mask change, emblem change, random hairstyle, duplicate character, extra limbs,
extra fingers, missing fingers, deformed hands, distorted mouth, broken teeth,
bad lip sync, invented dialogue, subtitles, text, watermark, logo,
Spider-Man, Marvel, web pattern, spider logo, exaggerated muscles, teleportation,
morphing, impossible physics, sudden location change, random camera cut,
random lighting change, inconsistent weather, inconsistent time of day,
character appearing from nowhere
```

---

# 5) قاعدة الصور والانتقال

## القاعدة الذهبية

إذا استعملنا صورتين:

```text
IMAGE A = START STATE
IMAGE B = END STATE
```

الـPrompt يجب أن يقول بوضوح:

1. ابدأ من Image A.
2. حافظ على هوية Image A.
3. نفذ الحركة خطوة بخطوة.
4. لا تقفز مباشرة إلى Image B.
5. اجعل الكاميرا تتحرك منطقيًا.
6. يصل الشخص إلى الوضعية الموجودة في Image B.
7. آخر ثانية تطابق Image B قدر الإمكان.

---

# 🎬 SCENE 01 — دخول السوق → الوصول إلى بائع الخضار

**المدة:** 10s

### FILES

```text
SDZ_01_START_Anis_EnteringMarket.png
SDZ_01_END_Anis_TomatoStall.png
```

### START IMAGE

```text
Photorealistic Algerian neighborhood market entrance, Anis Benyoucef, 25,
same fixed civilian identity, grey t-shirt, blue jeans, dark sneakers, entering
a busy vegetable market on foot. Warm afternoon sunlight, authentic Algerian
market, vegetable stalls, pedestrians, realistic architecture. Medium-wide
three-quarter rear shot, natural cinematic photography, 16:9.
```

### END IMAGE

```text
Photorealistic same Algerian market, same afternoon light and same stall layout.
Anis Benyoucef is now standing naturally at a vegetable stall, facing a vendor,
his right hand close to a pile of tomatoes. Same face, hair, grey t-shirt,
blue jeans and body proportions. Medium shot, matching the spatial direction
of movement from the previous image, 16:9.
```

### SEEDANCE VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_01_START_Anis_EnteringMarket.png
END REFERENCE FILE: SDZ_01_END_Anis_TomatoStall.png

Use START IMAGE as the exact beginning state and END IMAGE as the exact target
state.

0-2s:
Anis enters the market at a normal human walking speed. Keep the camera behind
and slightly to his left. Natural arm swing and footsteps.

2-4s:
The camera smoothly tracks forward with Anis. He notices the vegetable stall
ahead and gradually turns his head toward it without stopping suddenly.

4-6s:
Anis slows down naturally as he approaches the stall. His body rotates slightly
toward the vendor. Camera moves from the rear three-quarter angle toward a
medium side angle.

6-8s:
Anis reaches the stall and stops naturally. He extends his right hand toward
the tomatoes.

8-10s:
He settles into the exact position represented by
SDZ_01_END_Anis_TomatoStall.png. The final 1 second must be stable and visually
match the END IMAGE in body position, screen placement, lighting and framing.

NO CUT between START and END.
NO teleportation.
NO sudden zoom.
NO change of clothes.
NO change of face.
```

---

# 🎬 SCENE 02 — عند الطماطم → اللدغة

**FILES**

```text
SDZ_01_END_Anis_TomatoStall.png
SDZ_02_END_Anis_SpiderBite.png
```

### END IMAGE

```text
Same market, same vegetable stall, same Anis identity and clothes. Anis has just
pulled his right hand back after a small spider bite. He looks at the bite with
surprise. A tiny realistic spider is visible near the vegetables. Medium
close-up including face and right hand.
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_01_END_Anis_TomatoStall.png
END REFERENCE FILE: SDZ_02_END_Anis_SpiderBite.png

Begin exactly from the final state of the START IMAGE.

0-2s:
Anis casually picks up two tomatoes and examines them.

2-4s:
A small realistic spider crawls from between the vegetables toward his right
hand and bites him. The bite is quick and physically believable.

4-6s:
Anis reacts with a short natural flinch and immediately pulls his right hand
back.

6-8s:
He raises the bitten hand closer to his face and looks at the small bite.

8-10s:
His expression becomes confused and surprised. Hold the exact final pose shown
in SDZ_02_END_Anis_SpiderBite.png.

DIALOGUE:
Anis speaks only from approximately 6.2s to 9.2s:
"آي! واش هادي؟ عنكبوت؟ في السوق؟!"

Voice: young Algerian male, natural neighborhood Darija, surprised but restrained.
Accurate lip sync. No extra words.

SOUND:
Busy market ambience, small spider movement sound, brief sting reaction.
```

---

# 🎬 SCENE 03 — آثار القوة / تجربة الالتصاق

**FILES**

```text
SDZ_02_END_Anis_SpiderBite.png
SDZ_03_END_Anis_WallClimb.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_02_END_Anis_SpiderBite.png
END REFERENCE FILE: SDZ_03_END_Anis_WallClimb.png

This is the same Anis immediately after the bite. Maintain the same civilian
clothes and physical identity.

0-2s:
Anis leaves the market holding his bitten hand, walking quickly but naturally.

2-4s:
He reaches a quiet low concrete wall in the nearby neighborhood and places his
right palm against it.

4-6s:
His palm unexpectedly sticks. He gently pulls, realizes the resistance and
looks shocked.

6-8s:
He places his left palm on the wall and carefully lifts one foot.

8-10s:
He takes one cautious step upward and ends in the exact climbing pose shown in
SDZ_03_END_Anis_WallClimb.png.

Dialogue, quiet:
"واش بيّا اليوم؟"

Natural Algerian male voice. No magical glow. No superhero suit.
```

---

# 🎬 SCENE 04 — تجربة الخيط / الفشل الكوميدي

**FILES**

```text
SDZ_03_END_Anis_WallClimb.png
SDZ_04_END_Anis_ThreadFail.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_03_END_Anis_WallClimb.png
END REFERENCE FILE: SDZ_04_END_Anis_ThreadFail.png

0-2s:
Anis climbs down from the wall and looks at his wrist, curious.

2-4s:
He raises his wrist toward a nearby balcony railing and tries to shoot a thin
web-like thread.

4-6s:
The thread reaches only a short distance and attaches awkwardly to the railing.

6-8s:
Anis gives the thread a cautious tug, realizes it is weak and looks confused.

8-10s:
He gives a small defeated shrug and looks at the low buildings around him.

Dialogue:
"هادي هي القوة تاعي؟!"

Natural comedic delivery, not cartoonish. Realistic physics.
```

---

# 🎬 SCENE 05 — سرقة حقيبة زهرة

**FILE**

```text
SDZ_05_Thief_Snatches_Zahra_Bag.png
```

### IMAGE PROMPT

```text
Photorealistic Algerian street market, same visual world as earlier market.
Aunt Zahra, 72, white haik head covering, dark blue traditional dress with gold
embroidery, holding her worn brown leather handbag. Same Market Thief:
thin Algerian man, 30, messy black hair, thin goatee, dark grey hooded jacket,
black jeans. He is positioned directly behind her. Busy shoppers and vegetable
stalls. Warm daylight. Dynamic medium shot designed for a 10-second snatch action.
```

### VIDEO PROMPT

```text
Use SDZ_05_Thief_Snatches_Zahra_Bag.png as the exact starting composition.

0-2s:
The thief quietly steps closer behind Zahra and reaches toward the handbag.

2-4s:
He grabs the brown handbag and pulls it away in one quick realistic movement.

4-6s:
Zahra turns immediately, shocked, raises both hands and looks toward him.

6-8s:
The thief turns and starts running toward a clearly visible narrow side street.

8-10s:
Zahra points in the exact direction he escaped while nearby shoppers react.

DIALOGUE:
Zahra:
"آي يا ولدي! الحرامي! الحقو! سرقلي حقيبتي!"

Natural elderly Algerian female voice, emotional but intelligible. Exact words only.

SOUND:
Market ambience drops slightly at the scream, footsteps and crowd reaction.
```

---

# 🎬 SCENE 06 — المطاردة إلى الزقاق

**FILES**

```text
SDZ_05_Thief_Snatches_Zahra_Bag.png
SDZ_06_END_Thief_AlleyEntrance.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_05_Thief_Snatches_Zahra_Bag.png
END REFERENCE FILE: SDZ_06_END_Thief_AlleyEntrance.png

Continue immediately after the handbag snatch.

0-2s:
The thief runs away holding the same brown handbag. Keep his direction exactly
consistent with the START IMAGE.

2-5s:
Camera follows him in a handheld but controlled tracking movement through the
market.

5-7s:
He passes two shoppers and enters the narrow side street.

7-10s:
He reaches the exact position represented by
SDZ_06_END_Thief_AlleyEntrance.png and disappears deeper into the alley.

No superhero appears yet. Do not introduce new characters.
```

---

# 🎬 SCENE 07 — سوبر ذزيري يمسك الحرامي

**FILES**

```text
SDZ_06_END_Thief_AlleyEntrance.png
SDZ_07_END_SuperDziri_StopsThief.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_06_END_Thief_AlleyEntrance.png
END REFERENCE FILE: SDZ_07_END_SuperDziri_StopsThief.png

The thief continues from the same direction. Super Dziri is already farther
inside the alley, blocking his escape.

0-2s:
The thief runs deeper into the alley and suddenly sees Super Dziri standing
in his path.

2-4s:
The thief slows abruptly. Super Dziri steps forward and grabs the thief's jacket
collar without punching him.

4-6s:
The thief drops the brown handbag.

6-8s:
Super Dziri points toward the handbag and then toward the thief with a firm
disapproving gesture.

8-10s:
Hold the exact final composition of SDZ_07_END_SuperDziri_StopsThief.png.

DIALOGUE:
"تسرق حقيبة وحدة عجوز؟ عيب عليك! هذي حقيبة خالتي زهرة!"

Natural Algerian male superhero voice, calm but firm. Exact lip sync.
```

---

# 🎬 SCENE 08 — رجوع الحقيبة

**FILE**

```text
SDZ_08_Zahra_GetsBag_Back.png
```

### VIDEO PROMPT

```text
Use SDZ_08_Zahra_GetsBag_Back.png as the starting composition.

0-2s:
Super Dziri walks toward Zahra holding her brown handbag with both hands.

2-4s:
He gently extends the handbag toward her.

4-6s:
Zahra takes it with visible relief and holds it close.

6-8s:
She looks up at him gratefully.

8-10s:
Super Dziri gives a small reassuring nod and steps back.

Zahra:
"ربي يحفظك يا ولدي."

Super Dziri:
"المهم رجعتلك."

Natural Algerian voices, no exaggerated superhero movement.
```

---

# 🎬 SCENE 09 — التاكسي والحياة العادية

**FILE**

```text
SDZ_09_Taxi_Anis_SiTahar.png
```

### VIDEO PROMPT

```text
Use SDZ_09_Taxi_Anis_SiTahar.png as the exact starting composition.

0-3s:
Anis sits naturally in the back seat of the white-and-yellow taxi and looks
through the window.

3-5s:
Si Tahar checks the rear-view mirror and turns his eyes briefly toward Anis.

5-7s:
Si Tahar asks:
"وين رايح يا ولدي؟"

7-10s:
Anis answers:
"راني رايح نخدم... اليوم طويل."

Only the active speaker moves his lips. Natural Algerian pronunciation.
The taxi keeps moving normally. No unsafe driving.
```

---

# 🎬 SCENE 10 — التحول إلى سوبر ذزيري

**FILES**

```text
SDZ_10_START_Anis_HiddenAlley.png
SDZ_10_END_SuperDziri_Ready.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_10_START_Anis_HiddenAlley.png
END REFERENCE FILE: SDZ_10_END_SuperDziri_Ready.png

0-2s:
Anis enters the same quiet alley and checks left and right.

2-4s:
He opens the black sports bag and pulls out the dark emerald green superhero suit.

4-6s:
He changes into the suit in a practical continuous movement.

6-8s:
He puts on the exact same full-face mask with white lens eyes and red crescent.

8-10s:
He turns toward the alley exit and adopts the exact final stance of
SDZ_10_END_SuperDziri_Ready.png.

Dialogue, whispered:
"يلا... نبداو الخدمة."

No magical morphing. No instant costume transformation.
```

---

# 🎬 SCENE 11 — أول ظهور في الحومة

**FILES**

```text
SDZ_10_END_SuperDziri_Ready.png
SDZ_11_END_SuperDziri_FirstAppearance.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_10_END_SuperDziri_Ready.png
END REFERENCE FILE: SDZ_11_END_SuperDziri_FirstAppearance.png

0-2s:
Super Dziri walks out of the alley at a normal pace.

2-4s:
Residents and children notice him. Their heads turn naturally.

4-6s:
Super Dziri raises one hand in a friendly greeting.

6-8s:
He points toward Zahra's recovered handbag visible nearby.

8-10s:
He gives a small wave and holds the exact final posture shown in
SDZ_11_END_SuperDziri_FirstAppearance.png.

Dialogue:
"سلام عليكم! أنا سوبر ذزيري... نعاون الحومة تاعنا."

Natural Algerian male voice, confident but humble.
```

---

# 🎬 SCENE 12 — البلدية

**FILE**

```text
SDZ_12_Anis_Zahra_Baladiya.png
```

### VIDEO PROMPT

```text
Use SDZ_12_Anis_Zahra_Baladiya.png as the starting composition.

0-2s:
Zahra looks down at her paperwork and sighs.

2-5s:
Anis leans toward the document and points to the missing item.

5-7s:
Zahra looks at Anis with relief.

7-10s:
Anis nods reassuringly and helps organize the papers.

Zahra:
"يا ولدي، هذي الوثائق نهار ولا عام ما كملتهمش."

Anis:
"لا تخافي يا خالتي، نكملوها وحدة بوحدة."

Natural office ambience and realistic paper movement.
```

---

# 🎬 SCENE 13 — نهاية اليوم الأول فوق السطح

**FILE**

```text
SDZ_13_SuperDziri_Rooftop_Sunset.png
```

### VIDEO PROMPT

```text
Use SDZ_13_SuperDziri_Rooftop_Sunset.png as the starting frame.

0-3s:
Super Dziri sits quietly on the low rooftop edge and looks over the neighborhood.

3-5s:
He slowly looks down at the streets and people below.

5-7s:
He looks at his gloved hands.

7-10s:
He looks toward the sunset while the camera slowly pulls backward.

INNER VOICE:
"أنا أنيس... ولد الحومة. البطل الحقيقي هو اللي يوقف مع الناس."

Voice should sound like a quiet natural Algerian inner monologue, not theatrical.
```

---

# 🎬 SCENE 14 — صباح اليوم التالي / الحي يتكلم

**FILE**

```text
SDZ_14_Anis_Neighborhood_Morning.png
```

### VIDEO PROMPT

```text
Use SDZ_14_Anis_Neighborhood_Morning.png as the starting composition.

0-2s:
Anis walks normally carrying bread.

2-5s:
Two neighbors notice him and quietly compare him with the superhero they heard about.

5-7s:
One neighbor looks suspiciously at Anis.

7-10s:
Anis notices them, gives an innocent smile and continues walking.

Whispered dialogue:
"هذا ماشي أنيس؟"
"لا لا... أنيس ولد الحومة، عادي."

Keep the whispers subtle. Anis does not respond.
```

---

# 🎬 SCENE 15 — سيلفي مع سي الطاهر

**FILE**

```text
SDZ_15_Anis_SiTahar_Selfie.png
```

### VIDEO PROMPT

```text
Use SDZ_15_Anis_SiTahar_Selfie.png.

0-2s:
Si Tahar recognizes Anis through the rear-view mirror and becomes excited.

2-4s:
He gestures for a quick selfie while keeping the taxi safely stopped.

4-6s:
Anis reluctantly leans into the frame.

6-8s:
Si Tahar smiles and raises two fingers for the photo.

8-10s:
Camera shutter sound; Anis laughs nervously.

Si Tahar:
"إنت اللي مع سوبر ذزيري؟ ههه!"

Anis:
"خويا، راني غير أنيس!"

Natural Algerian humor. No extra dialogue.
```

---

# 🎬 SCENE 16 — طابور المخبزة

**FILE**

```text
SDZ_16_Anis_BakeryQueue.png
```

### VIDEO PROMPT

```text
Use SDZ_16_Anis_BakeryQueue.png.

0-2s:
Anis looks at the long bakery queue.

2-4s:
He counts the people in front of him with his fingers.

4-6s:
He looks briefly toward the open sky as if considering using his powers.

6-8s:
He shakes his head and decides to remain in the queue.

8-10s:
The person in front moves, and Anis takes one step forward.

INNER VOICE:
"نقدر نتجاوزهم... بصح البطل الحقيقي يستنى كيما الناس."

Natural inner voice, Algerian Darija.
```

---

# 🎬 SCENE 17 — اكتشاف المنتجات المقلدة

**FILES**

```text
SDZ_17_START_Anis_MarketFakeShoes.png
SDZ_17_END_Anis_LeavingStall.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_17_START_Anis_MarketFakeShoes.png
END REFERENCE FILE: SDZ_17_END_Anis_LeavingStall.png

0-2s:
Anis picks up the fake sneaker and examines its stitching.

2-4s:
He turns the shoe over and notices another defect.

4-6s:
He looks at the seller with a suspicious expression.

6-8s:
He places the sneaker back on the counter.

8-10s:
He turns toward the hidden passage and begins walking toward it, ending exactly
as shown in SDZ_17_END_Anis_LeavingStall.png.

Dialogue:
"هادي؟ ماركة عالمية؟ باينة مقلدة."

No exaggerated acting.
```

---

# 🎬 SCENE 18 — التحول الثاني

**FILES**

```text
SDZ_18_START_Anis_RooftopBag.png
SDZ_18_END_SuperDziri_RooftopReady.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_18_START_Anis_RooftopBag.png
END REFERENCE FILE: SDZ_18_END_SuperDziri_RooftopReady.png

0-2s:
Anis opens the black sports bag while overlooking the same market.

2-4s:
He pulls out the exact dark emerald green suit.

4-6s:
He changes into the suit in a practical continuous action.

6-8s:
He puts on the exact same mask.

8-10s:
He turns toward the market below and settles into the final pose of
SDZ_18_END_SuperDziri_RooftopReady.png.

Whisper:
"حان الوقت... سوبر ذزيري ينزل للميدان."

No magical transformation.
```

---

# 🎬 SCENE 19 — كشف المقلدة

**FILES**

```text
SDZ_18_END_SuperDziri_RooftopReady.png
SDZ_19_END_SuperDziri_FakeShoeStall.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_18_END_SuperDziri_RooftopReady.png
END REFERENCE FILE: SDZ_19_END_SuperDziri_FakeShoeStall.png

0-2s:
Super Dziri leaves the rooftop access and moves toward the market stall.

2-4s:
The camera follows him into the SAME market from Scene 17.

4-6s:
He approaches the same seller and picks up the same fake sneaker.

6-8s:
He raises the shoe so nearby shoppers can see the bad stitching.

8-10s:
He points toward the seller and holds the exact final position of
SDZ_19_END_SuperDziri_FakeShoeStall.png.

Dialogue:
"شوفو هذي! يقولك أصلية؟ هذي مقلدة!"

Natural firm Algerian voice. Exact words only.
```

---

# 🎬 SCENE 20 — مساعدة قويدر

**FILE**

```text
SDZ_20_SuperDziri_Kouider.png
```

### VIDEO PROMPT

```text
Use SDZ_20_SuperDziri_Kouider.png.

0-2s:
Super Dziri hands a detained criminal over to Officer Kouider.

2-4s:
Kouider takes custody and looks at Super Dziri suspiciously.

4-6s:
Super Dziri raises both hands calmly, showing he is only helping.

6-8s:
Kouider relaxes and gives a respectful nod.

8-10s:
Super Dziri nods back.

Kouider:
"راك تحب تقوم بدوري؟"

Super Dziri:
"لا خويا، غير نعاون."

Natural Algerian voices. No fighting.
```

---

# 🎬 SCENE 21 — فض الشجار

**FILE**

```text
SDZ_21_SuperDziri_StopsFight.png
```

### VIDEO PROMPT

```text
Use SDZ_21_SuperDziri_StopsFight.png.

0-2s:
Two young men argue loudly and prepare to fight.

2-4s:
Super Dziri steps between them and raises both hands to stop the argument.

4-6s:
Both men stop and look at him.

6-8s:
Super Dziri looks from one man to the other with amused disbelief.

8-10s:
The crowd laughs lightly.

Dialogue:
"وقفو! على واش تتقاتلو؟ على 500 دج؟ قاتلو في الدوري، ماشي في الشارع!"

Natural comedic Algerian delivery. Keep sentence clearly articulated.
```

---

# 🎬 SCENE 22 — مطاردة قويدر → Match Cut إلى الأطفال

**FILES**

```text
SDZ_22_START_SuperDziri_Chase.png
SDZ_22_END_AlleyCorner.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_22_START_SuperDziri_Chase.png
END REFERENCE FILE: SDZ_22_END_AlleyCorner.png

CRITICAL CONTINUITY SCENE.

0-2s:
Super Dziri runs forward on foot and looks over his shoulder.

2-4s:
Officer Kouider follows behind him at a realistic running speed.

4-6s:
Kouider shouts:
"وقوف!"

Super Dziri answers while running:
"خويا، نفهمك!"

6-8s:
Super Dziri approaches the EXACT sharp alley corner shown in
SDZ_22_END_AlleyCorner.png.

8-10s:
He turns around the corner and exits frame in the same direction shown by the
END IMAGE.

CRITICAL:
Do not change the running direction.
Do not teleport.
Do not introduce a new street.
The final camera position, alley corner and lighting must match the next scene.
Leave the last 0.5-1.0 seconds visually stable enough for a match cut.
```

---

# 🎬 SCENE 23 — Match Cut: الأطفال

**FILES**

```text
SDZ_22_END_AlleyCorner.png
SDZ_23_END_SuperDziri_WithChildren.png
```

### VIDEO PROMPT

```text
START REFERENCE FILE: SDZ_22_END_AlleyCorner.png
END REFERENCE FILE: SDZ_23_END_SuperDziri_WithChildren.png

CRITICAL MATCH CUT.

0-2s:
Continue from the exact same alley corner and same direction of motion.
Super Dziri emerges from behind the corner.

2-4s:
He notices a group of neighborhood children waiting nearby and naturally slows
from a run to a walk.

4-6s:
The children approach excitedly. Super Dziri crouches.

6-8s:
One child wearing a handmade paper mask gives him a high-five.

8-10s:
The child salutes him and Super Dziri returns the salute, ending exactly as
shown in SDZ_23_END_SuperDziri_WithChildren.png.

Children:
"سوبر ذزيري!"

Child:
"شوف! درت ماسك كيماك!"

Super Dziri:
"خليك في القراية... وبعد تولي بطل حقيقي!"

Natural Algerian pronunciation, child voices distinct and believable.

IMPORTANT:
The first two seconds must feel like the CONTINUATION of the chase, not a new
unrelated shot.
```

---

# 🎬 SCENE 24 — سرقة السيارة → الشاي → التصالح → النهاية
## ملاحظة إنتاجية مهمة

لأن Seedance يعطي 10 ثوانٍ، **لا نحشر ثلاث أحداث كاملة في فيديو واحد**. لذلك هذا الفصل النهائي يُنفذ كـ3 مقاطع 10 ثوانٍ إذا أردت الحفاظ على القصة كاملة، مع اعتبارها داخل النهاية الإنتاجية.

### 24A — سرقة السيارة

**FILE**

```text
SDZ_24A_Car_Thief.png
```

```text
10-second photorealistic Algerian street at dusk.

0-2s: A thin thief tries to force open a white car.
2-4s: Super Dziri enters the frame and stops behind him.
4-6s: The thief turns, freezes and drops the tool.
6-8s: Super Dziri points toward the street.
8-10s: The thief runs away.

Super Dziri:
"سرقة سيارة؟ يلا امشي قبل ما نجيب الشرطة!"

Natural Algerian male voice, firm but humorous.
```

### 24B — الشاي مع زهرة

**FILE**

```text
SDZ_24B_SuperDziri_Zahra_Tea.png
```

```text
10-second photorealistic cozy Algerian living room.

0-2s: Super Dziri sits at a small tea table, mask still fully on.
2-4s: Zahra pushes pastries toward him.
4-6s: Super Dziri looks at the tea glass and gestures toward his mask.
6-8s: Zahra laughs warmly.
8-10s: Super Dziri gives a thumbs-up.

Zahra:
"اشرب يا ولدي، الشاي يبرد!"

Super Dziri:
"شوفيني كياش نشرب بالقناع هذا؟ ههه!"

Natural Algerian Darija. Mask remains physically fixed.
```

### 24C — التصالح مع قويدر → السطح

**FILES**

```text
SDZ_24C_START_Kouider_Handshake.png
SDZ_24C_END_Rooftop_Sunset.png
```

```text
START REFERENCE FILE: SDZ_24C_START_Kouider_Handshake.png
END REFERENCE FILE: SDZ_24C_END_Rooftop_Sunset.png

0-2s:
Kouider extends his hand.

2-4s:
Super Dziri shakes it firmly.

4-6s:
Kouider says:
"شكرا يا سوبر ذزيري. الحومة راهي أهدى بيك."

6-7.5s:
Super Dziri answers:
"أنا واحد منكم... غير عندي قناع."

7.5-10s:
CINEMATIC TRANSITION:
Do NOT teleport the character.
End the handshake naturally. Super Dziri turns and walks away.
Cut only at the end to the rooftop sunset image. The final frame is
SDZ_24C_END_Rooftop_Sunset.png.

The rooftop is the same low Algerian rooftop established earlier.

Final inner voice:
"أنا سوبر ذزيري... وأنا واحد منكم."

Hold the final rooftop frame for editing.
```

---

# 6) أفضل تنظيم للصور

## صور يجب أن تكون مشتركة بين مشهدين

```text
SDZ_01_END_Anis_TomatoStall.png
→ used as Scene 01 END and Scene 02 START

SDZ_06_END_Thief_AlleyEntrance.png
→ used as Scene 06 END and Scene 07 START

SDZ_10_END_SuperDziri_Ready.png
→ used as Scene 10 END and Scene 11 START

SDZ_18_END_SuperDziri_RooftopReady.png
→ used as Scene 18 END and Scene 19 START

SDZ_22_END_AlleyCorner.png
→ used as Scene 22 END and Scene 23 START

SDZ_24C_END_Rooftop_Sunset.png
→ final frame
```

---

# 7) أهم قواعد الانتقال

### A → B
إذا عندك صورتان، لا تطلب من Seedance "make a transition".

اكتب:

```text
Start exactly from START IMAGE.
Move through a physically continuous sequence.
Reach END IMAGE naturally.
The final 1 second must closely match END IMAGE.
No jump cut.
No teleportation.
No morphing.
```

### اتجاه الحركة

إذا الشخصية تتحرك من اليسار إلى اليمين في الصورة الأولى:

```text
Maintain the same left-to-right screen direction.
```

إذا تدخل من الخلف:

```text
Maintain the same rear three-quarter orientation until the character naturally
turns toward the destination.
```

### المكان

```text
The location is the same physical location as the reference image.
Do not redesign the street, market, building or furniture.
```

### الملابس

```text
Exact wardrobe continuity. No clothing changes during the shot.
```

---

# 8) قواعد الكلام في 10 ثواني

**لا تستخدم حوارًا طويلًا مثل النسخة القديمة.**

القاعدة:

- جملة قصيرة = أفضل.
- متكلم واحد في اللقطة = أفضل.
- جملتين قصيرتين = ممكن.
- أكثر من شخصين يتكلمون في 10 ثوانٍ = خطر على الـlip-sync.

مثال جيد:

```text
Kouider:
"وقوف!"

Super Dziri:
"خويا، نفهمك!"
```

مثال سيئ:

```text
شخص يتكلم 5 ثوانٍ
+
شخص ثاني يتكلم 3 ثوانٍ
+
ضحك
+
حركة
+
مطاردة
```

لأن النموذج يبدأ يخلط بين الكلام وحركة الفم.

---

# 9) Negative Prompt خاص بالـLip Sync

```text
wrong lip sync, mouth moving without speech, wrong speaker speaking,
two characters speaking simultaneously, invented words, changed dialogue,
Arabic fusha pronunciation, robotic Arabic voice, unnatural Algerian accent,
English accent, French accent, exaggerated mouth movement, frozen mouth,
mouth deformation, duplicated voice, delayed speech, voice not matching character
```

---

# 10) ترتيب التوليد

لا تولد الـ24 فيديو دفعة واحدة.

### المرحلة 1
ولد صور الـSTART وEND للمشاهد الحرجة:

```text
01 → 02
06 → 07
10 → 11
17 → 18 → 19
22 → 23
24C
```

### المرحلة 2
اختبر فيديو واحد من كل نوع:

- مشي
- حوار
- تحول
- مطاردة
- Match Cut
- مشهد شخصيتين

### المرحلة 3
إذا ثبتت الشخصية والـlip-sync، ولّد باقي الفيديوهات.

### المرحلة 4
المونتاج:

```text
Scene 01
↓
Scene 02
↓
Scene 03
...
```

استعمل **Cut** في الانتقالات العادية.

استعمل **Match Cut** فقط عندما تكون الصورة/الحركة متطابقة.

---

# 11) معيار قبول كل فيديو

لا تعتبر الفيديو ناجحًا إلا إذا تحقق:

```text
[✓] نفس الوجه
[✓] نفس الملابس
[✓] نفس المكان
[✓] نفس الإضاءة
[✓] الحركة طبيعية
[✓] لا يوجد teleportation
[✓] لا توجد أطراف مشوهة
[✓] الكلام مطابق
[✓] المتكلم الصحيح فقط يحرك فمه
[✓] الدارجة طبيعية
[✓] النهاية تصلح كبداية للمشهد التالي
```

---

# 12) النتيجة المستهدفة

**الهدف ليس أن تكون كل صورة جميلة وحدها.**

الهدف:

```text
IMAGE 01
   ↓
حركة طبيعية 10s
   ↓
IMAGE 02
   ↓
حركة طبيعية 10s
   ↓
IMAGE 03
   ↓
حركة طبيعية 10s
   ↓
...
   ↓
FINAL ROOFTOP
```

يعني الصور تكون **نقاط ارتكاز للحركة**، والـPrompts تكون الجسر بينها.

هذه هي الطريقة التي يجب أن تُنتج بها النسخة النهائية حتى يبدو العمل كفيلم واحد، لا كمجموعة صور مولدة بالذكاء الاصطناعي.
