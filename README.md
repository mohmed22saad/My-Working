# دليل نظام OASIS Plus - المراحل التعليمية

موقع تعليمي لشرح نظام OASIS Plus للإدارة الطبية.

## 🚀 طريقة النشر

### الخيار 1: GitHub Pages (الأفضل)

1. **إنشاء مستودع GitHub جديد:**
   - اذهب إلى [github.com](https://github.com)
   - أنشئ مستودع جديد باسم `oasis-guide`
   - اجعل المستودع عام (Public)

2. **رفع الملفات:**
   ```bash
   cd "d:/My Web Side/موقع مراحل"
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/USERNAME/oasis-guide.git
   git push -u origin main
   ```

3. **تفعيل GitHub Pages:**
   - اذهب إلى إعدادات المستودع (Settings)
   - اضغط على "Pages" في القائمة الجانبية
   - في قسم "Build and deployment" اختر:
     - Source: Deploy from a branch
     - Branch: main
     - Folder: / (root)
   - اضغط "Save"

4. **رابط الموقع:**
   - بعد دقيقة سيظهر رابط الموقع:
   ```
   https://USERNAME.github.io/oasis-guide/
   ```

### الخيار 2: Netlify (الأسهل)

1. **افتح موقع Netlify Drop:**
   - اذهب إلى [app.netlify.com/drop](https://app.netlify.com/drop)

2. **اسحب المجلد:**
   - اسحب مجلد `موقع مراحل` وأفلته في الصفحة
   - انتظر ثوانٍ قليلة

3. **رابط الموقع:**
   - ستحصل على رابط مثل:
   ```
   https://random-name.netlify.app
   ```

4. **تغيير اسم الموقع (اختياري):**
   - اضغط "Site settings"
   - اضغط "Change site name"
   - اختر اسماً سهلاً مثل `oasis-guide`

### الخيار 3: Vercel

1. **تثبيت Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **نشر الموقع:**
   ```bash
   cd "d:/My Web Side/موقع مراحل"
   vercel
   ```

3. **اتبع التعليمات:**
   - اضغط Enter لكل سؤال
   - ستحصل على رابط الموقع

## 📁 محتويات الموقع

- `index.html` - الصفحة الرئيسية
- `styles.css` - التنسيق
- `script.js` - التفاعلية
- `README.md` - هذا الملف

## ✨ المميزات

- تصميم عربي RTL احترافي
- متجاوب مع جميع الأجهزة
- تحريكات سلسة
- سهل التنقل

## 📝 الترخيص

مفتوح المصدر للاستخدام التعليمي
