

# 🚀 khutwa_website

![khutwa_website Banner](https://github.com/vv7x-x/khutwa_website/blob/main/uploads/images/logo.png)

---

## 📌 نبذة عن المشروع
موقع ويب عصري متعدد الصفحات لخدمات الحج والعمرة والسياحة، بواجهة ديناميكية متجاوبة، مع دعم الروابط النظيفة ولوحات تحكم متقدمة، وإمكانية تخصيص التصميم والمحتوى بسهولة.

---

## ✨ مميزات المشروع

- واجهة عصرية متجاوبة (Responsive) مع أنيميشن جذاب (AOS.js).
- دعم الروابط النظيفة بدون .html (vercel.json).
- نظام حجز متكامل مع تحويل تلقائي لجروب واتساب بعد الحجز.
- تخصيص ألوان وخطوط وخلفيات من لوحة تحكم متقدمة (LocalStorage).
- إمكانية إضافة صفحات جديدة بسهولة وتنظيم الملفات تلقائيًا.
- دعم الصوتيات والمؤثرات الصوتية لكل صفحة.
- سكريبتات ديناميكية لتغيير العناوين وتفعيل الصفحة النشطة تلقائيًا.
- إمكانية ربط إعدادات متقدمة من صفحة settings.

---

## 🛠️ التقنيات المستخدمة

- HTML5, CSS3, JavaScript (Vanilla)
- مكتبة AOS.js للأنيميشن
- Sketchfab/3D Embeds (دليل مناسك تفاعلي)
- Node.js/Express (باك اند الحجز)
- Vercel (استضافة ودعم rewrites)

---

## 🔗 روابط مهمة

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-black?style=for-the-badge&logo=github)](https://github.com/vv7x-x/khutwa_website)
[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge&logo=google-chrome)](https://khutwa-website-xi.vercel.app/)
[![Download ZIP](https://img.shields.io/badge/Download-ZIP-blue?style=for-the-badge&logo=download)](https://github.com/vv7x-x/khutwa_website/archive/refs/heads/main.zip)
[![Contact](https://img.shields.io/badge/Contact-Email-red?style=for-the-badge&logo=gmail)](mailto:yvhyvredv@gmail.com)

---

## 🗂️ هيكلية المشروع

```
/
├── index.html                  # الصفحة الرئيسية
├── about.html                  # صفحة من نحن
├── booking.html                # صفحة الحجز
├── contact.html                # صفحة التواصل
├── gallery.html                # صفحة المعرض
├── offers.html                 # صفحة العروض
├── developer-info.html         # صفحة معلومات المطور
├── hacker-advanced-panel.html  # لوحة تحكم متقدمة
├── hacker-advanced-panel-pro.html # لوحة تحكم احترافية إضافية
├── pages/                      # صفحات فرعية وجديدة
├── uploads/                    # مجلد الملفات المرفوعة
│   ├── الأصوات/                # ملفات الصوت
│   ├── رحلاتنا السابقه/        # صور الرحلات السابقة
│   └── images/                 # صور عامة للموقع
├── robots.txt                  # ملف لمحركات البحث
├── sitemap.xml                 # ملف خريطة الموقع لمحركات البحث

└── sitemap-generator.js        # سكربت إنشاء خريطة الموقع
```

---

## � طريقة التشغيل محليًا

1. تأكد من وجود Node.js على جهازك (لخدمة الحجز).
2. شغل السيرفر الخلفي (Express) عبر:
   ```bash
   node main.js
   ```
3. افتح `index.html` مباشرة أو عبر سيرفر محلي (Live Server).
4. جميع الروابط تعمل بدون .html بفضل إعدادات vercel.json.

---

## 📬 نظام الحجز

- عند تعبئة نموذج الحجز يتم إرسال البيانات إلى باك اند Node.js (api/booking)، ثم تحويل المستخدم تلقائيًا إلى جروب واتساب.
- يمكن ربط الحجز مع Google Sheets أو أي API آخر بسهولة.

---

## �💡 نصائح تنظيمية

- ضع صفحات جديدة داخل مجلد `pages/` للحفاظ على تنظيم المشروع.  
- احفظ ملفات الصوت داخل `uploads/الأصوات/`.  
- الصور تحفظ في `uploads/رحلاتنا السابقه/` أو داخل مجلد صور آخر داخل `uploads/`.  
- تجنب وضع ملفات عشوائية في جذر المشروع، باستثناء الملفات الرئيسية.  
- يمكنك إضافة مجلدات فرعية إضافية داخل `uploads/` حسب الحاجة، مثل `uploads/docs/`.

---

## 🎨 التخصيص والإعدادات

جميع إعدادات لوحة التحكم (ألوان، تصميم، خيارات) تحفظ تلقائيًا في LocalStorage ويمكن تصديرها واستيرادها من الواجهة. التخصيص يتم مباشرة من صفحات اللوحات المتقدمة.

---

## � صور من المشروع

> يمكنك إضافة صور أو سكرينشوتات هنا لإبراز شكل الموقع (مثال: الصفحة الرئيسية، صفحة الحجز، دليل المناسك التفاعلي).

---

## 🤝 الدعم والمساهمة

لأي استفسار أو دعم، تواصل عبر صفحة [developer-info](https://khutwa-website-wine.vercel.app/developer-info.html) أو البريد: [yvhyvredv@gmail.com](mailto:yvhyvredv@gmail.com).

---

## 📄 الرخصة

[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg?style=for-the-badge)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

**شكراً لاستخدامك مشروع khutwa_website!**
