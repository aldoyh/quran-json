فيما يلي **الترجمة إلى العربية** مع الحفاظ الكامل على المعنى والدقة التقنية دون الإخلال بالمصطلحات أو الروابط:

---

# Quran JSON

[![أحدث إصدار](https://badgen.net/npm/v/quran-json)](https://www.npmjs.com/package/quran-json)

نص القرآن الكريم، والنقل الصوتي (Transliteration)، والترجمات بصيغة JSON.

## CDN

يمكنك الاطلاع على مجلد [`/dist`](https://github.com/risan/quran-json/tree/master/dist) لمشاهدة جميع ملفات JSON المتاحة. كما تتوفر ملفات JSON عبر شبكة CDN الخاصة بـ [JSDELIVR](https://www.jsdelivr.com/package/npm/quran-json?path=dist).

### الحصول على نص القرآن كاملًا مع الترجمات

يستخدم هذا المشروع نص القرآن العثماني من **[موسوعة القرآن الكريم](https://quranenc.com/en/home)**.
أما النقل الصوتي باللغة الإنجليزية فهو مأخوذ من **[Tanzil.net](https://tanzil.net/trans/en.transliteration)**.
الترجمات متوفرة بعدة لغات كما يلي:

* نص القرآن فقط:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran.json)
* النقل الصوتي الإنجليزي للقرآن:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_transliteration.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran.json)
* `bn` البنغالية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_bn.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_bn.json)
* `zh` الصينية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_zh.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_zh.json)
* `en` الإنجليزية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_en.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_en.json)
* `es` الإسبانية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_es.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_es.json)
* `fr` الفرنسية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_fr.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_fr.json)
* `id` الإندونيسية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_id.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_id.json)
* `ru` الروسية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ru.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ru.json)
* `sv` السويدية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_sv.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_sv.json)
* `tr` التركية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_tr.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_tr.json)
* `ur` الأردية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ur.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ur.json)

### الحصول على قائمة السور

* العربية فقط:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/index.json)
* البنغالية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/bn/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/bn/index.json)
* الصينية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/zh/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/zh/index.json)
* الإنجليزية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/index.json)
* الإسبانية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/es/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/es/index.json)
* الفرنسية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/fr/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/fr/index.json)
* الإندونيسية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/index.json)
* الروسية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ru/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ru/index.json)
* السويدية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/sv/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/sv/index.json)
* التركية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/tr/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/tr/index.json)
* الأردية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ur/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ur/index.json)

### الحصول على سورة واحدة

يمكنك جلب سورة واحدة بتحديد رقم السورة `chapterNumber` (من 1 إلى 114).
يتم توفير نص القرآن والنقل الصوتي لكل سورة. وللحصول على الترجمة، يمكنك تحديد رمز اللغة `langCode`:

```text
# نص القرآن مع النقل الصوتي:
https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/{chapterNumber}.json

# نص القرآن مع النقل الصوتي والترجمة:
https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/{langCode}/{chapterNumber}.json
```

أمثلة:

* سورة *الفاتحة* (نص فقط):
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/1.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/1.json)
* سورة *الرحمن* مع الترجمة الإنجليزية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/55.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/55.json)
* سورة *الإخلاص* مع الترجمة الإندونيسية:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/112.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/112.json)

### الحصول على آية واحدة

يمكنك جلب آية واحدة بتحديد رقم الآية `verseNumber` (من 1 إلى 6236):

```text
https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/{verseNumber}.json
```

على عكس باقي ملفات JSON، يحتوي ملف الآية الواحدة على **جميع الترجمات المتوفرة**.

أمثلة:

* الآية الأولى من سورة *الفاتحة*:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/1.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/1.json)
* الآية السادسة من سورة *الناس*:
  [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/6236.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/6236.json)

## توليد ملفات JSON

إذا رغبت في توليد ملفات JSON بنفسك:

### 1. استنساخ المستودع

قم باستنساخ المستودع إلى جهازك المحلي:

```bash
$ git clone git@github.com:risan/quran-json.git
```

### 2. تثبيت الاعتمادات

انتقل إلى مجلد المشروع ثم ثبّت الاعتمادات:

```bash
# الانتقال إلى مجلد المشروع
$ cd quran-json

# تثبيت الاعتمادات
$ npm install
```

### 3. توليد ملفات JSON

نفّذ الأمر التالي لتوليد ملفات JSON:

```bash
$ npm run build
```

## مصادر البيانات

* نص القرآن العثماني: **[موسوعة القرآن الكريم](https://quranenc.com/en/home)**
* النقل الصوتي الإنجليزي: **[tanzil.net](https://tanzil.net/trans/en.transliteration)**
* الترجمة البنغالية: تأليف محيي الدين خان — المصدر: tanzil.net
* الترجمة الإنجليزية: تأليف أم محمد (صحيح إنترناشونال) — المصدر: tanzil.net
* الترجمة الإسبانية: تأليف محمد عيسى غارسيا — المصدر: tanzil.net
* الترجمة الفرنسية: تأليف محمد حميد الله — المصدر: tanzil.net
* الترجمة الإندونيسية: وزارة الشؤون الإسلامية الإندونيسية — المصدر: موسوعة القرآن الكريم
* الترجمة الروسية: تأليف إلمير كولييف — المصدر: tanzil.net
* الترجمة السويدية: تأليف كنوت بيرنستروم — المصدر: tanzil.net
* الترجمة التركية: رئاسة الشؤون الدينية التركية — المصدر: tanzil.net
* الترجمة الأردية: تأليف أبو الأعلى المودودي — المصدر: tanzil.net
* الترجمة الصينية: تأليف محمد ماكين — المصدر: موسوعة القرآن الكريم

## الرخصة

[CC-BY-SA 4.0](https://github.com/risan/quran-json/blob/master/LICENSE.txt) ·
[Risan Bagja Pradana](https://risanb.com)

---

إذا رغبت، أقدر أجهّز لك **نسخة Markdown عربية جاهزة للنشر** أو **تعريب أسماء المفاتيح داخل JSON** نفسه 🔍📦

---

# Quran JSON

[![Latest Version](https://badgen.net/npm/v/quran-json)](https://www.npmjs.com/package/quran-json)

Quran text, transliteration, and translations in JSON format.

## CDN

Check out the [`/dist`](https://github.com/risan/quran-json/tree/master/dist) to see all available JSON files. The JSON files are also available through [JSDELIVR](https://www.jsdelivr.com/package/npm/quran-json?path=dist) CDN.

### Get The Entire Quran Text & Translations

This project is using the Uthmani Quran text from the [The Noble Qur'an Encyclopedia](https://quranenc.com/en/home). While the English transliteration is sourced from [Tanzil.net](https://tanzil.net/trans/en.transliteration). The translations are available in several languages:

- Quran text only: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran.json)
- Quran English transliteration: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_transliteration.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran.json)
- `bn` Bengali: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_bn.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_bn.json)
- `zh` Chinese: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_zh.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_zh.json)
- `en` English: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_en.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_en.json)
- `es` Spanish: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_es.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_es.json)
- `fr` French: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_fr.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_fr.json)
- `id` Indonesian: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_id.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_id.json)
- `ru` Russian: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ru.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ru.json)
- `sv` Swedish: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_sv.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_sv.json)
- `tr` Turkish: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_tr.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_tr.json)
- `ur` Urdu: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ur.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/quran_ur.json)

### Get the List of Chapters

- Arabic only: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/index.json)
- Bengali: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/bn/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/bn/index.json)
- Chinese: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/zh/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/zh/index.json)
- English: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/index.json)
- Spanish: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/es/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/es/index.json)
- French: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/fr/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/fr/index.json)
- Indonesian: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/index.json)
- Russian: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ru/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ru/index.json)
- Swedish: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/sv/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/sv/index.json)
- Turkish: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/tr/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/tr/index.json)
- Urdu: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ur/index.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/ur/index.json)

### Get a Chapter

You can get a single chapter (surah) by providing its `chapterNumber` (`1-114`). Both Quran text and its transliteration are provided on each chapter. To get the translation you can also provide the `langCode`:

```
# Quran text & transliteration:
https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/{chapterNumber}.json

# Quran text, transliteration, and translation:
https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/{langCode}/{chapterNumber}.json
```

For example:

* *Al-Fatihah* Quran text only: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/1.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/1.json)
* *Al-Rahman* with English translation: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/55.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/en/55.json)
* *Al-Ikhlas* with Indonesian translation: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/112.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/chapters/id/112.json)

### Get a Verse

You can get a single verse (ayah) by providing its `verseNumber` (`1-6236`).

```
https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/{verseNumber}.json
```

Unlike the rest of the JSON files, a single verse JSON file contains all available translations.

For example:

* *Al-Fatihah* verse #1: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/1.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/1.json)
* *An-Nas* verse #6: [`cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/6236.json`](https://cdn.jsdelivr.net/npm/quran-json@3.1.2/dist/verses/6236.json)

## Generate the JSON

If you want to generate the JSON files by yourself:

### 1. Clone the Repository

Clone this repository to your local computer:

```bash
$ git clone git@github.com:risan/quran-json.git
```

### 2. Install the Dependencies

`CD` into the project directory and install the dependencies:

```bash
# Go to the project directory
$ cd quran-json

# Install the dependencies
$ npm install
```

### 3. Generate the JSON Files

Run the following command to generate the JSON files:

```bash
$ npm run build
```

## Data Source

* The Uthmani Quran text is from [The Noble Qur'an Encyclopedia](https://quranenc.com/en/home).
* The English transliteration is from [tanzil.net](https://tanzil.net/trans/en.transliteration).
* The Bengali translation is authored by Muhiuddin Khan, and it's sourced from [tanzil.net](https://tanzil.net/trans/bn.bengali).
* The English translation is authored by Umm Muhammad (Saheeh International), and it's sourced from [tanzil.net](https://tanzil.net/trans/en.sahih).
* The Spanish translation is authored by Muhammad Isa García, and it's sourced from [tanzil.net](https://tanzil.net/trans/es.garcia).
* The French translation is authored by Muhammad Hamidullah, and it's sourced from [tanzil.net](https://tanzil.net/trans/fr.hamidullah).
* The Indonesian translation is authored by Indonesian Islamic Affairs Ministry, and it's sourced from [The Noble Qur'an Encyclopedia](https://quranenc.com/en/browse/indonesian_affairs).
* The Russian translation is authored by Elmir Kuliev, and it's sourced from [tanzil.net](https://tanzil.net/trans/ru.kuliev).
* The Swedish translation is authored by Knut Bernström, and it's sourced from [tanzil.net](https://tanzil.net/trans/sv.bernstrom).
* The Turkish translation is authored by Turkish Directorate of Religious Affairs, and it's sourced from [tanzil.net](https://tanzil.net/trans/tr.diyanet).
* The Urdu translation is authored by Abul A'la Maududi, and it's sourced from [tanzil.net](https://tanzil.net/trans/ur.maududi).
* The Chinese translation is authored by Muhammad Makin, and it's sourced from [The Noble Qur'an Encyclopedia](https://quranenc.com/en/browse/chinese_makin).

## License

[CC-BY-SA 4.0](https://github.com/risan/quran-json/blob/master/LICENSE.txt) · [Risan Bagja Pradana](https://risanb.com)
