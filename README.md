#  Gemini AI Chatbot

A sleek, dark-themed AI chatbot built with **Flask** + **Google Gemini** API.

##  Project Structure

```
gemini-chatbot/
├── app.py                  # Flask backend
├── requirements.txt        # Python dependencies
├── .env.example            # Environment variable template
└── templates/
    └── index.html          # Chat UI
```

##  Setup & Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Add your Gemini API key

**Option A** — Create a `.env` file:
```bash
cp .env.example .env
# Edit .env and paste your key
```

**Option B** — Set environment variable directly:
```bash
# Windows
set GEMINI_API_KEY=your_key_here

# Mac/Linux
export GEMINI_API_KEY=your_key_here
```

> Get your API key at: https://aistudio.google.com/app/apikey

### 3. Run the app
```bash
python app.py
```

### 4. Open in browser
```
http://localhost:5000
```

## ✨ Features
-  Multi-turn conversations with memory
- Reset / New Chat button
- Typing indicator
- Dark themed, modern UI
- Mobile-friendly
- Powered by Gemini 1.5 Flash
