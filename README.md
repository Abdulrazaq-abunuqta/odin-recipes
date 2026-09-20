# Odin Recipes

A simple recipes website created as part of [The Odin Project's Foundations Course](https://www.theodinproject.com/). This project serves as a hands-on introduction to fundamental web development principles, building a multi-page site using pure HTML.

---

## About the Project

The goal of this project is to build a clean, multi-page recipes site using semantically structured HTML. The site consists of a main landing page that links to individual recipe pages containing ingredient lists, step-by-step instructions, and visual assets.

### Key Features

- **Main Index Page:** Serves as the navigation hub containing links to all available recipes.
- **Dedicated Recipe Pages:** Detailed pages featuring structured recipe details, preparation steps, and images.
- **Semantic Structure:** Proper use of HTML elements to ensure accessibility, scannability, and clean document flow.

---

## Skills Demonstrated

Upon completion of this project, the following core skills and concepts are applied and demonstrated:

1. **Git & GitHub Workflow:**
   - Initializing a local repository and tracking project history through atomic commits.
   - Managing remote repositories on GitHub and pushing regular updates.
2. **HTML Core Fundamentals:**
   - Structuring document boilerplate (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
   - Utilizing semantic tags (`<h1>`–`<h6>`, `<p>`, `<ul>`, `<ol>`, `<li>`, `<a>`, `<img>`).
3. **File System Navigation & Linking:**
   - Organizing project directories (separating assets, stylesheets, and HTML pages).
   - Linking documents using relative file paths (`./`, `../`).
4. **Content Organization:**
   - Formatting content clearly using ordered lists for sequential cooking steps and unordered lists for ingredients.
   - Optimizing image inclusion using proper `src` paths and informative `alt` attributes.

---

## How to Run Locally

1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/](https://github.com/)Abdulrazaq-abunuqta/odin-recipes.git
   ```
   أهم أوامر **Git** و **GitHub** المستعملة يومياً في إدارة المشاريع وتتبع النسخ:

**إعداد البيانات والمستودع المحلي**

- `git config --global user.name "Your Name"`
  ضبط اسم المستخدم الذي يظهر في جميع التحديثات (Commits).
- `git config --global user.email "your_email@example.com"`
  ضبط البريد الإلكتروني المرتبط بحسابك على GitHub.
- `git init`
  إنشاء مستودع Git جديد فارغ داخل المجلد الحالي.
- `git clone <URL>`
  نسخ (تنزيل) مشروع موجود على GitHub بكامل تفاصيله وسجل تعذيلاته إلى حاسوبك.

---

**متابعة وتسجيل التغييرات**

- `git status`
  عرض حالة الملفات الحالية (الملفات المعتدلة، غير المضافة، أو الجاهزة للتأكيد).
- `git add <file_name>`
  إضافة ملف معين إلى مرحلة التجهيز (Staging Area).
- `git add .`
  إضافة جميع الملفات المعتدلة والجديدة في المجلد الحالي إلى مرحلة التجهيز دفعة واحدة.
- `git commit -m "Commit message"`
  تأكيد وحفظ التغييرات المجهزة في السجل المحلي مع كتابة رسالة توضيحية.
- `git log`
  عرض سجل جميع التعديلات والتأكيدات (Commits) السابقة مع تفاريخها ورسائلها.

---

**الربط والتعامل مع GitHub (Remote)**

- `git remote add origin <URL>`
  ربط المستودع المحلي بمستودع بعيد على GitHub وإعطائه الاسم الافتراضي `origin`.
- `git push -u origin <branch_name>`
  رفع التعديلات المحلية إلى GitHub مع حفظ اسم الفرع للرفعات القادمة.
- `git push`
  رفع التعديلات الأخيرة إلى الفرع المرتبط على GitHub بعد ضبطه سابقاً.
- `git pull`
  سحب ودمج التحديثات الأخيرة من GitHub إلى مشروك المحلي دمجاً مباشراً.
- `git fetch`
  جلب التحديثات والأفرع الجديدة من GitHub للاطلاع عليها فقط دون دمجها في كودك المحلي.

---

**إدارة الفروع (Branches)**

- `git branch`
  عرض جميع الفروع المحلية المتاحة (مع إشارة `*` على الفرع الحالي).
- `git branch <branch_name>`
  إنشاء فرع جديد مستقّل لتطوير ميزة معينة.
- `git checkout <branch_name>` أو `git switch <branch_name>`
  الانتقال والتبديل إلى فرع آخر.
- `git checkout -b <branch_name>`
  إنشاء فرع جديد والانتقال إليه مباشرة بطلب واحد.
- `git merge <branch_name>`
  دمج التغييرات من الفرع المحدد إلى الفرع الحالي الذي تقف عليه.
- `git branch -d <branch_name>`
  حذف الفرع المحلي المكتمل بعد الانتهاء منه.

---

**التراجع وإلغاء التغييرات**

- `git restore <file_name>`
  إلغاء التعديلات التي تمت على ملف معين وإعادته لآخرى حالة تم حفظها.
- `git restore --staged <file_name>`
  إخراج الملف من مرحلة التجهيز (Staging Area) دون إلغاء التعديلات المكتوبة في الكود.
- `git reset --hard <commit_hash>`
  التراجع الكامل والنهائي إلى نقطة حفظ (Commit) سابقة وحذف جميع التعديلات التالية لها.

## Thinx

<img align="center" height="150" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExeHhsbWhxc2VkcG12N2g4d3Vib3NjbWEwN2hoOTlsazJlbzMyNHlpbCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/LHZyixOnHwDDy/giphy.webp"  />
