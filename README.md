# إيجنت ذكاء المختبر — سلطان المالكي

## طريقة النشر على Vercel (مجاني — رابط دائم)

### الخطوة 1 — رفع الملفات على GitHub
1. افتح https://github.com وأنشئ حساب مجاني
2. اضغط "New repository"
3. سمّه: `lab-agent`
4. اضغط "Add file" → "Upload files"
5. ارفع ملفي: `index.html` و `vercel.json`
6. اضغط "Commit changes"

### الخطوة 2 — النشر على Vercel
1. افتح https://vercel.com وسجّل بحساب GitHub
2. اضغط "Add New Project"
3. اختر مستودع `lab-agent`
4. اضغط "Deploy" — سينتهي خلال 30 ثانية

### النتيجة
رابطك الدائم سيكون:
`https://lab-agent.vercel.app`

---

## تغيير رمز PIN
افتح ملف `index.html` وابحث عن هذا السطر:
```
const CORRECT_PIN = '1234';
```
غيّر `1234` إلى الرمز الذي تريده (4 أرقام)

---

## إضافة Claude API
بعد الدخول بالـ PIN، أدخل مفتاح API في الحقل أسفل الشاشة.
احصل على مفتاحك من: https://console.anthropic.com

---

## المعلومات
- المالك: سلطان المالكي
- النوع: إيجنت ذكاء مختبر جودة المياه
- اللغة: عربي RTL
- النشر: Vercel (مجاني — لا يوقف)
