# Question Express ⚡
**Fast & Offline Question Paper Generator App for Teachers**

---

### 🎯 क्यों बनाया? (Purpose)
शिक्षकों को मोबाइल और टैबलेट पर बिना किसी महंगे कंप्यूटर या जटिल सॉफ्टवेयर के तेजी से बोर्ड पैटर्न और सामान्य परीक्षाओं के लिए प्रश्न पत्र (Question Paper) तैयार करने और डाउनलोड करने की सुविधा देना।

---

### 🛠️ कैसे और कहाँ से बनाया? (Development Process & Tools)
* **Development Environment:** स्मार्टफोन और टैबलेट (Wireless Keyboard & Mouse सेटअप) का उपयोग करके निर्मित।
* **AI Collaborator:** Gemini AI के सहयोग से संपूर्ण फ्रंटएंड कोड और लॉजिक डिज़ाइन किया गया।
* **Core Technologies:** HTML5, CSS3, Vanilla JavaScript (Single Page Application Architecture).
* **Key Libraries Used:**
  * **MathJax v3:** गणितीय सूत्रों और संकेतों ($\Sigma, \frac{a}{b}, \theta$) के प्रदर्शन के लिए।
  * **Cropper.js:** चित्रों और डायग्राम को क्रॉप करने के लिए।
  * **html2canvas & jsPDF:** लाइव प्रिव्यू को HD PDF में कंवर्ट करके एक्सपोर्ट करने के लिए।
  * **PWA (Progressive Web App):** Service Worker (`sw.js`) और `manifest.json` के ज़रिए बिना इंटरनेट (Offline) काम करने की क्षमता।

---

### 🌐 कहाँ होस्टेड है? (Hosting & Deployment)
* **Source Code Storage:** GitHub Repository
* **Hosting Platform:** GitHub Pages (Free Web Hosting)
* **Live App Link:** `https://rohihirosan.github.io/qexpress/`
* **Demo Youtube Link:** `https://youtu.be/5LZUeMPWIIU?si=BsrG3vhn3jH6g6IN`

---

### ✨ मुख्य फीचर्स (Key Features)
1. **2-Step Wizard Interface:** बेसिक विवरण भरें ➔ प्रश्न जोड़ें और लाइव PDF देखें।
2. **Diagram Questions:** डायग्राम प्रश्नों के लिए ऑप्शन-वाइज़ इमेज अपलोड और स्मार्ट क्रॉपिंग।
3. **Math Tool Panel:** गणितीय फ़ार्मुलों के लिए वन-क्लिक सिंबल पैनल।
4. **Auto-Save & Backup:** LocalStorage ऑटो-सेव और `.json` बैकअप फाइल सेव/लोड करने की सुविधा।
5. **Multi-Type Questions:** MCQ, Match Column, Passage-Based, Short/Long और Diagram प्रश्नों का समर्थन।
