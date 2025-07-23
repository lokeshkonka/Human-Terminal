
# 🧠 Human Terminal

**Human Terminal** is an emotion-powered fake terminal interface that blends creativity, poetry, and AI.  
Type commands like `//write poem`, `//debug my heart`, or `//code my pain`, and watch GPT-4 respond like a soul trapped in code.

> A project where the terminal doesn't just compute — it *feels*.

---
🤝 Contributions
Feel free to fork, remix, or collab — especially if you have an idea for a new emotional command.

## 🌌 Live Demo

Coming Soon:

---

## 🎯 Project Vision

Built with the idea that a terminal can be more than just code —  
**Human Terminal** is where emotions, thoughts, and humor are processed through artificial intelligence in a *developer aesthetic*.

---

## 🖼️ Preview

![Preview Screenshot](./public/demo.png)

---

## ⚙️ Features

✅ Fake terminal interface with:
- Blinking cursor
- Typing effect
- Sound effects (clicks, keypress)

🤖 AI-Driven Interactions:
- GPT-4 for emotional and poetic outputs
- DALL·E for visual image generation
- Custom command prompts

💾 Optional Add-ons:
- Save command history (feelings.log)
- Auth (Clerk or anonymous)
- Shareable terminal snapshots

---

## 🔡 Supported Commands

| Command            | Description                                         |
|--------------------|-----------------------------------------------------|
| `//write poem`     | Returns a 2-liner or short poem based on mood       |
| `//debug my heart` | Mimics a fake emotional error log                   |
| `//code my pain`   | Returns a metaphorical code block with emotions     |
| `//generate art`   | Uses DALL·E to generate art from your feelings      |
| `//motivate`       | GPT sends a dose of positivity                      |
| `//simulate chat`  | AI becomes your younger/older self                  |
| `//feelings.log`   | Lists your previous thoughts and responses          |

---

## 🛠 Tech Stack

- **Frontend:** Next.js 14 (App Router), TailwindCSS, Framer Motion
- **AI Backend:** OpenAI GPT-4, DALL·E API
- **Optional Storage:** MongoDB, Mongoose (Command Logs)
- **Auth:** Clerk.dev or custom JWT

---

## 🧠 Folder Structure
📂 server/           (Node.js & Express Backend)
│   ├── config/        (Database connection, env variables)
│   │   └── db.js
│   ├── controllers/   (Logic for handling requests)
│   ├── middleware/    (Auth checks, error handling)
│   ├── models/        (Mongoose schemas)
│   ├── routes/        (API endpoints)
│   ├── server.js      (Main server entry point)

/app
└─ page.tsx // Main UI
└─ api/gpt/route.ts // Handles GPT requests

/components
└─ Terminal.tsx // Terminal output display
└─ InputField.tsx // Input + animation + cursor
└─ TerminalLine.tsx // Each command + response
└─ SoundPlayer.tsx // Typewriter effects

/lib
└─ openai.ts // GPT/DALL·E call logic
└─ prompts.ts // Prompt templates

/styles
└─ terminal.css // Glassmorphism theme

/models
└─ CommandLog.ts // (Optional) MongoDB model



🔮 Future Upgrades
 Command autocomplete

 Theme switcher: Dark / Hacker / Soft

 Keyboard-only navigation

 Terminal log export / .log file download

 Deploy to mobile PWA app




🧑‍💻 Creator
Lokesh Konka
Poet × Developer × Overthinker
