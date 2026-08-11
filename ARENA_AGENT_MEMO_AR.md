# مذكرة للوكيل - إنشاء فيديو قصير من مستودع القصص

## اسم المستودع

```text
latchi-short-films-stories
```

## رابط المستودع

```text
https://github.com/iskande233/latchi-short-films-stories
```

## حالة المستودع

```text
Public
```

## المهمة المطلوبة من الوكيل

إنشاء فيديو قصير كامل مدته حوالي 60 ثانية، عمودي 9:16، اعتماداً على الصور والنصوص والبرومبتات الموجودة داخل المستودع.

الفيديو المطلوب حالياً هو:

```text
films/001_al_maraa_elli_rjaat
```

العنوان:

```text
المرأة اللي رجعت
```

القصة:

```text
شاب جزائري يساعد عجوز في الطريق، وفي الأخير يكتشف أنها أمه التي ضاعت منه وهو صغير.
```

---

## أهم الملفات التي يجب على الوكيل قراءتها أولاً

### 1) تعليمات الإنتاج المختصرة

```text
films/001_al_maraa_elli_rjaat/docs/video_agent_instruction.md
```

هذا هو أهم ملف. يحتوي على تعليمات مباشرة لإنشاء الفيديو.

### 2) ملف تفاصيل الإنتاج

```text
films/001_al_maraa_elli_rjaat/docs/production_brief.md
```

فيه:

- ملخص القصة.
- وصف الشخصيات.
- طريقة الحفاظ على نفس الوجوه.
- الترتيب الزمني للمشاهد.
- Voice Over كامل بالدراجة الجزائرية.
- إعدادات التصدير.

### 3) ملف البيانات المنظمة

```text
films/001_al_maraa_elli_rjaat/docs/scene_metadata.json
```

فيه بيانات كل مشهد بشكل JSON:

- اسم الصورة.
- بداية ونهاية اللقطة.
- مدة اللقطة.
- الحوار بالدراجة.
- الترجمة العربية.
- الترجمة الإنجليزية.
- Prompt تحريك الصورة إلى فيديو.

### 4) ملف البرومبتات المفصل

```text
films/001_al_maraa_elli_rjaat/docs/prompts_and_video_plan.md
```

فيه لكل مشهد:

- Prompt الصورة.
- Prompt الفيديو.
- الحوار.
- الترجمة.
- حركة الكاميرا.

---

## الصور المرجعية للشخصيات

لازم استعمال هذه الصور كـ Character Reference في أي أداة AI تدعم ذلك:

```text
films/001_al_maraa_elli_rjaat/assets/references/01_yacine_reference.png
films/001_al_maraa_elli_rjaat/assets/references/02_fatima_reference.png
```

### ياسين

```text
شاب جزائري عمره 27 سنة، شعر أسود قصير، لحية خفيفة، عيون بنية، وجه حزين وطيب، ندبة صغيرة فوق الحاجب الأيسر، جاكيت أسود، قميص رمادي.
```

### فاطمة

```text
امرأة جزائرية مسنة عمرها 58 سنة، وجه متعب لكن حنون، عيون بنية حزينة، حجاب أبيض قديم، معطف بني، كيس قماشي قديم، سوار فضي في اليد اليمنى عليه حرف Y.
```

---

## صور المشاهد بالترتيب

```text
films/001_al_maraa_elli_rjaat/assets/scenes/scene_01_yacine_alone.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_02_help_old_woman.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_03_fatima_recognizes.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_04_crossing_road.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_05_bracelet_falls.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_06_yacine_shocked.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_07_fatima_crying.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_flashback_market.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_08_scar_reveal.png
films/001_al_maraa_elli_rjaat/assets/scenes/scene_09_reunion_hug.png
```

ملاحظة:

```text
scene_flashback_market.png
```

لقطة اختيارية قصيرة جداً بين المشهد 7 والمشهد 8، مدتها 1 ثانية تقريباً.

---

## ترتيب الفيديو والتوقيت

```text
scene_01: 00:00 - 00:05
scene_02: 00:05 - 00:12
scene_03: 00:12 - 00:19
scene_04: 00:19 - 00:27
scene_05: 00:27 - 00:34
scene_06: 00:34 - 00:42
scene_07: 00:42 - 00:50
flashback optional: 00:49 - 00:50
scene_08: 00:50 - 00:56
scene_09: 00:56 - 01:00
```

---

## ملفات الترجمة

```text
films/001_al_maraa_elli_rjaat/subtitles/arabic_dz.srt
films/001_al_maraa_elli_rjaat/subtitles/arabic_fusha.srt
films/001_al_maraa_elli_rjaat/subtitles/english.srt
```

يفضل استعمال:

```text
arabic_dz.srt
```

لأنه مناسب للفيديو باللهجة الجزائرية.

---

## ملف الحوار الكامل

```text
films/001_al_maraa_elli_rjaat/docs/dialogue_dz.txt
```

استعمله لتسجيل Voice Over باللهجة الجزائرية.

---

## إعدادات إخراج الفيديو

```text
Format: MP4
Resolution: 1080x1920
Aspect ratio: 9:16
FPS: 30
Duration: 60 seconds
Style: realistic cinematic emotional drama
Language: Algerian Darija
Subtitles: Arabic DZ
Music: emotional piano, sad but hopeful
```

---

## تعليمات مهمة جداً للحفاظ على الجودة

1. لا تغير وجه ياسين بين اللقطات.
2. لا تغير وجه فاطمة بين اللقطات.
3. الندبة فوق حاجب ياسين الأيسر مهمة للقصة.
4. السوار الفضي بحرف Y مهم جداً.
5. لا تضف كتابة داخل الصور أثناء التحريك؛ الترجمة تكون في المونتاج فقط.
6. حافظ على نفس الملابس:
   - ياسين: جاكيت أسود + قميص رمادي.
   - فاطمة: حجاب أبيض + معطف بني.
7. اجعل الحركة هادئة وسينمائية:
   - slow zoom
   - subtle camera movement
   - emotional facial micro-movements
   - no exaggerated motion
8. أضف مؤثر سقوط السوار في المشهد 5.
9. أضف صمت قصير قبل كشف الندبة.
10. النهاية لازم تكون مؤثرة: حضن، دموع، موسيقى بيانو ترتفع.

---

## Prompt عام يستعمل مع كل لقطة فيديو

```text
Use the provided image as the first frame and keep the same character identity. Realistic cinematic emotional drama, vertical 9:16, subtle motion, slow camera movement, natural facial micro-expressions, no face change, no clothing change, no distortion, no text, no watermark.
```

## Negative Prompt عام

```text
different face, changed identity, different clothes, deformed face, bad hands, extra fingers, blurry, cartoon, anime, distorted body, watermark, wrong age, text artifacts, face morphing
```

---

## المطلوب النهائي

على الوكيل تسليم:

```text
final_video.mp4
```

مع نسخة اختيارية بدون ترجمة:

```text
final_video_no_subtitles.mp4
```
