# حاسبة قراءة القامة لسُمك البلاطة

تطبيق ويب (PWA) يشتغل على الموبايل وبدون إنترنت بعد أول فتح.

## الرفع على GitHub Pages
1. أنشئ Repository جديد (مثلاً `slab-calc`).
2. ارفع كل محتويات هذا المجلد (index.html, manifest.json, sw.js, مجلد icons).
3. من Settings ← Pages ← Source: `Deploy from a branch` ← Branch: `main` / `(root)` ← Save.
4. افتح الرابط: `https://USERNAME.github.io/slab-calc/`

## التثبيت على الموبايل
- أندرويد (Chrome): القائمة ⋮ ← "تثبيت التطبيق" / "Add to Home screen".
- آيفون (Safari): زر المشاركة ← "Add to Home Screen".

## ملاحظة عند التعديل
لو عدّلت أي ملف، غيّر رقم `CACHE` في `sw.js` (مثلاً `slab-calc-v2`) عشان التحديث يوصل للأجهزة.
