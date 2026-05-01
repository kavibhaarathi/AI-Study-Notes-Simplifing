[README.md](https://github.com/AI-Study-Notes-Simplifing/files/27270316/README.md)
# NoteWise — AI Study Notes Simplifier 🧠✦

> Transform complex study notes into clear, structured knowledge using Google Gemini AI.

![NoteWise Banner](https://img.shields.io/badge/Powered%20by-Gemini%20AI-blue?style=for-the-badge&logo=google)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![HTML](https://img.shields.io/badge/Built%20with-HTML%20%2F%20CSS%20%2F%20JS-orange?style=for-the-badge)

---

## 📖 About

**NoteWise** is a fully client-side AI-powered web app that takes raw, messy study notes and converts them into clean, structured content. No backend required — just open the HTML file in a browser, enter your Gemini API key, and start learning smarter.

---

## ✨ Features

- **5 Conversion Modes**
  - 📝 **Simplify** — Summary + key concepts + key terms
  - 🔵 **Bullet Points** — Organized bullets + quick reference
  - 🃏 **Flashcards** — Q&A cards ready for revision
  - 👶 **ELI5** — Explain Like I'm 5 with fun analogies
  - 🗺 **Mind Map** — Hierarchical text outline

- **5 Reading Levels** — Child → Middle School → High School → College → Expert
- **4 Built-in Examples** — Photosynthesis, Newton's Laws, French Revolution, DNA Replication
- **Live Word & Char Counter**
- **Copy to Clipboard** & **Download as .txt**
- **Dark luxury UI** — grain texture, smooth animations, fully responsive

---

## 🚀 Demo

> 🔗 Live Site: `https://yourusername.github.io/notewise`

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling & animations |
| Vanilla JavaScript | Logic & API calls |
| Google Gemini 1.5 Flash | AI text generation |
| Google Fonts | Typography (Playfair Display, DM Sans, DM Mono) |

---

## 📦 Project Structure

```
notewise/
│
├── index.html        # Main app (single file — everything included)
└── README.md         # Project documentation
```

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/notewise.git
cd notewise
```

### 2. Get a Gemini API Key

1. Visit [Google AI Studio](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **"Create API Key"**
4. Copy the key (starts with `AIza...`)

> ✅ The Gemini API has a **free tier** — no credit card required.

### 3. Run the App

Simply open `index.html` in any modern browser:

```bash
# Option 1: Double-click index.html
# Option 2: Use VS Code Live Server extension
# Option 3: Use Python's built-in server
python -m http.server 8000
# Then open http://localhost:8000
```

### 4. Enter Your API Key

On first load, a prompt will ask for your Gemini API key. Paste it in — it's stored only in memory for that session.

---

## 🌐 Deploy to GitHub Pages

1. Push your code to GitHub:

```bash
git init
git add .
git commit -m "Initial commit — NoteWise"
git branch -M main
git remote add origin https://github.com/yourusername/notewise.git
git push -u origin main
```

2. Go to your repo on GitHub
3. Click **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch → `/ (root)` → **Save**
6. Your site is live at:

```
https://yourusername.github.io/notewise
```

---

## 🔐 API Key Security

- Your API key is **never stored** in the code or sent to any server other than Google's API
- The key lives only in the browser session memory
- Each user enters their own key — no shared credentials
- **Never commit your API key to GitHub**

---

## 🎮 How to Use

1. Open the app and enter your Gemini API key
2. Choose a **conversion mode** (Simplify, Bullet Points, Flashcards, ELI5, Mind Map)
3. Select a **reading level** from the dropdown
4. Paste your study notes in the left panel (or load an example)
5. Click **Convert →**
6. View the structured output on the right
7. Copy or download the result

---

## 📸 Screenshots

> Add your own screenshots here after deployment.

```
screenshots/
├── home.png
├── simplify-mode.png
└── flashcard-mode.png
```

---

## 🤝 Contributing

Contributions are welcome!

```bash
# Fork the repo
# Create a feature branch
git checkout -b feature/your-feature-name

# Commit your changes
git commit -m "Add: your feature description"

# Push and open a Pull Request
git push origin feature/your-feature-name
```

---

## 💡 Future Ideas

- [ ] PDF / DOCX file upload support
- [ ] Save notes history with localStorage
- [ ] Export as formatted PDF
- [ ] Multi-language support
- [ ] Dark / Light theme toggle
- [ ] Share output via link

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## 🙏 Acknowledgements

- [Google Gemini API](https://ai.google.dev/) — AI backbone
- [Google Fonts](https://fonts.google.com/) — Playfair Display, DM Sans, DM Mono
- [Google AI Studio](https://aistudio.google.com/) — API key management

---

<p align="center">Built with ✦ and Gemini AI</p>
