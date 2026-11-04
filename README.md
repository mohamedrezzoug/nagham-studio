# نغمة – ستوديو المواهب الموسيقية 🎵

ستوديو موسيقي كامل فالمتصفح: بيانو وآلات، دربوكة وإيقاعات مغربية، قيثارة ومقامات، غناء، دروس، مدارس للمبتدئين، ورشة الإبداع، واختبارات المواهب.

## النشر على GitHub Pages
```bash
cd nagham
git init && git add . && git commit -m "نغمة v1"
git branch -M main
git remote add origin https://github.com/mohamedrezzoug/nagham.git
git push -u origin main
```
من بعد: Settings → Pages → Branch: `main` / `root` → Save.
الرابط: https://mohamedrezzoug.github.io/nagham/

## الملفات
- `index.html` — التطبيق كامل
- `manifest.json` — معلومات التثبيت (PWA)
- `sw.js` — باش يخدم بلا إنترنت
- `icons/` — الأيقونات

## التحديث
ملي تبدل `index.html`، بدّل حتى `CACHE = 'nagham-v1'` فـ `sw.js` لـ `v2`… باش التيليفونات ياخدو النسخة الجديدة.
