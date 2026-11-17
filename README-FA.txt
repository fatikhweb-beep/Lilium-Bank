Lilium Bank — نسخه قابل انتشار در GitHub Pages

محتویات این بسته:
- index.html: خود برنامه
- manifest.webmanifest: تنظیمات نصب به‌عنوان برنامه
- sw.js: سرویس‌ورکر برای کش و اجرای آفلاین
- icon-192.png و icon-512.png: آیکون برنامه
- .nojekyll: جلوگیری از پردازش ناخواسته GitHub Pages

روش انتشار صحیح:
۱) فایل ZIP را دانلود و از حالت فشرده خارج کنید.
۲) وارد مخزن https://github.com/fatikhweb-beep/blossom شوید.
۳) فایل‌های داخل پوشه lilium_bank_final را مستقیماً در ریشه مخزن بارگذاری کنید؛ خود فایل ZIP را به‌تنهایی در مخزن قرار ندهید.
۴) فایل‌های هم‌نام قبلی را جایگزین و Commit changes کنید.
۵) در Settings > Pages مطمئن شوید انتشار از شاخه main و پوشه /(root) انجام می‌شود.
۶) پس از انتشار، نشانی https://fatikhweb-beep.github.io/blossom/ را با Chrome باز کنید.
۷) اگر نسخه قدیمی باز شد، داده‌های سایت را پاک نکنید؛ ابتدا صفحه را Refresh کنید و در صورت نیاز از منوی Chrome گزینه نصب برنامه را بزنید.

نکته: نصب PWA فقط از نشانی HTTPS (مانند GitHub Pages) یا localhost پشتیبانی می‌شود؛ باز کردن مستقیم فایل index.html از داخل فایل‌منیجر، نصب PWA را فعال نمی‌کند.
