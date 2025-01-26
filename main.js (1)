// استدعاء مكتبة Express لتشغيل السيرفر
const express = require('express');
const app = express();

// إعداد المسار الرئيسي
app.get('/', (req, res) => {
  res.send('مرحبًا! السيرفر يعمل بنجاح');
});

// تحديد المنفذ لتشغيل السيرفر
const PORT = process.env.PORT || 3000;
app.listen(PORT, () => {
  console.log(`Server is running on port ${PORT}`);
});