
# 📍 Seekir Location Tracking Tool - Usage Guide | دليل استخدام أداة تحديد الموقع Seekir

---

## 🇬🇧 English Version

### ✅ Step-by-Step Setup

#### 1. Open First Terminal - Start ngrok
This opens a public tunnel to your local server:
```bash
ngrok http 8080
```
If this is your first time using ngrok, authenticate with:
```bash
ngrok authtoken <YOUR_TOKEN>
```
After that, ngrok will give you a link like:
```
https://12abc345.ngrok.io
```
Copy this link — you'll send it to the target later.

---

#### 2. Open Second Terminal - Run Seekir
Navigate to the tool’s folder:
```bash
cd Seekir
```
Then run the tool:
```bash
python3 seekir.py
```
If that fails, try:
```bash
python seekir.py
```

---

#### 3. Choose Tracking Mode
Once the script starts, you'll see a menu:
```
[1] Live Tracking
[2] URL-based Tracking
[3] IP Lookup
[4] Exit
```
Select option `2` for URL-based tracking.

---

#### 4. Send the Tracking Link
Seekir will create a fake webpage hosted on `localhost:8080`.

Use the link given by **ngrok** (from step 1), e.g.:
```
https://12abc345.ngrok.io
```
Send this link to the target user.

---

#### 5. Receive and View Data
Once the target opens the link, Seekir will collect:
- IP Address
- GPS Location (if permission is granted)
- Browser & OS Info
- Timestamp

Data is typically saved to a file like:
```
results.txt
```

---

### 🔁 Future Use
Each time you want to reuse the tool:
1. Open a terminal:
```bash
ngrok http 8080
```
2. Open a second terminal:
```bash
cd Seekir
python3 seekir.py
```

---

### ⚠️ Notes
- Make sure port 8080 is free. If using Apache:
```bash
sudo service apache2 stop
```
- If ngrok doesn't give a link, check your internet or ngrok account.

---

## 🇸🇦 النسخة العربية

### ✅ خطوات التشغيل بالتفصيل

#### 1. افتح التيرمنال الأول - شغّل ngrok
افتح نفق عام للسيرفر المحلي:
```bash
ngrok http 8080
```
إذا أول مرة تستخدم ngrok، فعّل حسابك:
```bash
ngrok authtoken <YOUR_TOKEN>
```
بعدها بيعطيك رابط مثل:
```
https://12abc345.ngrok.io
```
انسخ الرابط — رح تبعته للهدف لاحقًا.

---

#### 2. افتح التيرمنال الثاني - شغّل أداة Seekir
ادخل مجلد الأداة:
```bash
cd Seekir
```
ثم شغّل الأداة:
```bash
python3 seekir.py
```
أو إذا ما اشتغلت:
```bash
python seekir.py
```

---

#### 3. اختر وضع التتبع
بتطلع لك قائمة:
```
[1] Live Tracking
[2] URL-based Tracking
[3] IP Lookup
[4] Exit
```
اختر `2` لتتبع شخص عن طريق رابط.

---

#### 4. أرسل الرابط للهدف
الأداة رح تنشئ صفحة وهمية على `localhost:8080`

استعمل الرابط اللي عطاك ياه ngrok (من الخطوة الأولى)، مثل:
```
https://12abc345.ngrok.io
```
وارسله للهدف.

---

#### 5. استقبال البيانات
لما الهدف يفتح الرابط، الأداة رح تسجل:
- عنوان الـ IP
- الموقع الجغرافي (GPS)
- نوع الجهاز والمتصفح
- الوقت

وبيتخزن غالبًا بملف اسمه:
```
results.txt
```

---

### 🔁 لإعادة الاستخدام لاحقًا:
1. افتح تيرمنال:
```bash
ngrok http 8080
```
2. افتح تيرمنال ثاني:
```bash
cd Seekir
python3 seekir.py
```

---

### ⚠️ ملاحظات:
- تأكد إن البورت 8080 مشغول. إذا فيه Apache شغال:
```bash
sudo service apache2 stop
```
- لو ngrok ما عطاك رابط، شيك الاتصال أو الحساب.

---

> 🛡️ أداة Seekir ممتازة لجمع معلومات الموقع عبر الروابط، لكن استخدمها لأغراض تعليمية وقانونية فقط.
