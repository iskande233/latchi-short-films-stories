# Production Brief - المرأة اللي رجعت

## معلومات عامة

```text
Title: المرأة اللي رجعت
Type: Short Film / Emotional Drama / Twist Ending
Duration: 60 seconds
Aspect Ratio: 9:16 Vertical
Language: Algerian Dialect
Target Platforms: TikTok, Instagram Reels, YouTube Shorts, Facebook Reels
```

## ملخص القصة
شاب اسمه ياسين يساعد امرأة عجوز في الطريق. عندما يسقط منها سوار قديم عليه حرف Y، يبدأ ياسين في الشك. العجوز تعترف أنها فقدت ابنها الصغير ياسين في السوق منذ عشرين سنة. ياسين يريها ندبة فوق حاجبه ويذكرها بجملة كانت تقولها له أمه. في النهاية يكتشف أنها أمه التي ضاعت منه وهو صغير.

## الشخصيات المرجعية

### ياسين
Reference image:

```text
assets/references/01_yacine_reference.png
```

وصف ثابت:

```text
شاب جزائري عمره 27 سنة، شعر أسود قصير، لحية خفيفة، عيون بنية، وجه حزين وطيب، ندبة صغيرة فوق الحاجب الأيسر، يلبس جاكيت أسود فوق قميص رمادي.
```

Prompt ثابت:

```text
YACINE_REF: a 27-year-old Algerian man, short black hair, light stubble beard, brown eyes, kind sad face, small scar above his left eyebrow, wearing a black jacket over a gray shirt, realistic cinematic style, same face identity, consistent character.
```

### فاطمة / الأم
Reference image:

```text
assets/references/02_fatima_reference.png
```

وصف ثابت:

```text
امرأة جزائرية مسنة عمرها 58 سنة، وجه متعب لكن حنون، عيون بنية حزينة، تجاعيد خفيفة، حجاب أبيض قديم، معطف بني بسيط، تحمل كيس قماشي قديم، عندها سوار فضي في يدها اليمنى عليه حرف Y.
```

Prompt ثابت:

```text
FATIMA_REF: a 58-year-old Algerian elderly woman, tired but kind face, brown sad eyes, light wrinkles, wearing an old white hijab and a simple brown coat, holding a worn fabric bag, silver bracelet on her right wrist with a small letter Y, realistic cinematic style, same face identity, consistent character.
```

## قاعدة الحفاظ على نفس الوجوه

في كل أداة AI لتحريك الصور إلى فيديو:

```text
Use the provided reference image. Keep the same face identity, same clothes, same age, same hairstyle, same scar, same hijab, same emotional cinematic realistic style. Do not change the character face.
```

Negative Prompt:

```text
different face, changed identity, different clothes, deformed face, bad hands, extra fingers, blurry, cartoon, anime, distorted body, watermark, wrong age, text artifacts
```

## إعدادات الفيديو النهائية

```text
Resolution: 1080x1920
FPS: 24 or 30
Duration: 60 seconds
Color: warm sunset, emotional cinematic, soft contrast
Music: emotional piano with soft strings
SFX: street ambience, footsteps, bracelet metal drop, silence before reveal
```

## ترتيب اللقطات

| Scene | Image | Time | Duration |
|---|---|---:|---:|
| 01 | assets/scenes/scene_01_yacine_alone.png | 00:00-00:05 | 5s |
| 02 | assets/scenes/scene_02_help_old_woman.png | 00:05-00:12 | 7s |
| 03 | assets/scenes/scene_03_fatima_recognizes.png | 00:12-00:19 | 7s |
| 04 | assets/scenes/scene_04_crossing_road.png | 00:19-00:27 | 8s |
| 05 | assets/scenes/scene_05_bracelet_falls.png | 00:27-00:34 | 7s |
| 06 | assets/scenes/scene_06_yacine_shocked.png | 00:34-00:42 | 8s |
| 07 | assets/scenes/scene_07_fatima_crying.png | 00:42-00:50 | 8s |
| Flashback optional | assets/scenes/scene_flashback_market.png | 00:49-00:50 | 1s |
| 08 | assets/scenes/scene_08_scar_reveal.png | 00:50-00:56 | 6s |
| 09 | assets/scenes/scene_09_reunion_hug.png | 00:56-01:00 | 4s |

## Voice Over كامل بالدراجة الجزائرية

```text
كان ياسين دايماً يقول: أمي ضاعت عليا وأنا صغير.

نهار من النهارات، وهو راجع من الخدمة، شاف عجوز واقفة في الطريق، ما قدرتش تقطع.

قرب منها وقالها: يمّا، نعاونك تقطعي الطريق؟

شافت فيه وسكتت... كأنها تعرفو.

كي وصلها للجهة الأخرى، طاح منها سوار قديم.

ياسين هزّو... ولقا فيه حرف Y.

قلبو حبّس.

قالها: هذا السوار... منين جبتيه؟

العجوز بدات تبكي وقالت: كان عندي وليدي صغير... اسمو ياسين... وضاع مني في السوق من عشرين عام.

ياسين ورّاها الندبة اللي فوق حاجبو.

قالها بصوت مكسور: يمّا... كنتي تقوليلي: ما تبكيش يا ضو عيني.

العجوز رجفت، حطت يدها على وجهو وقالت: ياسين؟ ولدي؟

وفي هذيك اللحظة، ماكانش لقاء عادي.

كان حضن رجع بعد عشرين عام.
```

## ملفات مهمة

- `docs/scene_metadata.json`: بيانات منظمة لكل مشهد.
- `docs/prompts_and_video_plan.md`: Prompts تفصيلية لكل مشهد.
- `subtitles/arabic_dz.srt`: ترجمة/كابشن بالدراجة الجزائرية.
- `subtitles/arabic_fusha.srt`: ترجمة عربية فصحى.
- `subtitles/english.srt`: ترجمة إنجليزية.
- `docs/dialogue_dz.txt`: الحوار كامل.
- `docs/video_agent_instruction.md`: تعليمات مختصرة للوكيل الذي سيصنع الفيديو.
