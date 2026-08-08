# ServerAndClient
# 🌐 Client-Server Learning Repository

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active%20Learning-blue.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-orange.svg)

مرحباً بكم في المستودع التعليمي المخصص لتطبيق مفاهيم **عميل-خادم (Client-Server Architecture)** وتطوير مهارات العمل الجماعي باستخدام **Git & GitHub Flow**.

---

## 📌 أهداف المشروع (Project Objectives)

يهدف هذا المشروع إلى نقل الفريق من الأساسيات النظرية إلى التطبيق العملي من خلال نقطتين رئيسيتين:

1. **الجانب التقني (Technical Knowledge):**
   - فهم آلية الاتصال عبر بروتوكولات الشبكة (TCP / UDP).
   - بناء برمجيات المقابس (Socket Programming).
   - التعامل مع البرمجة متعددة الخيوط (Multi-threading / Async) لإدارة كائنات خادم تستقبل عدة عملاء في وقت واحد.
   - تشفير وتسلسل البيانات (Data Serialization & Protocols) المتبادلة بين العميل والخادم (JSON / Byte Streams).

2. **جانب إدارة المشاريع (GitHub Workflow):**
   - التدرب على إنشاء الفروع (Branching Strategy).
   - كتابة رسائل حفظ معيارية (Conventional Commits).
   - إنشاء ومراجعة طلبات السحب (Pull Requests & Code Reviews).
   - حل تعارضات الكود (Merge Conflicts) بشكل احترافي.

---

## 🏗️ هيكلية المستودع (Folder Structure)

تم تنظيم المستودع ليفصل بين كود الخادم، العميل، والوثائق التعليمية:

```text
client-and-server/
│
├── 📁 src/
│   ├── 📁 Server/            # كود مشروع الخادم (Server Project)
│   │   ├── Program.cs
│   │   └── Core/             # منطق إدارة الاتصالات والـ Sockets
│   │
│   └── 📁 Client/            # كود مشروع العميل (Client Project)
│       ├── Program.cs
│       └── Services/         # خدمات إرسال واستقبال البيانات
│
├── 📁 docs/                  # التوثيق والرسومات التوضيحية للمشروع
│   └── architecture-diagram.png
│
├── .gitignore                # استبعاد ملفات البناء المؤقتة (Visual Studio)
└── README.md                 # الوثيقة الرئيسية للمشروع

