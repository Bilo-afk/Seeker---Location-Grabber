# 📍 Seeker - GPS Tracker

## 📌 What is Seeker?

**Seeker** is a tool that uses social engineering techniques to obtain the GPS location of a target. It creates a fake webpage that mimics a legitimate service and asks for location access. Once the victim grants permission, their coordinates are sent back to you.

⚠️ **Warning:** This tool is for educational purposes only. Unauthorized use may be illegal and punishable by law.

---

## 🛠️ Requirements

- Python 3
- PHP
- ngrok or serveo
- Git

---

## 🔧 Installation

```bash
git clone https://github.com/thewhiteh4t/seeker.git
cd seeker
pip3 install -r requirements.txt
```

---

## 🌐 How to Run ngrok on Kali Linux

1. Download ngrok from the official website:
```bash
wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip
```

2. Unzip the archive:
```bash
unzip ngrok-stable-linux-amd64.zip
```

3. Make it executable:
```bash
chmod +x ngrok
```

4. Authenticate ngrok with your account token:
```bash
./ngrok authtoken <your_token_here>
```

5. Run ngrok on port 8080:
```bash
./ngrok http 8080
```

You will get a public URL to share.

---

## 🚀 Usage

```bash
python3 seeker.py
```

After launching the tool, you can choose a webpage template. When the victim opens the ngrok or serveo link and allows location access, Seeker will capture their GPS coordinates.

---

## 📍 Sample Output

```
Location: Latitude: 37.4219983 | Longitude: -122.084
Accuracy: 20 meters
Browser: Chrome on Android
IP Address: 192.168.1.5
```

---

## ⚖️ Legal Disclaimer

> This tool is for ethical hacking and educational purposes only. The developer is not responsible for any misuse or damage caused by this tool.

---



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# 📍 Seeker - أداة تحديد الموقع الجغرافي باستخدام الهندسة الاجتماعية

## 📌 ما هي أداة Seeker؟

**Seeker** هي أداة تستخدم تقنيات الهندسة الاجتماعية للحصول على الموقع الجغرافي (GPS) للضحية من خلال إرسال رابط مزيف يشبه مواقع مشهورة. بمجرد دخول الضحية للرابط والموافقة على مشاركة الموقع، يتم إرسال الإحداثيات مباشرة إليك.

⚠️ **تنبيه:** هذه الأداة لأغراض تعليمية فقط. أي استخدام غير قانوني يعرضك للمساءلة القانونية.

---

## 🛠️ المتطلبات

- Python 3
- PHP
- ngrok أو serveo
- Git

---

## 🔧 خطوات التثبيت

```bash
git clone https://github.com/thewhiteh4t/seeker.git
cd seeker
pip3 install -r requirements.txt
```

---

## 🌐 تشغيل ngrok في Kali Linux

1. قم بتحميل ngrok من الموقع الرسمي:
```bash
wget https://bin.equinox.io/c/4VmDzA7iaHb/ngrok-stable-linux-amd64.zip
```

2. فك الضغط:
```bash
unzip ngrok-stable-linux-amd64.zip
```

3. اجعل ngrok ملفًا قابلًا للتنفيذ:
```bash
chmod +x ngrok
```

4. سجّل الدخول باستخدام توكن حسابك:
```bash
./ngrok authtoken <ضع_التوكن_هنا>
```

5. شغّل ngrok على المنفذ 8080 مثلًا:
```bash
./ngrok http 8080
```

سيتم توليد رابط خارجي يمكنك استخدامه.

---

## 🚀 طريقة الاستخدام

```bash
python3 seeker.py
```

بعد تشغيل الأداة، ستظهر لك قائمة لاختيار الصفحة التي سيتم إرسالها للضحية. عند الدخول إلى الرابط، سيُطلب من الضحية السماح بالوصول إلى الموقع.

---

## 📍 النتيجة المتوقعة

```
الموقع: خط العرض: 37.4219983 | خط الطول: -122.084
الدقة: 20 متر
المتصفح: Chrome على Android
عنوان IP: 192.168.1.5
```

---

## ⚖️ التحذير القانوني

> هذه الأداة مخصصة لأغراض التعليم والاختبار الأخلاقي فقط. المطور لا يتحمل أي مسؤولية عن أي استخدام غير قانوني.

---

## 👨‍💻 المطور

- تم التعديل بواسطة: Belal Alhamid
- المطور الأصلي: [@thewhiteh4t](https://github.com/thewhiteh4t)
