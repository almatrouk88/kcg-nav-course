# موقع دورة الأجهزة الملاحية — خفر السواحل
https://almatrouk88.github.io/kcg-nav-course/

## إضافة عرض جديد (مثال: جهاز الأعماق)
1. `mkdir depth && cp <العرض>.html depth/index.html && cp -r <media> depth/media && cp <العرض>.pdf depth/depth-slides.pdf`
2. في `index.html`: بدّل بطاقة «قريباً» الخاصة به بنفس شكل بطاقة الرادار (زر «افتح العرض» → `depth/` وزر PDF → `depth/depth-slides.pdf`).
3. `git add -A && git commit -m "…" && git push`

## تحديث المذكرة أو قسم
انسخ الملف الجديد فوق القديم في `memo/` بنفس الاسم ثم commit/push — الرابط لا يتغير.

الملفات مولّدة من `~/Documents/دورة الأجهزة الملاحية/`.
