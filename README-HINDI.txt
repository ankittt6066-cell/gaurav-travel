GAURAV TRAVEL - Android APK project

यह Android ऐप का source project है। इसमें आपके मौजूदा booking page को Android WebView ऐप के अंदर रखा गया है।

मुख्य बातें:
- ऐप का नाम: GAURAV TRAVEL
- Booking page: app/src/main/assets/index.html
- Call नंबर: 9129069898। WhatsApp booking message +91 7007346876 पर तैयार होता है। ग्राहक को WhatsApp में Send दबाना होगा।
- गाड़ियों की फोटो ऑनलाइन URL से लोड होती हैं, इसलिए इंटरनेट जरूरी है।

महत्वपूर्ण:
यह ZIP APK नहीं है। APK बनाने के लिए नीचे दिए गए GitHub Actions workflow का उपयोग करें। इस environment में Android SDK/Gradle उपलब्ध नहीं था, इसलिए APK compile/sign नहीं किया गया।

मोबाइल से APK बनाने के चरण:
1. GitHub पर अपना account खोलें और नया repository बनाएं: gaurav-travel-android
2. इस ZIP को extract करके इसके अंदर की सभी files/folders repository में upload करें। .github folder भी upload होना चाहिए।
3. GitHub repository में Actions tab खोलें।
4. "Build GAURAV TRAVEL APK" workflow चुनें और Run workflow दबाएं।
5. Build पूरा होने पर workflow run के नीचे Artifacts में GAURAV-TRAVEL-APK डाउनलोड करें।
6. ZIP extract करें; app-debug.apk मिलेगा। उसे Android फोन में खोलकर Install करें। जरूरत पड़ने पर Settings में उस स्रोत से app install की अनुमति दें।

यह debug APK होगा, परीक्षण/अपने उपयोग के लिए। Play Store पर डालने के लिए अलग release signing और store setup चाहिए।
