# تعليمات للوكيل الذي سيصنع الفيديو النهائي

أنت وكيل إنتاج فيديو. المطلوب إنشاء فيلم قصير عمودي 9:16 مدته 60 ثانية من الصور والنصوص الموجودة في هذا المجلد.

## المدخلات

- صور الشخصيات المرجعية:
  - `assets/references/01_yacine_reference.png`
  - `assets/references/02_fatima_reference.png`

- صور المشاهد:
  - `assets/scenes/scene_01_yacine_alone.png`
  - `assets/scenes/scene_02_help_old_woman.png`
  - `assets/scenes/scene_03_fatima_recognizes.png`
  - `assets/scenes/scene_04_crossing_road.png`
  - `assets/scenes/scene_05_bracelet_falls.png`
  - `assets/scenes/scene_06_yacine_shocked.png`
  - `assets/scenes/scene_07_fatima_crying.png`
  - `assets/scenes/scene_flashback_market.png` اختياري بين المشهد 7 و8 لمدة ثانية واحدة
  - `assets/scenes/scene_08_scar_reveal.png`
  - `assets/scenes/scene_09_reunion_hug.png`

- بيانات منظمة:
  - `docs/scene_metadata.json`

- Prompts تفصيلية:
  - `docs/prompts_and_video_plan.md`

- ترجمات:
  - `subtitles/arabic_dz.srt`
  - `subtitles/arabic_fusha.srt`
  - `subtitles/english.srt`

## المطلوب

1. حرك كل صورة حسب `video_prompt` الموجود في `scene_metadata.json`.
2. حافظ على نفس الوجوه واللباس في كل اللقطات.
3. لا تضف نصوص داخل الصور أثناء التحريك؛ الترجمة تضاف في المونتاج فقط.
4. ركّب المشاهد حسب التوقيت التالي:

```text
scene_01: 00:00-00:05
scene_02: 00:05-00:12
scene_03: 00:12-00:19
scene_04: 00:19-00:27
scene_05: 00:27-00:34
scene_06: 00:34-00:42
scene_07: 00:42-00:50
optional flashback: 00:49-00:50
scene_08: 00:50-00:56
scene_09: 00:56-01:00
```

5. أضف Voice Over بالدراجة الجزائرية من ملف:

```text
docs/dialogue_dz.txt
```

6. أضف ترجمة واضحة أسفل الفيديو، يفضل استعمال `arabic_dz.srt`.
7. أضف موسيقى بيانو حزينة ومؤثرة بدون صوت غناء.
8. أضف SFX:
   - شارع وسيارات خفيفة في البداية.
   - صوت خطوات.
   - صوت سقوط سوار معدني في scene_05.
   - صمت قصير قبل الكشف في scene_08.
   - ارتفاع الموسيقى في الحضن النهائي.

## إعدادات التصدير

```text
Format: MP4
Resolution: 1080x1920
FPS: 30
Duration: 60 seconds
Audio: voice over + soft music + SFX
Style: realistic emotional cinematic short film
```

## ملاحظات مهمة جداً

- لا تغير وجه ياسين ولا وجه فاطمة.
- الندبة الصغيرة فوق حاجب ياسين الأيسر مهمة للقصة.
- السوار الفضي بحرف Y مهم للقصة.
- الحجاب الأبيض والمعطف البني لفاطمة لازم يبقاو نفسهم.
- جاكيت ياسين الأسود وقميصه الرمادي لازم يبقاو نفسهم.
- النهاية لازم تكون مؤثرة وبطيئة: حضن + دموع + موسيقى.
