# The English Master Key — Android App (GitHub Actions Builder)

**Author:** Fahim Miya  
**App Package:** `com.fahimmiya.englishmasterkey`

## কীভাবে GitHub Actions দিয়ে স্বয়ংক্রিয়ভাবে APK তৈরি করবেন:

১. গিটহাবে (GitHub) একটি নতুন Repository তৈরি করুন।
২. এই প্রজেক্টের সব ফাইল ও ফোল্ডার (`app`, `.github/workflows/build-apk.yml`, `build.gradle`, `settings.gradle`, `gradle.properties`) আপনার Repository-তে আপলোড (Commit) করুন।
৩. ফাইল আপলোড হওয়ার সাথে সাথেই গিটহাবের **Actions** ট্যাবে গিয়ে দেখবেন **"Build Android APK (The English Master Key)"** চালু হয়ে গেছে।
৪. ১–২ মিনিট পর বিল্ড সবুজ রঙের (✅ Success) হলে সেটির ভেতরে ঢুকে নিচে **Artifacts** সেকশন থেকে **`English-Master-Key-APK`** ডাউনলোড করুন।
৫. ডাউনলোড করা জিপের ভেতরে **`EnglishMasterKey-Signed.apk`** ফাইলটি পাবেন, যা সরাসরি আপনার অ্যান্ড্রয়েড ফোনে ইনস্টল করতে পারবেন!
