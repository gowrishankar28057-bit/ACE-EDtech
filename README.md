<div align="center">

<img src="https://img.shields.io/badge/Platform-AllCollegeEvent-6366f1?style=for-the-badge&logo=globe&logoColor=white" />
<img src="https://img.shields.io/badge/Built%20by-ECLearnix%20Edtech-10b981?style=for-the-badge" />
<img src="https://img.shields.io/badge/Team-NOVACORE-f43f5e?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Active%20Development-facc15?style=for-the-badge" />
<img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" />

<br /><br />

# 🎓 ACE — AllCollegeEvent
### *Discover, Connect, and Compete Across Every Campus*

**ACE** is an AI-powered college event discovery and innovation platform built for students, faculty, and entrepreneurs. From hackathons and cultural fests to research workshops and startup pitches — ACE is the single hub where campus life meets opportunity.

[🌐 Live Demo](#) · [📖 Docs](#) · [🐛 Report Bug](../../issues) · [✨ Request Feature](../../issues)

</div>

---

## 📌 Table of Contents
- [About the Project](#-about-the-project)
- [Core Features](#-core-features)
- [Platform Screens](#-platform-screens)
- [Tech Stack](#-tech-stack)
- [AI & ML Capabilities](#-ai--ml-capabilities)
- [Architecture](#-architecture)
- [Getting Started](#-getting-started)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Team](#-team)
- [License](#-license)

---

## 🚀 About the Project

**AllCollegeEvent (ACE)** was born from a simple but persistent problem: college students across India miss out on life-changing opportunities — hackathons, research fests, innovation challenges, cultural fests — simply because there is no unified, intelligent platform to discover them.

ACE solves this by combining a rich event catalogue with AI-driven personalization, competitive tools, and a career intelligence engine — all in one seamless web experience.

Built under **ECLearnix Edtech Pvt. Ltd.** and developed by **Team NOVACORE**, ACE targets the 40M+ college students in India who currently rely on fragmented WhatsApp forwards, noticeboard posters, and word-of-mouth to find events worth attending.

### The Problem We're Solving

| Pain Point | How ACE Solves It |
|---|---|
| Events discovered too late | Real-time listings with deadline alerts |
| No personalization | AI Career DNA analyzer matches events to your profile |
| Scattered hackathon info | Dedicated Hackathon War Room with team-formation tools |
| No innovation recognition | Innovation Arena for project pitching and community voting |
| Study resources siloed | Integrated Study Hub with curated content per domain |
| No single student identity | Role-based profiles for Student, Faculty, and Organizer |

---

## ✨ Core Features

### 🔍 Event Discovery Engine
- **Smart Search & Filter** — Filter by category (Tech, Cultural, Sports, Research, Entrepreneurship), date, college, fee, and mode (online/offline)
- **Bookmarking System** — Save events with one click; receive reminders as deadlines approach
- **Event Detail Pages** — Full breakdowns with eligibility, prizes, registration links, and countdown timer
- **Sort & Rank** — Sort by popularity, deadline urgency, relevance to your Career DNA, or campus proximity

### 🧬 Career DNA Analyzer
- AI module that profiles students based on skills, past participation, academic stream, and goals
- Generates a personalized **Career DNA string** (e.g., `ML-Engineer | IoT-Builder | Research-Oriented`)
- Recommends the top 5 events each week that directly match the student's DNA
- Tracks evolution of Career DNA over time as more events are attended

### 🏆 Hackathon War Room
- Centralized hub for all active and upcoming hackathons — national, international, and campus-level
- **Team Formation Board** — Post team requirements, find co-founders, or join incomplete teams
- **Submission Tracker** — Track your team's submission status, round results, and feedback
- **Problem Statement Library** — Browse past hackathon problems by domain to practice and prepare
- Leaderboard of top-performing student teams across campuses

### 💡 Innovation Arena
- Platform for students to pitch project ideas publicly
- **Community Voting** — Peers, faculty, and industry mentors can upvote, comment, and endorse projects
- **Prototype Showcase** — Upload demo videos, GitHub links, pitch decks, and architecture diagrams
- Monthly featured innovation spotlights published on the platform blog

### 📚 Study Hub
- Curated YouTube playlists, NPTEL lectures, and open-access resources organized by engineering domain
- **Domain Channels** — ECE, CSE, Mechanical, Civil, BioTech, and Management
- **Exam Corner** — GATE, GRE, and placement preparation resources linked directly
- Bookmarkable resources synced with student profile

### 🤖 Zuzu — AI Event Assistant
- Conversational chatbot for natural-language event search
- Ask Zuzu: *"Find me free ML hackathons happening in Chennai next month"*
- Cross-references Career DNA for sharper recommendations
- Available 24/7 via floating chat widget on every page

### 👤 Role-Based Authentication
- **Student** — Discover, register, track, and compete
- **Faculty** — Post departmental events, track student participation, endorse projects
- **Organizer** — Create listings, manage registrations, access analytics dashboards

---

## 🖥️ Platform Screens

ACE is a **multi-page Single Page Application (SPA)** with click-navigated distinct screens:

| Screen | Path | Description |
|---|---|---|
| Landing Page | `/` | Hero with animated background, value proposition, CTA |
| Login / Register | `/login` | Role-based auth with animated vortex background |
| Welcome | `/welcome` | Personalized greeting with Career DNA preview |
| Discover | `/discover` | Main event feed with search, filter, sort, bookmark |
| Event Detail | `/event/:id` | Full event info, registration panel, countdown |
| Career DNA | `/career-dna` | AI analyzer with profile radar chart |
| Hackathon War Room | `/hackathons` | Hackathon hub with team formation board |
| Innovation Arena | `/innovation` | Project pitch and community voting feed |
| Study Hub | `/study` | Curated learning resources by domain |
| Profile | `/profile` | Student dashboard with activity, bookmarks, DNA |

---

## 🛠️ Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)

- **React** — Component-based SPA architecture with hook-based state management
- **Tailwind CSS** — Utility-first styling for responsive, consistent UI
- **Custom SVG Charts** — Lightweight data visualizations without heavy chart libraries
- **CSS Variables** — Theming engine supporting dark/light mode switching
- **Canvas API** — Ambient particle and aurora background effects

### Design System
- **Typography** — `Instrument Serif` (display) + `JetBrains Mono` (code/labels)
- **Palette** — Deep navy `#0f172a` base · Coral `#f43f5e` · Mint `#10b981` accents · Glassmorphism surfaces
- **Motion** — Curtain fade transitions, breathing animations, micro-interactions on all interactive elements

### Backend *(Planned)*
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

- **Node.js + Express** — REST API for event CRUD, user auth, and recommendations
- **MongoDB** — Flexible document store for events, user profiles, and engagement logs
- **JWT Authentication** — Stateless, role-based auth tokens

### AI / ML Layer *(Research Phase)*
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

- **Career DNA Engine** — K-Means + PCA clustering on student interaction vectors
- **Recommendation Engine** — Hybrid KNN + NMF + Neural Network collaborative filtering
- **Engagement Predictor** — Random Forest binary classifier for feed ranking

---

## 🧠 AI & ML Capabilities

### Career DNA Engine
Students are described by six interaction features (category preference shares, bookmark rate, events browsed, engagement rate, average lead time, same-college preference share). Features are **standard-scaled** and reduced via **PCA** before K-Means clustering produces career archetypes refreshed monthly.

### Recommendation System
A hybrid pipeline tested across three models:
- **KNN Collaborative Filtering** — Finds peers with similar event engagement patterns
- **NMF Matrix Factorization** — Decomposes the student-event interaction matrix into latent factors
- **Neural Network Recommender** — Embedding-based deep recommender trained on interaction history

### Engagement Prediction
Supervised binary classifier predicting `Engaged = 1` before recommendations are served. Features include event category, days until event, bookmark status, and historical engagement rate. Random Forest achieved AUC > 0.83 on held-out data.

---

## 🏗️ Architecture
──────────────────────────────────────────────────────┐
│               ACE Frontend (React SPA)               │
│  Landing → Login → Welcome → Discover → Detail       │
│  Career DNA | Hackathon War Room | Innovation Arena  │
│  Study Hub  |  Profile Dashboard  |  Zuzu Chatbot   │
└───────────────────┬──────────────────────────────────┘
│ REST API (JSON)
┌───────────────────▼──────────────────────────────────┐
│            ACE Backend (Node.js + Express)           │
│   Auth Service │ Event Service │ User Service        │
│   Recommendation Service │ Analytics Service        │
└───────────────────┬──────────────────────────────────┘
│
┌───────────▼───────────┐
│      MongoDB Atlas    │
│  Events │ Users │ Logs│
└───────────┬───────────┘
│
┌───────────▼────────────────────┐
│    Python ML Microservice      │
│  Career DNA | Recommender      │
│  Engagement Predictor | NLP    │
└────────────────────────────────┘

---

## ⚙️ Getting Started

### Prerequisites
- Node.js ≥ 18.x
- npm ≥ 9.x
- Git

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/AllCollegeEvent.git
cd AllCollegeEvent

# 2. Install dependencies
cd frontend
npm install

# 3. Start development server
npm run dev
```

App runs at `http://localhost:5173`

### Environment Variables

Create `.env` in `/frontend`:

```env
VITE_API_BASE_URL=http://localhost:3000/api
VITE_ZUZU_API_KEY=your_ai_key_here
```

---

## 🗺️ Roadmap

- [x] Multi-page SPA with click navigation
- [x] Event discovery with search, filter, sort, bookmark
- [x] Role-based login flow
- [x] Career DNA Analyzer (ML prototype)
- [x] Hackathon War Room
- [x] Innovation Arena
- [x] Study Hub
- [x] Zuzu AI chatbot (NLP prototype)
- [ ] Backend REST API (Node.js + Express)
- [ ] MongoDB integration
- [ ] Mobile-responsive PWA
- [ ] Push notifications for deadline reminders
- [ ] Organizer analytics dashboard
- [ ] National college network (1000+ institutions)
- [ ] Mobile app (React Native)

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

### Good First Issues
- Improving mobile responsiveness on the Discover page
- Adding more event categories to the filter sidebar
- Writing unit tests for the Career DNA data layer
- Improving Zuzu's response templates for edge-case queries

---

## 👥 Team

**Team NOVACORE** — Built under ECLearnix Edtech Pvt. Ltd.

| Role | Contribution |
|---|---|
| Platform Architect & Lead Developer | Frontend SPA, AI/ML integration, system design |
| ECLearnix Edtech Pvt. Ltd. | Product vision, institutional partnerships, infrastructure |

> *ACE was shortlisted for the Hackathon 360 4.0 Innovation Challenge (EdTech domain) and is under active incubation at ECLearnix.*

---


---

## 🙏 Acknowledgements

- [React](https://react.dev/) — UI library
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework
- [Google Fonts](https://fonts.google.com/) — Instrument Serif & JetBrains Mono
- [shields.io](https://shields.io/) — Badge generation
- Every college student in India whose missed opportunity made ACE necessary

---

<div align="center">

**Built with purpose by Team NOVACORE | ECLearnix Edtech Pvt. Ltd.**

*"Every opportunity you miss is one you didn't know about. ACE fixes that."*

⭐ Star this repo if ACE helped you find your next big opportunity!

</div>
