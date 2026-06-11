
# AI Workplace Productivity Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-informational)](#)
[![Status](https://img.shields.io/badge/status-active-success)](#)
[![Built with AI](https://img.shields.io/badge/Built%20with-AI-7c3aed)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](#contributing)

> A modern, SaaS-style web application that uses AI to automate everyday workplace tasks — writing emails, summarizing meetings, and answering workplace questions through an intelligent assistant.

---

## ✨ Project Description

The **AI Workplace Productivity Assistant** is a professional productivity platform that helps employees, managers, and teams reclaim their time. Through a clean dashboard experience, users can generate polished emails tailored to any tone and audience, transform unstructured meeting notes into executive-ready summaries with action items, and chat with an AI assistant designed specifically for the workplace.

The platform is built to feel like a real enterprise SaaS product: fast, responsive, accessible, and grounded in **Responsible AI principles** that keep humans in the loop.

---

## 🚀 Key Features

### 📧 Smart Email Generator
- Context-based email generation from a short brief
- Multiple tone options: *Formal, Informal, Persuasive, Friendly, Professional*
- Audience-specific adaptation: *Client, Manager, Team Member, Stakeholder*
- Auto-generated subject line, body, and call-to-action
- One-click **copy-to-clipboard** and regenerate

### 📝 Meeting Notes Summarizer
- Summarizes long meeting notes or transcripts in seconds
- Extracts key discussion points and decisions made
- Generates structured **action items** with owners and deadlines
- Highlights important tasks, dates, and responsibilities
- Export summaries as **TXT** or **PDF**

### 🤖 AI Workplace Assistant
- Interactive, real-time chatbot experience
- Multi-turn conversations with persistent history
- Curated **suggested prompts** for common workplace tasks
- Typing indicator and instant feedback
- One-click **clear chat** for fresh sessions

### 📊 Dashboard Features
- Modern sidebar navigation
- Productivity statistics & estimated time saved
- Recent AI activity tracking
- Quick-access cards to all tools

---

## 🖼️ Screenshots

> Replace the placeholders below with real screenshots from your deployment.

| Dashboard | Email Generator |
|-----------|-----------------|
| ![Dashboard](./docs/screenshots/dashboard.png) | ![Email Generator](./docs/screenshots/email.png) |

| Meeting Summarizer | AI Assistant |
|--------------------|--------------|
| ![Summarizer](./docs/screenshots/summarizer.png) | ![Assistant](./docs/screenshots/assistant.png) |

**Mobile Responsive View**

![Mobile View](./docs/screenshots/mobile.png)

---

## 🛠️ Technology Stack

### Frontend
| Tool | Purpose |
|------|---------|
| **React** | UI framework |
| **Next.js** | App framework / SSR *(placeholder)* |
| **TypeScript** | Type safety |
| **Tailwind CSS** | Utility-first styling |
| **shadcn/ui** | Accessible component primitives |

### Backend
| Tool | Purpose |
|------|---------|
| **Node.js** | Server runtime |
| **Express.js** | API layer *(placeholder)* |

### AI Integration
| Tool | Purpose |
|------|---------|
| **OpenAI API** | Text generation, summarization, chat |

### Deployment
| Tool | Purpose |
|------|---------|
| **Vercel** | Frontend hosting *(placeholder)* |
| **Netlify** | Alternative hosting *(placeholder)* |

---

## 🏗️ Project Architecture

```
project-root/
├── public/                 # Static assets
├── src/
│   ├── components/         # Reusable UI components
│   ├── pages/              # Application routes
│   ├── services/           # API + AI service layer
│   ├── hooks/              # Custom React hooks
│   ├── utils/              # Helpers and formatters
│   ├── styles/             # Global styles & tokens
│   └── assets/             # Images, icons, fonts
├── README.md
├── package.json
└── .env
```

---

## ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/ai-workplace-productivity-assistant.git

# 2. Navigate into the project folder
cd ai-workplace-productivity-assistant

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

The app will be available at `http://localhost:3000`.

---

## 🔐 Environment Variables

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_openai_api_key_here
API_BASE_URL=https://api.your-domain.com
```

> ⚠️ Never commit your `.env` file. Add it to `.gitignore`.

---

## 📖 Usage Guide

| Feature | How to Use |
|---------|------------|
| **Generate Emails** | Open *Email Generator*, describe the purpose, choose tone & audience, then click **Generate**. |
| **Summarize Meetings** | Open *Meeting Summarizer*, paste your raw notes, click **Summarize**, then export as TXT/PDF. |
| **Chat with the Assistant** | Open *AI Assistant*, pick a suggested prompt or type your own question. |
| **Dashboard** | View productivity stats, recent activity, and jump into any tool from the home screen. |

---

## 📱 Responsive Design

- **Mobile** — Touch-friendly sidebar, single-column layouts, optimized inputs
- **Tablet** — Adaptive two-column grids and collapsible navigation
- **Desktop** — Full multi-pane SaaS experience with persistent sidebar
- **Accessibility** — Semantic HTML, keyboard navigation, ARIA labels, focus states, and sufficient color contrast

---

## 🛡️ Responsible AI Statement

> AI-generated content is intended to assist users and may require human review before use in professional environments. Users remain responsible for verifying the accuracy, completeness, and appropriateness of generated content.

---

## 🔮 Future Improvements

- 🔑 User authentication and profiles
- 👥 Team collaboration and shared workspaces
- 📄 Export to PDF (advanced templates)
- 📅 Calendar integration (Google / Outlook)
- 🎙️ Voice-to-text meeting notes
- 📈 Advanced analytics and productivity insights
- 🌍 Multi-language support

---

## ⚡ Performance & Security

- **Secure API handling** via server-side proxying — no API keys exposed to the browser
- **Environment variables** for all secrets and configuration
- **Input validation** with schema-based checks (Zod)
- **Robust error handling** with user-friendly messages and rate-limit awareness
- **Optimized performance** — code splitting, lazy loading, and responsive assets

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. **Fork** the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m "Add amazing feature"`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a **Pull Request**

Please follow the existing code style and include relevant tests where applicable.

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for more information.

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/Phindile-T)

---

## 🙏 Acknowledgements

- [OpenAI](https://openai.com) — for the language models powering the assistant
- [React](https://react.dev) — for the UI framework
- [Next.js](https://nextjs.org) — for the application framework
- [Tailwind CSS](https://tailwindcss.com) — for the styling system
- The wider **open-source community** — for the countless libraries that make projects like this possible

---

<p align="center">Made with ❤️ to help teams work smarter, not harder.</p>
