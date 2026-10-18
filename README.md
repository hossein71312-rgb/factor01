# اپ اندروید فاکتور

## ساخت APK
1. Android Studio (نسخه‌ی جدید) را باز کنید → Open → همین پوشه (AsiaFactor) را انتخاب کنید.
2. صبر کنید Gradle Sync تمام شود (بار اول اینترنت لازم است).
3. برای تست: دکمه‌ی Run ▶ با گوشی یا شبیه‌ساز.
4. برای فایل APK: Build → Build Bundle(s) / APK(s) → Build APK(s)
   خروجی: app/build/outputs/apk/debug/app-debug.apk

## ساختار
- app/src/main/assets/index.html  ← همان فاکتور شما (فقط چند تغییر برای اندروید)
- app/src/main/java/.../MainActivity.kt ← پوسته‌ی اندروید (WebView + ذخیره/اشتراک/چاپ)
