
   # 🚀 HackFlow - AI-Powered Hackathon Companion

HackFlow is your ultimate hackathon assistant — an AI-powered platform that helps developers, students, and innovators ideate, pitch, and plan hackathon-ready projects in minutes— with the help of Google’s Gemini AI.

---

## 🌟 Features

- 💡 **AI Project Idea Generator** — Based on domain, tech stack, team size & difficulty
- 🧠 **Prompt Generator** — One-click prompt to rebuild the entire project via LLMs like Gemini or ChatGPT
- 🎤 **Pitch Generator** — Customizable pitch with tone, language, and duration control
- 💾 **Save Ideas & Prompts** — Store your ideas with implementation roadmap and prompt
- 🖼️ **Responsive UI** — Sleek, dark-mode-friendly interface with smooth Framer Motion animations

---


## 🛠️ Tech Stack

| Tech          | Usage                         |
|---------------|-------------------------------|
| React.js      | Frontend framework            |
| Tailwind CSS  | UI styling                    |
| Framer Motion | Animations                    |
| Vite          | Build tool                    |
| Gemini 1.5 API| Project idea & prompt generation |
| Context API   | Global state management       |

---

## 📸 Screenshots

> ![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)


## ⚙️ Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/09khushi09/HackFlow.git
cd HackFlow-BinaryBrains
2. Install Dependencies
bash
Copy
Edit
npm install
3. Set Up API Key
Create a .env file in the root:

env
Copy
Edit
VITE_GEMINI_API_KEY=your_gemini_api_key
Get your key from: https://makersuite.google.com/app/apikey

4. Run the App
bash
Copy
Edit
npm run dev
🧩 Folder Structure
css
Copy
Edit
src/
├── components/
│   ├── PitchGenerator.jsx
│   ├── PromptGenerator.jsx
│   └── Toast.jsx
├── pages/
│   └── IdeaGenerator.jsx
├── services/
│   └── storageService.js
├── utils/
│   └── generatefromGemini.js
├── App.jsx
├── main.jsx

Author :
Khushi Gupta
