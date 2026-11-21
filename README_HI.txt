MAHALA STORE Android App Project

इस ZIP में MAHALA STORE का Android Studio प्रोजेक्ट और HTML ऐप शामिल है।

APK बनाने का आसान तरीका (GitHub Cloud Build):
1. ZIP को Extract करें।
2. GitHub पर नया Repository बनाएं।
3. इस फोल्डर के अंदर की सभी फाइलें Repository में Upload करें (ऊपर वाला .github फोल्डर भी शामिल करें)।
4. Repository में Actions टैब खोलें।
5. “Build MAHALA STORE APK” workflow चुनें और “Run workflow” दबाएँ।
6. Build पूरा होने पर workflow run खोलें। नीचे Artifacts में “MAHALA-STORE-APK” डाउनलोड करें।
7. ZIP खोलकर app-debug.apk फोन में भेजें और Install करें। Android पूछे तो उस स्रोत से Install की अनुमति दें।

वैकल्पिक तरीका (कंप्यूटर पर Android Studio):
1. Android Studio में यह प्रोजेक्ट फोल्डर खोलें।
2. Gradle Sync पूरा होने दें (इंटरनेट जरूरी है)।
3. Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
4. APK app/build/outputs/apk/debug/app-debug.apk में मिलेगी।

महत्वपूर्ण सीमाएँ:
- इस चैट के रनटाइम में Android SDK/Gradle build tools उपलब्ध नहीं हैं; इसलिए यहाँ APK binary compile नहीं की जा सकी है।
- मौजूदा ऐप का demo/localStorage व्यवहार जस का तस है। ग्राहक के ऑर्डर/चैट अलग-अलग फोन पर अपने-आप साझा नहीं होंगे। उसके लिए सुरक्षित ऑनलाइन backend/database और admin authentication बनाना होगा।
- UPI QR भुगतान शुरू करने में मदद करता है; ऐप भुगतान की server-side पुष्टि नहीं करता।
- सार्वजनिक उपयोग से पहले demo admin login को सुरक्षित server login से बदलें।
