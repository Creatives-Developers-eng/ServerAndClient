# 🌐 Client-Server Desktop Application (WinForms)

![C#](https://img.shields.io/badge/Language-C%23-purple.svg)
![NET](https://img.shields.io/badge/Framework-.NET%208.0--windows-blue.svg)
![UI](https://img.shields.io/badge/UI-Windows%20Forms-brightgreen.svg)
![IDE](https://img.shields.io/badge/IDE-Visual%20Studio-blueviolet.svg)

مرحباً بأعضاء الفريق! هذا المستودع مخصص لتطبيق مفاهيم **Client-Server Architecture** ببرمجة الواجهات الرسمية **Windows Forms**، مع تطبيق أفضل ممارسات إدارة المشاريع عبر **Git & GitHub Flow**.

---

## 📐 هيكلية المشروع (Project Structure)

تم تنظيم الكود داخل مجلد `src` ليحتوي على مشروعين مستقلين كـ Windows Forms:

```text
client-and-server/
│
├── 📁 src/
│   ├── 📁 Server/             # تطبيق الخادم (Windows Forms App)
│   │   ├── ServerForm.cs      # واجهة التحكم بالخادم (UI)
│   │   ├── ServerForm.Designer.cs
│   │   └── Server.csproj
│   │
│   ├── 📁 Client/             # تطبيق العميل (Windows Forms App)
│   │   ├── ClientForm.cs      # واجهة العميل وإرسال الرسائل (UI)
│   │   ├── ClientForm.Designer.cs
│   │   └── Client.csproj
│   │
│   └── 📄 ClientAndServer.sln # ملف الحل الرئيسي في Visual Studio
│
├── 📄 .gitignore              # استبعاد ملفات البناء المؤقتة لـ Visual Studio
└── 📄 README.md               # الدليل الشامل وقواعد العمل
