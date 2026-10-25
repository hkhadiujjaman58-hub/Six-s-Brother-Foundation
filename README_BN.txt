Six Brothers Foundation — Android App Project

এটি Android Studio-তে APK বানানোর জন্য প্রজেক্ট সোর্স। এটি নিজে APK ফাইল নয়।

APK বানানোর ধাপ:
1) কম্পিউটারে Android Studio ইনস্টল করুন এবং Android SDK Platform 35 সেটআপ করুন।
2) Android Studio থেকে এই প্রজেক্ট ফোল্ডারটি Open করুন।
3) Gradle Sync সম্পন্ন হতে দিন।
4) Build > Build Bundle(s) / APK(s) > Build APK(s) নির্বাচন করুন।
5) সফল হলে app/build/outputs/apk/debug/app-debug.apk তৈরি হবে।
6) APK ফোনে কপি করে ইনস্টল করা যাবে। অন্য সদস্যদেরও একই APK শেয়ার করা যাবে।

অফলাইন নোট:
- অ্যাপের রেকর্ড ফোনের অ্যাপের WebView storage-এ সংরক্ষিত হবে।
- প্রতিটি ফোনে আলাদা ডেটা থাকবে; অটোমেটিক সিঙ্ক হবে না।
- অ্যাপ আনইনস্টল করলে ডেটা হারাতে পারেন; নিয়মিত ব্যাকআপ নিন।
- ডেটা export/import সুবিধা ব্রাউজার/Android WebView-এর ফাইল-পিকার আচরণের ওপর নির্ভর করতে পারে।
