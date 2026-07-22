# 🌻 ШвидкоПереклад

> Free AI translator with specialized context support for official documents, medical terms, and legal paperwork. Built especially for Ukrainians navigating life abroad.

**🔗 [Open Application](https://shvydkopereklad.github.io/)**

## ✨ Features

- 🌐 **Free translation** — no API keys, no registration, no signup
- 🎯 **Context-aware** — specialized modes for legal, medical, official documents, education, and banking
- 📷 **Photo OCR** — recognize and translate text from document photos directly in your browser
- 🎤 **Voice input** — speak instead of typing
- 🔊 **Smart text-to-speech** — listen to translations with one-click stop toggle
- 💬 **Phrasebook** — curated useful phrases for emergencies, medicine, documents, housing, and work
- 📚 **History** — automatic saving of your last 100 translations
- ⭐ **Saved translations** — bookmark important translations for quick access (up to 200)
- 🔒 **Privacy-first** — all data stored locally, never leaves your browser
- 📱 **Mobile-optimized** — responsive design for phones, tablets, and desktops
- 🛡️ **Daily fair-use limits** — keeps free APIs available for everyone (resets at midnight)
- 🌍 **5 languages** — Ukrainian 🇺🇦 · English 🇬🇧 · Polish 🇵🇱 · German 🇩🇪 · Czech 🇨🇿

## 🚀 How It Works

### Translation Providers (Automatic Fallback)
1. **Google Translate** — primary provider (fastest, best quality)
2. **MyMemory API** — fallback (5000 words/day free)
3. **LibreTranslate** — secondary fallback (public instances)

If one provider fails or is unavailable, the next one automatically takes over — you always get a translation.

### OCR (Optical Character Recognition)
Powered by [Tesseract.js](https://tesseract.projectnaptha.com/) — runs entirely in your browser using WebAssembly. Images never leave your device.

### Text-to-Speech
Built on the Web Speech API with robust handling of browser quirks:
- Async voice loading with smart fallback matching
- Chrome 15-second cutoff bug workaround
- One-click toggle (start/stop) on every speak button
- Auto-stop on tab switch and page unload
- Visual feedback with pulsing red animation while speaking

## 📖 Usage

### Text Translation
1. Open the [application](https://shvydkopereklad.github.io/)
2. Select source and target languages
3. Choose a context (optional, improves accuracy for specialized vocabulary)
4. Type, paste, or speak (🎤) your text
5. Click **🔄 Перекласти** (Translate)
6. Listen (🔊), copy (📋), or save (⭐) the result

### Photo Translation
1. Go to the **📷 Фото** tab
2. Upload a photo or take one with your camera
3. Select source and target languages
4. Click **🔍 Розпізнати і перекласти**
5. Listen to the result with the speak button

### Phrasebook
1. Go to the **💬 Фрази** tab
2. Pick a category (Emergency, Medical, Documents, Housing, Work)
3. Choose target language
4. Tap any phrase to copy and hear it aloud

### Saved Translations
1. After translating, click **⭐ Зберегти**
2. Visit the **⭐ Збережені** tab to review
3. Open, copy, speak, or delete saved items individually

## 🛠️ Tech Stack

- Pure HTML, CSS, and JavaScript — no build step, no framework
- [Tesseract.js v5](https://github.com/naptha/tesseract.js) for in-browser OCR
- Web Speech API for voice input and text-to-speech
- IndexedDB for image storage
- LocalStorage for settings, history, and saved translations
- Custom modal system (no native browser dialogs)
- Progressive Web App ready

## 🔒 Privacy

- ✅ No analytics tracking your translations
- ✅ No user accounts or registration
- ✅ Photos are processed locally with Tesseract.js
- ✅ History and saved items live only in your browser
- ✅ Translation API calls send only the text being translated
- ✅ One-click "Clear all data" button removes everything instantly

## 🎨 Design

The visual identity draws inspiration from Ukrainian symbols — the blue and yellow flag and the sunflower 🌻 — representing resilience, warmth, and hope. Designed to feel friendly and accessible during stressful situations like medical appointments or document submissions.

## 🎯 Use Cases

- 📋 Translating official documents and government forms
- 🏥 Medical appointments and prescription instructions
- ⚖️ Legal paperwork, contracts, and notarized documents
- 🏠 Housing applications and rental agreements
- 💼 Job applications, CVs, and interview preparation
- 🎓 School enrollment forms and educational materials
- 🏦 Banking documents and financial paperwork
- 🆘 Emergency communication when you don't speak the local language

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests on [GitHub](https://github.com/ShvydkoPereklad/ShvydkoPereklad.github.io).

Ways you can help:
- 🐛 Report bugs and edge cases
- 🌍 Suggest additional languages or phrase categories
- 🎨 Improve UI/UX and accessibility
- 📝 Add translations for the interface itself
- ⭐ Star the repository to spread the word

## 📄 License

MIT © 2025-2026 Yuliya Kolesnikova

---

Made with 💙💛 for Ukrainians around the world.
