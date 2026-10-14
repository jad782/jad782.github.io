# خطوط صفحات مصحف المدينة (QCF v2) — نسخة تطبيق الأنوار

**المصدر:** خطوط مجمع الملك فهد لطباعة المصحف الشريف (King Fahd Glorious Qur'an Printing Complex)، إصدار الخط الثاني لصفحات المصحف (`QCF2001`…`QCF2604` + `QCF2BSML`). الملفات الأصلية بصيغة TTF من موقع المجمّع `qurancomplex.gov.sa`، ومرآتها مستودع `nuqayah/qpc-fonts` (مجلد `mushaf-v2`).

**ما الذي تغيّر:** لا شيء في الرسم أو الحروف أو الجداول. التعديل الوحيد هو **تحويل الصيغة من TTF إلى WOFF2** (ضغط بلا فقد، بأداة fontTools) لتصغير التنزيل. وقد تحقّقنا آلياً من تطابق ترتيب المحارف وجدول `cmap` وحدود كلّ محرف وجداول `GSUB/GPOS` بين كلّ ملف أصلي ونسخته.

**الحقوق والترخيص:** الخطوط ملك لمجمع الملك فهد لطباعة المصحف الشريف، وتُستعمل بشروطه كما ينشرها على موقعه. هذا المستودع ليس من المجمّع ولا يدّعي أيّ حقّ فيها؛ وهو يخدم تطبيق «الأنوار» لعرض المصحف فقط.

**الاستعمال من التطبيق:**
```
https://cdn.jsdelivr.net/gh/jad782/jad782.github.io@fonts-v1/anwar-fonts/qcf2/QCF2001.woff2
https://jad782.github.io/anwar-fonts/qcf2/QCF2001.woff2   (احتياط)
```
`qcf2/manifest.json` يحوي حجم كلّ ملف والمجموع ليعرضه التطبيق قبل التنزيل.

---

# Madinah Mushaf page fonts (QCF v2) — Al-Anwar app copy

**Source:** the King Fahd Glorious Qur'an Printing Complex page fonts, version 2 (`QCF2001`…`QCF2604` plus `QCF2BSML`). The original TTF files come from the Complex (`qurancomplex.gov.sa`) and are mirrored in `nuqayah/qpc-fonts` (`mushaf-v2`).

**What changed:** nothing in the glyphs, characters or tables. The only change is the **container format, TTF → WOFF2** (lossless compression via fontTools). Each converted file was checked automatically against its original: glyph order, `cmap`, every glyph's outline and the `GSUB/GPOS` tables are identical.

**Rights:** the fonts belong to the King Fahd Complex and are used under the terms it publishes on its site. This repository is not affiliated with the Complex and claims no rights; it only serves the Al-Anwar app's mushaf view.
