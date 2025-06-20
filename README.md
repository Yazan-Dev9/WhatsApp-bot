
# 🤖 بوت واتساب الذكاء الاصطناعي | WhatsApp AI Bot

---

## المقدمة | Introduction

**العربية:**  
بوت واتساب ذكي مبني على مكتبة [Baileys](https://github.com/WhiskeySockets/Baile
ys)، يتيح لك التفاعل مع الذكاء الاصطناعي والإجابة على الأسئلة عبر رسائل تبدأ بال
رمز #. يتم حذف أي أوامر من غير المالك تلقائيًا لحماية الخصوصية والتحكم.

**English:**  
A smart WhatsApp bot built with [Baileys](https://github.com/WhiskeySockets/Ba
ileys), enabling you to interact with AI and get instant answers by sending
 messages starting with #. For security and control, only the owner can use
 commands; all others' commands are automatically deleted.

---

## ⚙️ الميزات | Features

- 🔒 **دخول آمن عبر كود QR**  
  Secure login using QR code
- 🤖 **إجابات فورية من الذكاء الاصطناعي (Gemini / TGPT)**  
  Instant answers from AI (Gemini / TGPT)
- 🛡️ **حذف أوامر غير المالك تلقائيًا**  
  Auto-delete non-owner commands
- ✂️ **تقسيم الردود الطويلة تلقائيًا**  
  Automatic splitting of long replies
- 👥 **دعم المجموعات والدردشة الخاصة**  
  Supports both group and private chats
- 🌐 **إمكانية التوسعة والتخصيص بسهولة**  
  Easily extensible and customizable

---

## 📝 المتطلبات | Requirements

- [Node.js](https://nodejs.org/) v20 أو أحدث | or newer
- [tgpt4](https://github.com/aandrew-me/tgpt) (تأكد من تثبيته على جهازك) | Make
 sure it's installed
- Gemini API Key (مفتاح Gemini API صالح)
- [@whiskeysockets/baileys](https://github.com/WhiskeySockets/Baileys)
- [qrcode-terminal](https://www.npmjs.com/package/qrcode-terminal)

---

## 🚀 التثبيت والتشغيل | Installation & Usage

### 1. تثبيت الحزم | Install Dependencies

```bash
git clone https://github.com/Yazan-Dev9/whatsapp-bot.git
cd whatsapp-bot
npm install
```

### 2. إعداد tgpt4 & API Key | Setup tgpt4 & API Key

- ضع ملف tgpt4 التنفيذي في نفس مجلد الكود أو عدّل المسار في الكود.
- أدخل مفتاح Gemini API الخاص بك في مكانه المناسب داخل الكود.

### 3. تشغيل البوت | Run the Bot

```bash
node whbot.js
```

- امسح رمز QR الظاهر عبر تطبيق واتساب لديك.
- أرسل رسالة تبدأ بـ # (مثال: #ما هو الذكاء الاصطناعي؟ أو #What is
 artificial intelligence?).

---

## 👤 ضبط المالك | Owner Setup

- غيّر قيمة متغير OWNER_ID في الكود إلى رقمك بصيغة واتساب JID (مثال: 963
XXXXXXXXX@s.whatsapp.net).

---

## 🧩 مثال على الاستخدام | Usage Example

**العربية:**  
أرسل:  
```
#ما هي لغة جافاسكريبت؟
```
**English:**  
Send:  
```
#What is JavaScript?
```
**سيتم الرد عليك مباشرة من الذكاء الاصطناعي! | You will get an instant AI
-powered reply!**

---

## 💡 نصائح الأمان | Security Tips

- لا تشارك مفتاح Gemini API مع أي شخص.
- يمكنك تعديل الكود لإضافة صلاحيات أو توسيع الميزات حسب حاجتك.

---

## 📄 الرخصة | License

MIT (2025) *Yazan Khdaj* <yksy.dev@gmail.com>

---

## 📬 الدعم والتطوير | Support & Development

**العربية:**  
لأي استفسار أو اقتراح، افتح تذكرة (issue) أو تواصل معي عبر GitHub.

**English:**  
For questions or suggestions, open an issue or contact me via GitHub.

---

**ملاحظة:**  
تأكد من تحديث جميع الروابط، المسارات، ومفتاح API بما يتناسب مع مشروعك الفعلي.  
Please make sure to update all links, paths, and API keys as per your actual
 project.

---
