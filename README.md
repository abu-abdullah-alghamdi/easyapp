# azirapp للتجار

صفحة هبوط azirapp للتجار — عربي (RTL) وإنجليزي (LTR) في صفحة واحدة مع زر تبديل اللغة.

## الملفات

```
index.html          الصفحة كاملة (العربي والإنجليزي)
assets/
  fonts/            خط TT Commons Pro (4 أوزان)
  js/lenis.min.js   السكرول الناعم (Lenis 1.3.26 — MIT)
  hero-bg.webp      خلفية القسم الأول
  app-store.webp    صورة واجهة المتجر
  favicon.svg       أيقونة تاب المتصفح
  logo-black.svg / logo-white.svg
```

## اللغة

- الافتراضي عربي.
- `?lang=en` يفتح الصفحة بالإنجليزي مباشرة.
- الموقع يتذكر آخر لغة اختارها الزائر.
- الترجمة الإنجليزية موجودة في سكربت اللغة داخل `index.html`.

## الرفع على استضافة

ارفع `index.html` ومجلد `assets` كما هم إلى جذر الموقع (مثلاً `public_html`)،
أو اسحب المجلد كاملاً في Netlify / Cloudflare Pages.
