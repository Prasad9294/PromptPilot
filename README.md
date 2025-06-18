# 🧠 PromptPilot - Multi-Tool AI Web App

PromptNest is a sleek and powerful web application that brings together multiple AI tools into one simple interface. Built with **React + TailwindCSS**, it leverages advanced language and vision models to:

- ✂️ **Summarize Long Texts**
- 🤖 **Chat with AI (Gemini API)**
- 🎨 **Generate Images from Text Prompts**

---

## 🚀 Features

### 📄 Text Summarizer
- Paste large paragraphs or essays.
- Get a clean, concise summary in seconds.

### 🤖 AI Chatbot
- Ask any question or prompt.
- Get intelligent answers using Google's Gemini API.

### 🎨 Image Generator
- Type a creative prompt like “a futuristic city at sunset”.
- Instantly generate an AI image using Hugging Face APIs.

---

## 🛠️ Tech Stack

| Tech              | Description                        |
|------------------|------------------------------------|
| **React**         | Frontend framework                 |
| **Tailwind CSS**  | UI Styling                         |
| **Axios**         | API requests                       |
| **Gemini API**    | For Chat & Text Summarization      |
| **Hugging Face API** | For Text-to-Image generation |

---

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/your-username/promptnest.git
cd promptnest

```

2. **Install dependencies**
```bash
npm install
```

3. **Setup environment variables**

Create a `.env` file in the root with:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key
VITE_HUGGING_FACE_API_KEY=your_hugging_face_api_key
```

> ⚠️ You must have valid API keys from:
> - [Gemini (Google AI)](https://aistudio.google.com/app/apikey)
> - [Hugging Face](https://huggingface.co/settings/tokens)

4. **Run the app**
```bash
npm run dev
```

---

## 📁 Project Structure

```
src/
├── components/
│   ├── ChatBot.jsx
│   ├── ImageGenerator.jsx
│   └── TextSummarizer.jsx
├── App.jsx
├── main.jsx
└── index.css
```

---

## 🌐 Live Demo

👉 [Deploy your app on Netlify or Vercel and put the link here]

---

## 🙌 Credits

- Developed with 💖 by Atharv
- Powered by **Google AI** and **Hugging Face**

---

## 📜 License

This project is open source under the [MIT License](LICENSE).
```

---

### ✅ What You Can Do Next:

- 📦 Add the CodeGenerator later as a separate branch
- 🌍 Deploy to [Netlify](https://netlify.com/) or [Vercel](https://vercel.com/) for a public demo
- 🖼 Want me to make a logo/banner for your GitHub README?

Let me know and I’ll make it!
