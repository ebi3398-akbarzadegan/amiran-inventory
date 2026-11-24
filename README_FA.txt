پروژه اندرویدی «انبار قطعات امیران»

این پوشه یک پروژه Android Studio است که نسخه آفلاین انبار را درون برنامه اندرویدی (WebView) اجرا می‌کند.

ساخت APK:
1) Android Studio را روی رایانه نصب کنید.
2) پوشه AmiranAndroid را با گزینه Open باز کنید.
3) اجازه دهید Gradle Sync و دریافت Android SDK انجام شود.
4) از منوی Build گزینه Build Bundle(s) / APK(s) و سپس Build APK(s) را انتخاب کنید.
5) فایل APK در مسیر app/build/outputs/apk/debug/app-debug.apk ساخته می‌شود.

نیازمندی‌ها: Android SDK Platform 35 و Android Gradle Plugin 8.7.3 (Gradle سازگار 8.9)، JDK 17 یا بالاتر.

توجه مهم: داده‌ها در فضای محلی WebView همین نصب ذخیره می‌شوند. قبل از حذف برنامه یا پاک‌کردن داده‌های آن، از داخل برنامه فایل پشتیبان JSON بگیرید. انتقال داده به گوشی دیگر با بازیابی همان فایل پشتیبان انجام می‌شود.

ساخت خودکار APK با GitHub (بدون نصب Android Studio):
1) در github.com حساب بسازید و وارد شوید.
2) یک مخزن جدید با نام AmiranAndroid ایجاد کنید.
3) محتویات پوشه AmiranAndroid را استخراج و در مخزن بارگذاری و Commit کنید.
4) زبانه Actions را باز کنید؛ با push روی main، ساخت خودکار اجرا می‌شود. در صورت نیاز Build Amiran APK را دستی اجرا کنید.
5) پس از پایان موفق، وارد اجرای workflow شوید و از بخش Artifacts فایل Amiran-Inventory-APK را دانلود کنید.
6) فایل ZIP خروجی را باز کنید؛ app-debug.apk داخل آن است. آن را به گوشی منتقل و نصب کنید.
