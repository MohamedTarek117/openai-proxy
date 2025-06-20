# OpenAI Proxy Server

خادم وسيط لاستدعاء OpenAI API من الواجهة الأمامية بأمان (Node.js + Express).

## كيف تستخدم؟

1. ضع مفتاح OpenAI في متغير البيئة OPENAI_KEY (تم تضمينه هنا تلقائيًا).
2. شغّل السيرفر:
   ```
   npm install
   node server.js
   ```
3. أرسل طلب POST إلى:
   ```
   /api/ai
   ```
   مع body مثل:
   ```
   { "prompt": "اكتب لي تحليل لسوق الذهب اليوم" }
   ```