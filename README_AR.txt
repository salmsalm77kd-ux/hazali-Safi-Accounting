مشروع Ghazali Safi Accounting - Android / Google Play

1) افتح المجلد في Android Studio.
2) انتظر Gradle Sync.
3) للاختبار: Build > Build APK(s).
4) للنشر: Build > Generate Signed Bundle / APK > Android App Bundle.
5) أنشئ مفتاح توقيع Keystore واحفظه في مكان آمن جداً. ستحتاجه لتحديث التطبيق مستقبلاً.
6) applicationId: com.ghazali.safiaccounting
7) targetSdk / compileSdk: API 36 (Android 16).
8) ملف البرنامج الأصلي موجود داخل app/src/main/assets/index.html.
9) التخزين المحلي في Android WebView هو IndexedDB. وظائف SQLite الموجودة في HTML تخص نسخة Windows ولن تعمل على Android إلا بجسر Android مخصص.
10) المزامنة السحابية تحتاج الإنترنت.

ملاحظة: قبل الرفع النهائي يجب اختبار الاستيراد والتصدير والطباعة والمزامنة على هاتف حقيقي، ثم تجهيز سياسة الخصوصية وبيانات صفحة Google Play.
