Daily Work Report — Android APK

এই ZIP-এ আপনার HTML ফাইলটি Android WebView অ্যাপ হিসেবে প্যাকেজ করা হয়েছে।
অ্যাপের নাম: Daily Work Report
Package ID: com.sm40.dutylog
Version: 1.0

মোবাইল দিয়ে APK তৈরি করার সহজ পদ্ধতি:
1) GitHub-এ লগইন করে New repository তৈরি করুন (যেমন: sm40-duty-log)।
2) এই ZIP ফাইলটি Extract করে ভেতরের সব ফাইল/ফোল্ডার repository-তে আপলোড করুন।
   .github ফোল্ডারটিও অবশ্যই আপলোড করবেন।
3) GitHub repository-তে Actions ট্যাব খুলুন।
4) বাম পাশে "Build SM40 APK" নির্বাচন করে "Run workflow" চাপুন।
5) Build শেষ হলে ওই workflow run-এর নিচে Artifacts থেকে
   "SM40-Duty-Log-APK" ZIP ডাউনলোড করুন।
6) ZIP Extract করে app-debug.apk ফোনে ইনস্টল করুন।
   Android চাইলে Settings থেকে এই উৎসের জন্য "Install unknown apps" অনুমতি দিন।

গুরুত্বপূর্ণ:
- প্রথমবার Tailwind, Font Awesome, Hind Siliguri font এবং রিপোর্ট export লাইব্রেরি
  CDN থেকে লোড হওয়ার কারণে ইন্টারনেট সংযোগ প্রয়োজন।
- ফর্মের ডেটা ফোনের অ্যাপের নিজস্ব WebView storage-এ সেভ হয়।
- অ্যাপ আনইনস্টল/ডেটা ক্লিয়ার করলে সংরক্ষিত রিপোর্ট মুছে যেতে পারে।
- এটি Debug APK; ব্যক্তিগতভাবে ইনস্টল/পরীক্ষার জন্য। Play Store প্রকাশের জন্য
  আলাদা signed release build প্রয়োজন।
