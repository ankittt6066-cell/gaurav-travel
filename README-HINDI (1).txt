GAURAV TRAVEL - Android APK Source Project

यह पूरा Android Studio/Gradle project है। इसे GitHub repository की ROOT में अपलोड करें। ZIP फाइल को सीधे repository में डालना पर्याप्त नहीं है; ZIP extract करके उसके अंदर की सभी files और folders upload करें।

PROJECT में शामिल:
- app/ : Android app source, manifest, WebView activity और booking page
- .github/workflows/build-apk.yml : GitHub Actions से APK build workflow
- build.gradle, settings.gradle, gradle.properties : Gradle project configuration

ऐप विवरण:
- App name: GAURAV TRAVEL
- Call: 9129069898
- WhatsApp booking: +91 7007346876
- Book Now पर पूरी booking details WhatsApp message में खुलती हैं; ग्राहक को Send दबाना होगा।
- Vehicle images बाहरी इंटरनेट URL से आती हैं; इंटरनेट आवश्यक है।

GitHub पर अपलोड:
1. Repository खोलें और Code tab चुनें।
2. Add file > Upload files चुनें।
3. इस ZIP को पहले फोन में Extract करें।
4. Project के अंदर की सभी files/folders अपलोड करें; app और .github सहित। Hidden .github folder भी जरूरी है।
5. Commit changes दबाएँ।
6. Actions tab खोलें। 'Build GAURAV TRAVEL APK' workflow चुनें और Run workflow दबाएँ (यदि push पर अपने-आप शुरू न हुआ हो)।
7. Workflow सफल होने पर run खोलें, Artifacts में GAURAV-TRAVEL-APK डाउनलोड करें।
8. Artifact ZIP extract करके app-debug.apk पर टैप करें और Install करें।

ध्यान दें:
- यह source project है, पहले से बनी APK नहीं। GitHub Actions को build पूरा करना होगा।
- Android APK इस environment में compile/test नहीं की गई है।
- GitHub web uploader में folders/hidden files अपलोड करने में दिक्कत हो तो GitHub Desktop/Android browser का desktop mode या दूसरा upload तरीका चाहिए होगा।
