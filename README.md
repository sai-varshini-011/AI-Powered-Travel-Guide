# 🌍 AI-Powered Travel Guide

**Explore Places. Discover Stories. Powered by AI. ✨**

An AI-powered travel guide web application built as part of the **LEVEL X Hands-on AI Workshop by NxtWave Academy**.

The application uses **Google Gemini AI** to generate historical information and interesting insights about tourist destinations, helping users explore and learn about places through AI.

This project is being developed further, with plans to integrate **Murf.AI** for AI-powered audio guides.

## 🌐 Live Demo

🚀 **[Try the AI-Powered Travel Guide](https://ai-powered-travel-guide-rolg.onrender.com/)**

Explore tourist destinations and discover AI-generated historical information powered by Google Gemini.

**Note:** The application is hosted on Render's free tier, so it may take a few moments to load after a period of inactivity.

## ✨ Features

### ✅ Currently Implemented

- 🌍 **Tourist Destination Selection:** Explore different tourist destinations.
- 📖 **Historical Information:** Generate AI-powered historical insights about selected places.
- 📝 **Text-Based Information:** Read AI-generated descriptions directly in the application.
- 📚 **Summary & Detailed Views:** Choose how much information you want.
- 💻 **Interactive Interface:** A simple and user-friendly travel guide experience.

### 🚀 Future Scope

- 🔊 AI-powered audio guides using Murf.AI
- 🎙️ Voice selection and customization
- 🌐 Enhanced multilingual support
- 🗺️ Personalized travel itineraries
- ✨ Improved user experience and additional features

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML, CSS | Frontend design |
| JavaScript | Frontend functionality |
| Python | Backend development |
| Flask | Backend API |
| Google Gemini API | AI-generated travel information |
| Murf.AI | Planned audio integration |
| GitHub | Version control |
| Render | Backend deployment platform |

## 📂 Project Structure

```text
AI-Powered-Travel-Guide/
│
├── Backend/
│   ├── app.py
│   ├── requirements.txt
│   └── .env (local only)
│
├── Frontend/
│   ├── index.html
│   └── index.js
│
├── .gitignore
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/sai-varshini-011/AI-Powered-Travel-Guide.git
cd AI-Powered-Travel-Guide
```

### 2. Install Dependencies

```bash
cd Backend
pip install -r requirements.txt
```

### 3. Configure Environment Variables

Create a `.env` file inside the `Backend` folder and add:

```env
GEMINI_API_KEY=your_gemini_api_key
```

**Note:** Never share API keys publicly or upload your `.env` file to GitHub.

### 4. Run the Backend

```bash
python app.py
```

The Flask server should start at:

`http://127.0.0.1:5000`

### 5. Run the Frontend

Open `Frontend/index.html` using VS Code Live Server or another local development server.

Select a destination and generate historical information using AI.

## 🔄 How It Works

1. The user selects a tourist destination.
2. The user chooses the information length and language.
3. The frontend sends a request to the Flask backend.
4. Google Gemini generates information about the selected destination.
5. The generated information is displayed on the frontend.

**Application Workflow:**

```text
User
  ↓
Frontend (HTML, CSS, JavaScript)
  ↓
Flask Backend
  ↓
Google Gemini API
  ↓
AI-Generated Travel Information
  ↓
Frontend Display
```

## 🔐 API Key Security

- API keys are managed using environment variables.
- The `.env` file is excluded from GitHub through `.gitignore`.
- Sensitive credentials should never be committed to public repositories.
- Deployment environment variables must be configured separately.

## 🌱 Future Enhancements

The next step is integrating **Murf.AI** to convert AI-generated travel information into audio guides.

Further improvements will focus on multilingual experiences, voice customization, personalized trip planning, and making the application more interactive and accessible.

## 🙌 Acknowledgement

This project was developed as part of the **LEVEL X Hands-on AI Workshop**, organized by **NxtWave Academy** at **Chalapathi Institute of Engineering and Technology, Vijayawada**.

The workshop was a great opportunity to explore Generative AI, experiment with APIs, and understand how AI can be used to build practical applications.

Grateful to NxtWave Academy and everyone involved in making this hands-on learning experience possible!

## 👩‍💻 About the Developer

**M Sai Varshini**

*Curious Mind | Lifelong Learner | Turning Ideas into Projects ✨*

**Student by Education | Learner by Choice | Builder by Curiosity 🌱**

**GitHub:** https://github.com/sai-varshini-011

## ©️ Copyright & A Little Reminder

© 2026 M Sai Varshini. All rights reserved.

Built with curiosity, effort, countless experiments, and a little help from AI. ✨

**Inspiration is always welcome. Copying without giving credit? Not so much. 🙂**

Feel free to explore the project, learn from it, and get inspired. But if you're using someone else's work, the least you can do is acknowledge their effort.

**AI can generate content, but it can't generate originality for you. 😉**

A little credit costs nothing, but it says a lot about your character.

*Learn from others. Build something of your own. And never forget to give credit where it's due.* 🤝

## 📌 Project Status

🚀 **Live & Under Development**

The AI-powered historical information feature has been implemented and the application is now deployed on Render.

More features, including Murf.AI-powered audio guides, are planned for future updates!

---

**Built as part of LEVEL X | Learning by Building. 💻✨**
