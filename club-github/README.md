# موقع لجنة التنظيم — نادي رواد الصناعة

## الرفع على GitHub Pages (٥ خطوات)
1. github.com ← New repository ← اسمه مثلًا `club` ← Public ← Create.
2. Add file ← Upload files ← اسحب الملفات الثلاثة (index.html و shim.js و config.js) ← Commit.
3. Settings ← Pages ← Source: Deploy from a branch ← Branch: main ← / (root) ← Save.
4. بعد دقيقة يطلع الرابط: `https://اسمك.github.io/club/`

## مهم
- GitHub Pages لا يشغّل سيرفر. بدون سيرفر يعمل الموقع بـ**وضع تجريبي**: البيانات تُحفظ في متصفح كل شخص فقط ولا تتشارك بين الأعضاء.
- للتشارك الحقيقي: شغّل `server.js` (من club-site.zip) على استضافة مثل Render، ثم ضع رابطه في `config.js`:
  `window.API_BASE='https://رابط-السيرفر';`
- أكواد الإدارة نفسها تعمل في الوضعين.
