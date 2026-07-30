<div dir="rtl">

# آزمون جمع‌بندی نهایی شیمی دوازدهم

یک برنامهٔ تک‌فایلی و موبایل‌محور برای مرور شب امتحان نهایی شیمی پایهٔ دوازدهم.
۱۷ سؤال منتخب با پاسخ تشریحی، شکل‌های برداری و جدول‌های داده — بدون ثبت‌نام، بدون تنظیمات، بدون نیاز به اینترنت.

## اجرا

فایل `index.html` را در مرورگر گوشی باز کنید. تمام است.
هیچ نصب، وابستگی یا سروری لازم نیست.

برای انتشار روی **GitHub Pages**: مخزن را بسازید، این فایل‌ها را آپلود کنید، سپس از مسیر
`Settings → Pages → Branch: main → /(root)` انتشار را فعال کنید.
فایل `index.html` به‌صورت خودکار صفحهٔ اصلی می‌شود.

## مسیر دانش‌آموز

```
معرفی سازندگان (فقط بار اول)
        ↓
      خانه
        ↓
   شروع آزمون
        ↓
مرحله ۱ · مرور سریع        سؤال ۱ تا ۷
مرحله ۲ · سؤال‌های اصلی     سؤال ۸ تا ۱۷
        ↓
  مرور نقطه‌های ضعیف
        ↓
   آمادگی نهایی
```

هر سؤال یک الگوی ثابت دارد: صورت سؤال ← تلاش خود دانش‌آموز ← نمایش پاسخ تشریحی ← خودسنجی سه‌حالته (بلد بودم / با شک حل کردم / بلد نبودم) ← سؤال بعدی.
در پایان، فقط سؤال‌هایی که با شک یا ناتوانی علامت خورده‌اند دوباره مرور می‌شوند.

## ویژگی‌ها

- تک‌فایل کامل؛ فونت و تصاویر داخل خود فایل جاسازی شده‌اند
- کار بدون اینترنت
- راست‌به‌چپ کامل، با فرمول‌های شیمیایی در جهت درست چپ‌به‌راست
- آزموده‌شده روی عرض‌های ۳۲۰، ۳۶۰، ۳۹۰ و ۴۳۰ پیکسل
- حفظ وضعیت در حافظهٔ محلی مرورگر؛ رفرش تصادفی جلسه را از بین نمی‌برد
- پشتیبانی از `prefers-reduced-motion`، وضعیت فوکوس و دکمه‌های معنایی
- بدون ردیابی، بدون ارسال داده به سرور، بدون حساب کاربری

## ساختار مخزن

```
index.html    برنامه (کامل و مستقل)
LICENSE.md    متن پروانه
NOTICE        اطلاعیهٔ الزامی پروانه
.nojekyll     غیرفعال‌کردن پردازش Jekyll در GitHub Pages
.gitignore
```

## سازندگان

- برنامه‌نویس پروژه — [@forkcode](https://t.me/forkcode)
- همکاری آموزشی — [@rebwar_edu](https://t.me/rebwar_edu)
- ارتباط مستقیم — [@Oxmit](https://t.me/Oxmit)

## پروانه

این پروژه تحت **PolyForm Noncommercial License 1.0.0** منتشر شده است.

استفادهٔ شخصی، آموزشی و غیرتجاری آزاد است — از جمله استفاده توسط مدارس، آموزشگاه‌های غیرانتفاعی و نهادهای عمومی.
فروش این برنامه، قراردادن آن در محصول پولی یا استفادهٔ تجاری از آن مجاز نیست.

متن کامل: [LICENSE.md](LICENSE.md)

</div>

---

## English summary

A single-file, mobile-first review app for the Iranian Grade 12 Chemistry final exam:
17 selected questions with worked answers, vector figures and data tables.
No signup, no configuration, no network required — just open `index.html`.

The flow is fixed: quick warm-up questions, then the full descriptive questions,
then a short review of only the topics the student marked as shaky or unknown,
and finally a readiness summary with the three topics worth one last look.

Licensed under the **PolyForm Noncommercial License 1.0.0**.
Noncommercial and educational use is permitted; selling it or bundling it into a
paid product is not. See [LICENSE.md](LICENSE.md).
