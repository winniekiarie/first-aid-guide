# 🩺 First Aid Step-by-Step Guide
### Powered by the Anthropic Claude API

A beginner-friendly, AI-powered first aid assistant that gives clear, step-by-step emergency guidance using the Claude API.

---

## 🚀 Quick Start

No build tools or package installs needed! This is a single HTML file.

### Option A – Open directly in your browser
```bash
# Clone or download the project
git clone https://github.com/YOUR-USERNAME/first-aid-guide.git

# Open the file directly
open index.html        # macOS
start index.html       # Windows
xdg-open index.html   # Linux
```

### Option B – Run a local dev server (recommended)
```bash
# Using Python (comes pre-installed on most systems)
python3 -m http.server 8080

# Then visit:
# http://localhost:8080
```

---

## 🔑 API Key Setup

1. Visit [https://console.anthropic.com](https://console.anthropic.com)
2. Sign up / log in and create an API key
3. Paste the key into the app's **API Key** input field
4. Click **Save Key** – you're ready!

> ⚠️ Your API key is stored only in memory (not saved to disk or localStorage). You'll need to re-enter it if you reload the page.

---

## 🗂️ Project Structure

```
first-aid-guide/
├── index.html     ← The entire application (single file)
└── README.md      ← You are here
```

---

## ✨ Features

- **12 Quick Scenario Buttons** – Burns, Bleeding, Choking, CPR, Shock, and more
- **Free-Text Input** – Describe any emergency in your own words
- **Numbered Step-by-Step Response** – Clear, stress-readable instructions from Claude AI
- **Query History** – Re-run recent questions with one click
- **No Installation Required** – Pure HTML + CDN React

---

## 🛠️ Technology Used

| Tech | Purpose |
|------|---------|
| HTML / CSS / JS | App structure & styling |
| React 18 (CDN) | UI components |
| Babel Standalone | JSX transpilation in-browser |
| Anthropic Claude API | AI first aid responses |

---

## 🧠 How the AI Works

The app sends your emergency query to the Claude API (`claude-sonnet-4-20250514`) with a specialized system prompt that instructs it to:
- Provide numbered, step-by-step first aid instructions
- Use plain, calm language suitable for stressful situations
- Flag when emergency services should be called
- Warn about what NOT to do

---

## ⚠️ Disclaimer

This tool is for **educational purposes only**. Always call **911** (or your local emergency number) for life-threatening emergencies. This is not a substitute for professional medical advice.

---

## 📄 License

MIT – Free to use, modify, and distribute.
