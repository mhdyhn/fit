# رخ فیت

اپلیکیشن آفلاین برنامه‌ی تمرینی فارسی برای اندروید.

- شناسه: `app.rokh.fitness`
- نسخه: `1.0.0`
- حداقل اندروید: Android 7 (API 24)
- بدون درخواست اینترنت
- داده‌ها و تصاویر داخل APK

## ساخت APK فقط با گوشی و GitHub

1. در GitHub یک Repository جدید بسازید؛ بهتر است نام آن `rokh-fit` باشد.
2. تمام فایل‌ها و پوشه‌های این بسته را در ریشه‌ی Repository آپلود کنید. پوشه‌ی `.github` نیز ضروری است.
3. به تب **Actions** بروید.
4. در صورت نمایش پیام، روی **I understand my workflows, go ahead and enable them** بزنید.
5. گردش‌کار **Build Rokh Fit APK** را باز کنید.
6. روی **Run workflow** و سپس دکمه‌ی سبز **Run workflow** بزنید.
7. پس از سبزشدن اجرای Build، همان اجرا را باز کنید.
8. پایین صفحه، از بخش **Artifacts** فایل **RokhFit-APK** را دانلود کنید.
9. ZIP دانلودشده را استخراج و `RokhFit-v1.0.apk` را نصب کنید.

## نصب روی گوشی

اگر اندروید اجازه نداد:

`Settings → Security/Privacy → Install unknown apps`

به Chrome یا Files اجازه بدهید، APK را نصب کنید و سپس این مجوز را دوباره خاموش کنید.

## نکته درباره‌ی نسخه‌های بعدی

APK این Workflow از نوع Debug و قابل نصب است. برای انتشار در Google Play باید نسخه‌ی Release با کلید امضای خصوصی ساخته شود.
