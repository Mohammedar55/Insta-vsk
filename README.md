# 📱 Insta-vsk

تطبيق رائع تم بناؤه بحب وعناية! ❤️

## 🎯 المميزات

- ✅ بناء تلقائي مع GitHub Actions
- ✅ دعم Android API 24 وما فوق
- ✅ واجهة مستخدم حديثة ونظيفة
- ✅ توافق كامل مع Kotlin
- ✅ معايير Gradle الحديثة
- ✅ مكتبات قوية (Retrofit, Glide, Gson)

## 📋 المتطلبات

- ☕ Java 17 أو أحدث
- 🤖 Android SDK 34
- 📦 Gradle 8.1.0

## 🚀 كيفية البدء

### بناء المشروع محلياً

```bash
# استخراج المشروع
git clone https://github.com/Mohammedar55/Insta-vsk.git
cd Insta-vsk

# بناء Debug APK
./gradlew assembleDebug

# بناء Release APK
./gradlew assembleRelease
```

### تثبيت على جهاز

```bash
# تثبيت Debug APK على المحاكي أو الجهاز
adb install app/build/outputs/apk/debug/app-debug.apk
```

## 📤 نشر Release على GitHub

### الطريقة 1: استخدام Tags (مع البناء التلقائي)

```bash
# إنشاء tag جديد
git tag -a v1.0.0 -m "الإصدار 1.0.0"

# رفع الـ tag
git push origin v1.0.0

# GitHub Actions سيبني التطبيق تلقائياً وينشئ Release
```

### الطريقة 2: النشر اليدوي

1. اذهب إلى صفحة [Releases](../../releases)
2. اضغط "Create a new release"
3. أكتب الإصدار (مثل `v1.0.0`)
4. أرفع ملفات APK
5. اضغط "Publish"

## 🔄 GitHub Actions

المشروع يحتوي على workflow تلقائي يقوم بـ:

- 🔨 بناء Debug و Release APK
- 📤 رفع APK كـ Artifacts
- 🚀 إنشاء Release تلقائي عند وضع Tag
- 📊 إنشاء ملخص البناء

## 📁 هيكل المشروع

```
Insta-vsk/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/instavsk/
│   │   │   │   └── MainActivity.kt
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── values/
│   │   │   │   └── ...
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
├── .github/
│   └── workflows/
│       └── build.yml
├── build.gradle
├── settings.gradle
├── gradle.properties
├── local.properties
└── README.md
```

## 🛠️ التكوينات الرئيسية

### build.gradle (الرئيسي)
- إعدادات Gradle العامة
- تبعيات المكتبات المشتركة
- إصدار Kotlin

### app/build.gradle
- إعدادات بناء التطبيق
- Java/Kotlin Configuration
- Dependencies المختلفة

### gradle.properties
- إعدادات الأداء
- تهيئة Android
- إعدادات Kotlin

## 📦 المكتبات المستخدمة

| المكتبة | الإصدار | الاستخدام |
|---------|---------|----------|
| AndroidX AppCompat | 1.6.1 | واجهة المستخدم |
| Material Design | 1.10.0 | مكونات المواد |
| Retrofit | 2.10.0 | استدعاءات API |
| Gson | 2.10.1 | تحويل JSON |
| Glide | 4.16.0 | تحميل الصور |
| Coroutines | 1.7.3 | البرمجة غير المتزامنة |

## 🔐 الأمان

- ✅ ProGuard Rules محددة
- ✅ Minification للـ Release
- ✅ Obfuscation للكود

## 🎨 التصميم

- المظهر: Material Design 3
- الألوان: Purple & Teal
- الخط: System Default

## 👨‍💻 المطور

تم تطويره بـ ❤️ بواسطة [@Mohammedar55](https://github.com/Mohammedar55)

## 📝 الترخيص

هذا المشروع مفتوح المصدر وحر الاستخدام.

## 🤝 المساهمة

نرحب بالمساهمات! يمكنك:
1. Fork المشروع
2. إنشاء فرع جديد
3. القيام بالتغييرات
4. إرسال Pull Request

## 📞 التواصل

إذا كان لديك أي أسئلة أو اقتراحات، لا تتردد في التواصل!

---

**استمتع بالتطوير! 🎉**
