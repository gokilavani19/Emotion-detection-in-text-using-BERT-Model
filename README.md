# Emotion-Detection-in-Text-Hugging-Face

# Emotion-Detection-in-Text-Hugging-Face

🌍 **Multilingual Sentiment Analysis**

Emotion-Detection-in-Text-Hugging-Face is a robust multilingual sentiment analysis tool powered by Hugging Face Transformers. Effortlessly detect emotions in text across various languages, leveraging advanced NLP models and seamless translation support. The project provides an interactive web interface and a progressive web app (PWA) experience for accessibility and ease of use.

---

## 🚀 Introduction

Understanding emotions in text is crucial for modern applications ranging from customer feedback analysis to social media monitoring. This project combines the power of Hugging Face models, automatic language detection, and translation to deliver accurate sentiment analysis for users worldwide.

---

## ✨ Features

- **Multilingual Support:** Detect emotions in text written in any language.
- **Automatic Language Detection:** No need to specify the language—it's detected automatically!
- **Instant Translation:** Non-English text is translated for accurate analysis.
- **State-of-the-Art Sentiment Model:** Uses `cardiffnlp/twitter-roberta-base-sentiment` for robust predictions.
- **User-Friendly Web Interface:** Built with Gradio for quick interaction.
- **Progressive Web App (PWA):** Offline support and mobile-friendly experience via `frontend/sw.js`.

---

## 🛠️ Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/your-username/Emotion-Detection-in-Text-Hugging-Face.git
    cd Emotion-Detection-in-Text-Hugging-Face
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    # Or install manually:
    pip install gradio transformers deep-translator langdetect torch
    ```

3. **(Optional) Setup Frontend for PWA**
    Place the contents of the `frontend` folder in your web root.

---

## 💡 Usage

1. **Run the Application**
    ```bash
    python app.py
    ```

2. **Open the Web Interface**
    - Access via the local Gradio URL provided in the terminal.
    - Enter any text in your preferred language and view the detected emotion!

3. **PWA Installation (Optional)**
    - Visit the web app in your browser.
    - Click the "Install" button to add it to your device as a PWA.

---

## 📁 Project Structure

```
Emotion-Detection-in-Text-Hugging-Face/
├── app.py                # Main backend application (Gradio interface)
├── requirements.txt      # Python dependencies
├── frontend/
│   ├── sw.js             # Service Worker for PWA
│   ├── index.html        # Web interface
│   ├── manifest.json     # PWA manifest
│   └── icons/            # App icons
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

> **Made with ❤️ using Hugging Face, Gradio, and the open-source community.**

---

## 📫 Contact

For questions, issues, or suggestions, feel free to open an [issue](https://github.com/your-username/Emotion-Detection-in-Text-Hugging-Face/issues) or reach out via [GitHub Discussions](https://github.com/your-username/Emotion-Detection-in-Text-Hugging-Face/discussions).

---

**Happy emotion detecting! 😊🌈**

## License
This project is licensed under the **MIT** License.

---
🔗 GitHub Repo: https://github.com/gokilavani19/Emotion-detection-in-text-using-BERT-Model/