# حزمة البناء التلقائي لنظام السويدي للجودة (Windows `.exe` + Android `.apk` + iOS PWA)

هذه الحزمة تحتوي على نظام **`El_Sewedy_Factory_QC_System`** مربوطاً لحظياً بمشروع **Supabase (`el-sewedy-qc`)** ومهيأ للبناء السحابي المجاني عبر **GitHub Actions**.

## خطوات الحصول على ملفات التثبيت (`.exe` و `.apk`) خلال 3 دقائق:
1. فك ضغط الملف المضغوط.
2. افتح حسابك على [GitHub](https://github.com/new) وأنشئ مستودعاً جديداً (مثلاً باسم `el-sewedy-qc-app`).
3. ارفع جميع الملفات والمجلدات الموجودة هنا (بما في ذلك مجلد `.github` المخفي وملف `package.json` ومجلد `www`).
4. افتح تبويب **Actions** داخل المستودع على GitHub؛ ستجد عملية **Build El Sewedy QC (Windows EXE & Android APK)** تعمل تلقائياً (أو اضغط **Run workflow**).
5. بعد 3–4 دقائق، انزل لأسفل صفحة الـ Workflow تحت قسم **Artifacts** وحمّل:
   - **`El_Sewedy_QC_Windows_EXE`**: ملف تثبيت ويندوز مستقل (`.exe`) بأيقونة السويدي.
   - **`El_Sewedy_QC_Android_APK`**: ملف تثبيت أندرويد (`.apk`) جاهز للنقل والتثبيت المباشر على أي هاتف أندرويد.

## تثبيت نسخة الآيفون (iOS):
- فعّل **GitHub Pages** من إعدادات المستودع (أو ارفع مجلد `www` على [Netlify Drop](https://app.netlify.com/drop))، ثم افتح الرابط من متصفح **Safari** على الآيفون واضغط **Share ← Add to Home Screen** ليعمل كتطبيق iOS مستقل بأيقونة السويدي ومزامنة سحابية لحظية.
