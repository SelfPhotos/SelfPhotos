<h1 align="center">
  <img src="https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/logo.png?raw=true" height="80" alt="Self Photos Logo" />
  <p>Self Photos</p>
</h1>

<p align="center"><a href="./README.md">English</a> | <a href="./README.zh.md">中文</a> | <a href="./README.de.md">Deutsch</a> | <a href="./README.es.md">Español</a> | <a href="./README.fr.md">Français</a> | हिन्दी | <a href="./README.it.md">Italiano</a> | <a href="./README.ja.md">日本語</a> | <a href="./README.pt.md">Português</a> | <a href="./README.ru.md">Русский</a></p>

**Self Photos** Rust से बनाया गया एक **क्रॉस-प्लेटफ़ॉर्म फोटो और वीडियो प्रबंधन टूल** है, जो Windows, macOS, Linux (जल्द आ रहा है), Android और iOS के लिए उपलब्ध है।

इसे अपने ही उपकरणों के लिए एक पूरी तरह स्थानीय Google Photos समझिए। यह आपके कंप्यूटर, बाहरी ड्राइव, NAS और फोन से तस्वीरों और वीडियो को व्यवस्थित करने में मदद करता है, और गोपनीयता तथा नियंत्रण को सबसे आगे रखता है: आपका मीडिया क्लाउड में अपलोड नहीं होता और आपके अपने उपकरणों पर ही रहता है।

![Screenshot: desktop app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/self-photos-screenshot.png?raw=true)

> 👏 [Discord](https://discord.gg/VCqXcAz6Js) से जुड़ें | [X(Twitter)](https://x.com/wikkefly) पर हमें फॉलो करें

# ✨ मुख्य विशेषताएँ

## 1. बिखरी हुई तस्वीरों और वीडियो को एक जगह लाना

Self Photos आपके कंप्यूटर, बाहरी ड्राइव, जुड़े हुए डिस्क और NAS से तस्वीरें और वीडियो स्कैन करता है, फिर उन्हें एक स्थानीय मीडिया लाइब्रेरी में बदल देता है।

- **एक-क्लिक स्कैन**: अपने कंप्यूटर पर तस्वीरें और वीडियो जल्दी खोजें, और शूटिंग समय, स्थान, मीडिया प्रकार और अन्य मेटाडेटा अपने-आप निकालें
- **लचीले डेटा स्रोत**: लोकल फ़ोल्डर, बाहरी ड्राइव, नेटवर्क स्थान और बहुत कुछ जोड़ें; पुराना फ़ोल्डर पेज अब एक साफ़ डेटा-सोर्स पेज और बेहतर फ़ोल्डर सूची दृश्य बन गया है
- **SMB समर्थन**: NAS पर मौजूद तस्वीरें और वीडियो पहले कॉपी किए बिना सीधे SMB के जरिए स्कैन और इंडेक्स करें
- **लचीले स्कैन नियम**: स्कैन पथ तय करें, फ़ोल्डर बाहर रखें, nested path नियम सेट करें, और आकार-सीमा के आधार पर icons, cache images और अन्य छोटे बेकार फ़ाइलें फ़िल्टर करें
- **फ़ाइल मॉनिटरिंग और मैनुअल स्कैन**: लोकल डेटा स्रोतों को रीयल-टाइम में मॉनिटर किया जा सकता है; गैर-लोकल स्रोत ज़रूरत पड़ने पर मैनुअली स्कैन किए जा सकते हैं
- **Live Photo पहचान**: अलग-अलग स्रोतों में Live Photos को अपने-आप पहचानकर जोड़ता है, ताकि स्थिर फोटो और मूवमेंट क्लिप साथ रहें

![Screenshot: scan select](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/scan-screenshot.png?raw=true)

## 2. मोबाइल एल्बम को अपने कंप्यूटर पर बैकअप करें

Self Photos का मोबाइल ऐप इंस्टॉल करने के बाद, उसे उसी लोकल नेटवर्क पर डेस्कटॉप ऐप के साथ पेयर करें, ताकि Android और iOS डिवाइस से तस्वीरें और वीडियो आपके कंप्यूटर या बाहरी ड्राइव पर बैकअप किए जा सकें।

- **लगाते ही बैकअप**: मोबाइल एल्बम चुनने के बाद नई तस्वीरें और वीडियो अपने-आप कंप्यूटर पर सिंक हो सकते हैं
- **मैनुअल बैकअप**: ज़रूरत पड़ने पर खास तस्वीरें और वीडियो चुनकर बैकअप लें
- **तारीख-सीमा बैकअप**: सिर्फ हाल की तस्वीरें और वीडियो बैकअप करें, जो नए कंटेंट को जल्दी व्यवस्थित करने में उपयोगी है
- **मूल गुणवत्ता**: बिना compression या quality loss के मूल तस्वीरें और वीडियो सहेजें
- **अलग-अलग डिवाइस का स्वतंत्र प्रबंधन**: अलग फोन के लिए अलग बैकअप फ़ोल्डर सेट करें, और subfolders तथा filenames के नियम तय करें, जैसे `E:/Backup/iPhone 16 Pro Max/2025/2025-12/2025.12.01_IMG_1234.jpg`
- **लोकल नेटवर्क ट्रांसफ़र**: बैकअप मोबाइल डेटा का उपयोग नहीं करता; गति आपके लोकल नेटवर्क और डिस्क प्रदर्शन पर निर्भर करती है

![Screenshot: mobile app](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/screenshot-mobile.png?raw=true)

## 3. टाइमलाइन के साथ यादों में लौटना

Self Photos आपकी लाइब्रेरी को तस्वीरों और वीडियो के वास्तविक शूटिंग समय के अनुसार व्यवस्थित करता है, ताकि आप किसी खास दिन, महीने या साल पर डायरी पलटने की तरह लौट सकें।

- **शूटिंग तारीख के अनुसार स्वचालित छंटाई**: तस्वीरें और वीडियो उनके लिए गए समय के आधार पर रखे जाते हैं, केवल फ़ाइल निर्माण समय के आधार पर नहीं
- **तेज़ तारीख जंप**: टाइमलाइन और तारीख नेविगेशन से सीधे किसी खास साल या महीने पर जाएँ
- **बड़ी लाइब्रेरी में भी smooth browsing**: अनुकूलित डेस्कटॉप अनुभव, जो लाखों तस्वीरों में भी तरल बना रहता है
- **Hover preview**: तस्वीरों और वीडियो की त्वरित झलक देखने के लिए mouse over करें, जिससे ब्राउज़िंग और फ़िल्टरिंग तेज़ हो जाती है
- **Built-in video player**: वीडियो सीधे ऐप में चलाएँ, और format support आपके सिस्टम codecs पर निर्भर करता है
- **कई तरह से ब्राउज़ करें**: टाइमलाइन, मूल फ़ोल्डर संरचना, favorites, system default app, या system file manager में फ़ाइल दिखाने का उपयोग करें

![Screenshot: timeline](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/timeline.png?raw=true)

## 4. एल्बम के साथ महत्वपूर्ण पलों को व्यवस्थित करना

समय और फ़ोल्डर संरचना के आधार पर स्वतः व्यवस्था के अलावा, Self Photos में album सुविधा भी है, जिससे आप यात्रा, परिवार, प्रोजेक्ट, छुट्टी या किसी theme-based media को सक्रिय रूप से इकट्ठा कर सकते हैं।

- **थीम वाले एल्बम बनाएं**: अलग-अलग स्रोतों और तारीखों की तस्वीरें और वीडियो एक ही एल्बम में इकट्ठा करें
- **मूल फ़ाइलें अपनी जगह पर रहें**: एल्बम मीडिया को व्यवस्थित और दिखाते हैं, लेकिन मूल फ़ाइलों को नहीं हिलाते
- **लंबी अवधि के संग्रह के लिए उपयुक्त**: शादी, बच्चों का बढ़ना, यात्रा संग्रह, creative assets और दूसरी meaningful collections के लिए अलग-अलग एल्बम बनाए जा सकते हैं

![Screenshot: album](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/album.png?raw=true)

## 5. साफ़ करें, प्रबंधित करें, और नई desktop experience का आनंद लें

Self Photos केवल देखने के लिए नहीं है। यह आपकी media library को अधिक कुशलता से प्रबंधित करने में भी मदद करता है।

- **Duplicate detection**: duplicate तस्वीरें और वीडियो बुद्धिमानी से ढूँढें, उन्हें preview करें, और library साफ़ करने के लिए batch में हटाएँ
- **नई design system**: बड़े photo और video संग्रहों के लंबे समय तक प्रबंधन के लिए अधिक आधुनिक UI और desktop experience
- **Favorites और comparison preview**: महत्वपूर्ण मीडिया को जल्दी से favorite करें और preview पेज पर तस्वीरों की side-by-side तुलना करें
- **Unlimited storage and speed**: क्षमता सिर्फ आपके डिस्क तक सीमित है, और transfer speed सिर्फ आपके लोकल नेटवर्क तथा device performance तक
- **Private and secure**: ऐप offline काम करता है; तस्वीरें और वीडियो आपके उपकरणों से बाहर नहीं जाते, और mobile backup के लिए बस devices का एक ही local network पर होना पर्याप्त है

![Screenshot: duplicate detection](https://github.com/SelfPhotos/SelfPhotos/blob/main/assets/duplicate.png?raw=true)

# ⬇️ डाउनलोड

नवीनतम **desktop installer** और **mobile app** आधिकारिक वेबसाइट से डाउनलोड करें: [https://selfphotos.com/download](https://selfphotos.com/download)
