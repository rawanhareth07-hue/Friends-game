# ألعاب الصديقات — دليل سريع

يحتوي index.html على 5 ألعاب: من الأكثر احتمالًا (30 سؤالًا)، اختاري بين اثنين (20)، صراحة باختيارات (20)، مين تعرف الثانية أكثر (15)، وخمني بالإيموجي (15).

## النشر
1. أنشئي مستودعًا على https://github.com/new باسم `friends-games` واجعليه Public.
2. ارفعي `index.html` إلى جذر المستودع.
3. Settings → Pages → Deploy from a branch → `main` و`/(root)` → Save.
4. افتحي رابط GitHub Pages الناتج.

## الاتصال
في صفحة اللعبة، أدخلي Project URL ومفتاح publishable/anon من إعدادات API في Supabase، ثم اسمك ورمز غرفة. الصديقات يستخدمن رابط الموقع ورمز الغرفة نفسيهما.

لا تضعي مفتاح `secret` أو `service_role` في الموقع. تستخدم النسخة Realtime Broadcast/Presence؛ وقد تحتاج إعدادات Supabase إلى السماح بـ Realtime. رمز الغرفة ليس وسيلة حماية للمعلومات الخاصة.
