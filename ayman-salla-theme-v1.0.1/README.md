# 🎨 Ayman Salla Theme - قالب سلة متقدم

قالب Shopify احترافي بتصميم عربي حديث مع دعم الوضع الليلي والنهاري التلقائي، تأثيرات زجاجية متقدمة، وتجربة مستخدم متميزة.

## ✨ المميزات الرئيسية

### 🌙 الوضع الليلي والنهاري التلقائي
- تبديل تلقائي حسب إعدادات نظام المستخدم
- ألوان متوازنة ومريحة للعين في كلا الوضعين
- انتقالات سلسة بين الأوضاع

### 🪟 تأثير الزجاج (Glassmorphism)
- هيدر شفاف مع تأثير ضبابي متقدم
- عناصر UI عائمة بتصميم زجاجي
- تأثيرات بصرية عصرية وجذابة

### 🚀 حركات وتفاعلات متقدمة
- أزرار بتدرجات لونية وتأثيرات لمعان
- بطاقات منتجات تفاعلية مع حركات ثلاثية الأبعاد
- حركات ظهور متدرجة للعناصر
- تأثيرات التمرير والنقر

### 📱 تصميم متجاوب بالكامل
- يعمل بسلاسة على جميع الأجهزة
- تخطيط مرن يتكيف مع أحجام الشاشات
- تحسينات خاصة للهواتف المحمولة

### 🎯 محسن للأداء
- تحميل سريع للصفحات
- تحميل تدريجي للصور
- أكواد CSS و JavaScript محسنة

### 🔧 التحسينات الأخيرة (2025)
- **إصلاح مشاكل الأزرار البصرية** - إزالة تأثير اللمعان المزعج
- **تحسين سرعة التفاعل** - انتقالات أسرع وأكثر سلاسة
- **تحسين تفاعل اللمس** - دعم محسن للأجهزة اللمسية
- **تقليل التأثيرات المزعجة** - توازن مثالي بين الجمال والوظيفة
- **تحسين إمكانية الوصول** - دعم أفضل لقارئات الشاشة

## 📁 هيكل الملفات

```
ayman_salla_1/
├── assets/
│   └── theme.css                 # الأنماط الرئيسية
├── config/
│   └── settings_schema.json      # إعدادات القالب
├── layout/
│   └── theme.liquid              # التخطيط الأساسي
├── sections/
│   ├── header.liquid             # رأس الصفحة
│   └── footer.liquid             # ذيل الصفحة
├── snippets/
│   └── product-card.liquid       # بطاقة المنتج
├── templates/
│   └── index.liquid              # الصفحة الرئيسية
└── README.md                     # هذا الملف
```

## 🧪 اختبار القالب

### طريقة سريعة للاختبار
1. افتح الملف `preview-test.html` في المتصفح لاختبار الأزرار والتفاعلات
2. اختبر الوضع المظلم والفاتح باستخدام الزر الموجود في الصفحة
3. تأكد من عدم ظهور أي تأثيرات مزعجة عند المرور على الأزرار

### اختبار شامل
- **اختبار الأزرار**: تأكد من عدم ظهور تأثير لمعان مزعج
- **اختبار بطاقات المنتجات**: تحقق من سلاسة الحركات
- **اختبار الوضع المظلم**: تأكد من تبديل الألوان بشكل صحيح
- **اختبار الاستجابة**: جرب القالب على أحجام شاشة مختلفة

## 🛠️ التثبيت والاستخدام

### 1. تحميل القالب
```bash
# استنساخ المستودع
git clone [repository-url]

# أو تحميل الملفات مباشرة
```

### 2. رفع القالب لـ Shopify
1. اذهب إلى لوحة تحكم Shopify
2. انتقل إلى **Online Store > Themes**
3. اختر **Upload theme**
4. ارفع ملف ZIP للقالب

### 3. تخصيص القالب
انتقل إلى **Customize** لتعديل:
- الألوان والخطوط
- الشعار والهوية البصرية
- محتوى الصفحة الرئيسية
- إعدادات الهيدر والفوتر
- معلومات التواصل

## 🎨 تخصيص الألوان

يمكنك تغيير الألوان من إعدادات القالب أو تعديل متغيرات CSS مباشرة:

```css
:root {
  --color-primary: #5a67d8;      /* اللون الأساسي */
  --color-secondary: #ff7e3e;    /* اللون الثانوي */
  --color-text: #2d3748;         /* لون النص */
  --color-bg: #f7f8fc;           /* لون الخلفية */
  --color-surface: #ffffff;      /* لون الأسطح */
}
```

## 🔧 الميزات التقنية

### مكونات CSS المتقدمة
- **متغيرات CSS**: للتحكم السهل في الألوان والأبعاد
- **Grid Layout**: لتخطيطات مرنة ومتجاوبة
- **Flexbox**: لمحاذاة مثالية للعناصر
- **CSS Animations**: لحركات سلسة وجذابة
- **Backdrop Filter**: لتأثيرات الزجاج المتقدمة

### JavaScript التفاعلي
- إدارة سلة التسوق
- البحث التفاعلي
- المفضلة (Wishlist)
- الإشعارات التفاعلية
- تحسينات إمكانية الوصول

## 📧 الدعم والمساعدة

### إعداد المنتجات
1. أضف منتجاتك في لوحة تحكم Shopify
2. تأكد من إضافة صور عالية الجودة
3. املأ الأوصاف والأسعار
4. نظم المنتجات في مجموعات

### إعداد القوائم
1. اذهب إلى **Navigation**
2. أنشئ قائمة باسم `main-menu`
3. أضف الروابط المطلوبة
4. احفظ التغييرات

### إعداد الصفحات
أنشئ الصفحات التالية:
- About (عن المتجر)
- Contact (تواصل معنا)
- Shipping Policy (سياسة الشحن)
- Refund Policy (سياسة الاسترداد)
- Privacy Policy (سياسة الخصوصية)
- Terms of Service (شروط الخدمة)

## 📊 تحسين الأداء

### نصائح لسرعة أفضل
1. اضغط الصور قبل الرفع
2. استخدم تنسيق WebP للصور
3. فعل التحميل التدريجي
4. قلل من عدد تطبيقات Shopify

### SEO
- العناوين محسنة تلقائياً
- البيانات المنظمة مدمجة
- روابط Canonical موجودة
- متوافق مع محركات البحث

## 🌟 ميزات إضافية

### سلة التسوق المنبثقة
- عرض المنتجات بشكل أنيق
- إمكانية تعديل الكميات
- حساب المجموع تلقائياً
- ربط مباشر بصفحة الدفع

### نظام المفضلة
- حفظ المنتجات المفضلة
- تخزين محلي في المتصفح
- إشعارات تفاعلية

### النشرة البريدية
- نموذج اشتراك مدمج
- إرسال تلقائي لـ Shopify
- تأكيد الاشتراك

## 📱 التوافق

### المتصفحات المدعومة
- ✅ Chrome (الإصدارات الحديثة)
- ✅ Firefox (الإصدارات الحديثة)
- ✅ Safari (الإصدارات الحديثة)
- ✅ Edge (الإصدارات الحديثة)
- ⚠️ Internet Explorer (دعم محدود)

### الأجهزة
- 📱 الهواتف الذكية
- 📱 الأجهزة اللوحية
- 💻 أجهزة الكمبيوتر المحمولة
- 🖥️ أجهزة سطح المكتب

## 🔄 التحديثات

### الإصدار 1.0.1 (يناير 2025) - تحديث الإصلاحات
- 🔧 **إصلاح مشاكل الأزرار البصرية**: تم حل مشكلة ظهور عنصر غير مرغوب فيه عند المرور على زر "عرض جميع المنتجات"
- ⚡ **تحسين الأداء**: تسريع تفاعلات الأزرار والعناصر التفاعلية
- 🎨 **تحسين التأثيرات البصرية**: توازن أفضل بين الجمال والوظيفة
- 📱 **تحسين دعم الأجهزة اللمسية**: منع التأثيرات غير المرغوبة على الهواتف
- 🧪 **إضافة ملف اختبار**: `preview-test.html` لاختبار القالب قبل الاستخدام

### الإصدار 1.0.0 (يناير 2025)
- إطلاق القالب الأولي
- تأثير الزجاج للهيدر
- الوضع الليلي والنهاري
- بطاقات منتجات تفاعلية
- سلة تسوق منبثقة

## 📄 الترخيص

هذا القالب محفوظ الحقوق © 2025. جميع الحقوق محفوظة.

---

**تم تطويره بواسطة:** Ayman1.sa  
**تاريخ الإنشاء:** يناير 2025  
**الإصدار:** 1.0.0
