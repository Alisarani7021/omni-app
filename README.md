# OMNI — دانلود اپ

انتشار عمومی نسخه‌های اپ **OMNI** (وی‌پی‌ان اختصاصی OMNI).

## دانلود آخرین نسخه

- مستقیم: [OMNI.apk](https://github.com/Alisarani7021/omni-app/releases/latest/download/OMNI.apk)
- از طریق پنل (همیشه آخرین نسخه): https://omni-panel.t2zyibe5udus.workers.dev/apk
- نسخه سبک‌تر ۱٫۳ (بدون دیتابیس شهرها، ~۱۰ مگابایت): https://omni-panel.t2zyibe5udus.workers.dev/apk?lite=1

## درباره OMNI

OMNI یک وی‌پی‌ان تمام‌دستگاهی برای اندروید است که فقط با کانفیگ اختصاصی `omni://` کار می‌کند
(پروتکل OEP روی WebSocket از طریق Cloudflare Worker). نود خودت را با ربات تلگرام یا پنل
در چند ثانیه روی اکانت کلودفلر خودت بساز.

امکانات: اسکنر مسیر، چند نودی +.failover، تونل تقسیم‌شده (split tunnel)، سوئیچ قطع اضطراری،
کاشی تنظیمات سریع، ویجت، شروع خودکار بعد از ری‌بووت، تست نشتی با موقعیت شهر و ASN به‌صورت آفلاین.

## استناد داده‌ها (Attribution)

دیتابیس‌های آفلاین موقعیت جغرافیایی (کشور/شهر) و ASN از سرویس رایگان [db-ip.com](https://db-ip.com)
تهیه شده‌اند و تحت مجوز [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) منتشر می‌شوند.

## نسخه‌ها

| نسخه | تاریخ | تغییرات |
|------|-------|---------|
| 1.4  | 2026-10 | موقعیت شهر سطح آی‌پی (آفلاین)، فشرده‌سازی انتخابی تونل (deflate)، ... |
| 1.3  | 2026-10 | split tunnel، kill switch، tile/widget/boot، تست نشتی، GeoIP کشور + ASN آفلاین |
