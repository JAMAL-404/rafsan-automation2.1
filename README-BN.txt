RAFSAN AUTOMATION WEN — ANDROID APP PROJECT

এই প্রজেক্টটি আপনার লাইভ ওয়েবসাইটকে Android অ্যাপের মতো চালায়।
অ্যাপ চালু হলে Rafsan Automation Wen স্প্ল্যাশ স্ক্রিন/আইকন দেখাবে,
তারপর আপনার ওয়েবসাইট WebView-এর মধ্যে খুলবে।

ওয়েবসাইট URL:
https://jamal-404.github.io/rafsan-automation-wen/

APK বানানোর সহজ উপায় (GitHub Actions):
1. GitHub-এ নতুন Public বা Private repository তৈরি করুন।
2. এই ZIP Extract করুন।
3. Extract করা প্রজেক্টের সব ফাইল ও ফোল্ডার repository-র root-এ upload করুন।
   .github ফোল্ডারটিও অবশ্যই upload করতে হবে।
4. Commit changes করুন।
5. Repository-র Actions tab খুলুন।
6. "Build Android APK" workflow শেষ হওয়া পর্যন্ত অপেক্ষা করুন।
7. সবুজ successful workflow-তে প্রবেশ করুন।
8. নিচের Artifacts থেকে Rafsan-Automation-Wen-APK ডাউনলোড করুন।
9. ZIP extract করে app-debug.apk ফোনে install করুন।
   Android চাইলে Settings থেকে এই উৎসের APK install করার অনুমতি দিন।

নোট:
- এটি একটি WebView Android app; ওয়েবসাইটে পরিবর্তন করলে অ্যাপে নতুন কনটেন্টও দেখা যাবে।
- APK install করার আগে Android নিরাপত্তা সতর্কতা ভালোভাবে পড়ুন।
- Facebook password, cookies, 2FA code বা access token সংগ্রহ/সংরক্ষণ করে না।
- এই প্রজেক্টের URL MainActivity.java-তে HOME_URL হিসেবে সেট করা আছে।
