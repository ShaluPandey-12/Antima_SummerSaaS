# Antima_SummerSaaS
<div align="center">

<img src="https://img.shields.io/badge/अंतिमा-Antima-D4AF37?style=for-the-badge&labelColor=8B4513&color=D4AF37" alt="Antima" width="200"/>

# 🪔 Antima — *The Last Journey Platform*

### *A compassionate AI-powered SaaS platform for end-of-life rituals, grief support & family guidance*

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Now-D4AF37?style=for-the-badge&logoColor=white)](https://antima-summer-saa-2h08i3eiw-shalupandey-12s-projects.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-ShaluPandey--12-181717?style=for-the-badge&logo=github)](https://github.com/ShaluPandey-12/Antima_SummerSaaS)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel)](https://vercel.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-99%25-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)

---

> *"Honoring life's final chapter with dignity, technology, and compassion."*

</div>

---

---

## 🌸 About the Project

**Antima** (अंतिमा) means *"the last"* in Sanskrit — a platform built to support families during one of life's most difficult moments.

This SaaS platform combines **AI technology** with **cultural sensitivity** to provide:
- Step-by-step guidance for funeral rituals across **7 religions**
- AI-powered grief counseling and emotional support
- Hospital coordination and documentation management
- A marketplace for ritual essentials
- Multi-language, multi-region support across **all of India**

Built as part of **Summer SaaS 2025** challenge.

---

## 🚀 Live Demo

<div align="center">

### 👉 [https://antima-summer-saa-2h08i3eiw-shalupandey-12s-projects.vercel.app/](https://antima-summer-saa-2h08i3eiw-shalupandey-12s-projects.vercel.app/)

</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🤖 **AI Ritual Guide** | Step-by-step ritual guidance powered by Google Gemini AI |
| 🕌 **Multi-Religion Support** | Hindu, Muslim, Christian, Sikh, Jain, Buddhist & more |
| 🗺️ **Region-Based Guidance** | Covers North, South, East, West & Central India |
| 💬 **Grief Counseling** | AI-powered emotional support & grief chat |
| 🏥 **Hospital Screen** | Medical documentation & hospital coordination |
| 🛒 **Marketplace** | Ritual essentials & products marketplace |
| 📅 **Events & Ceremonies** | Schedule and manage post-funeral ceremonies |
| 💰 **Financial Planning** | Funeral expense management & financial guidance |
| 🌐 **Multi-Language** | Support for regional Indian languages |
| 🔐 **Firebase Auth** | Secure login & signup with Firebase |
| 📱 **Fully Responsive** | Mobile-first design with smooth animations |

---

## 🛠 Tech Stack

<div align="center">

![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Google Gemini](https://img.shields.io/badge/Google_Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-EF008F?style=for-the-badge&logo=framer&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

| Layer | Technology |
|---|---|
| **Frontend** | React 19, TypeScript, Vite |
| **Styling** | Tailwind CSS v4, Framer Motion |
| **Backend** | Express.js, Node.js, TypeScript |
| **Database** | Firebase Firestore |
| **Auth** | Firebase Authentication |
| **AI** | Google Gemini AI (`@google/genai`) |
| **Icons** | Lucide React |
| **Charts** | Recharts |
| **Deployment** | Vercel |

---

## 🏁 Getting Started

### Prerequisites

- Node.js `v18+`
- npm or yarn
- Firebase project setup
- Google Gemini API key

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/ShaluPandey-12/Antima_SummerSaaS.git

# 2. Navigate to project folder
cd Antima_SummerSaaS/Antima-yatra_summer-_saas_26621-main

# 3. Install dependencies
npm install

# 4. Create environment file
cp .env.example .env
```

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
GEMINI_API_KEY=your_gemini_api_key
```

### Run Locally

```bash
# Development mode
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

---

## 📁 Project Structure

```
src/
├── components/
│   ├── LandingPage.tsx       # Landing page with hero section
│   ├── AuthScreen.tsx        # Login & Signup screen
│   ├── HomeScreen.tsx        # Main dashboard with AI chat
│   ├── RitualScreen.tsx      # Religion-based ritual guide
│   ├── CommunicateScreen.tsx # Family communication tools
│   ├── MarketplaceScreen.tsx # Products marketplace
│   ├── EventsScreen.tsx      # Ceremony scheduling
│   ├── FinancialScreen.tsx   # Expense management
│   ├── GriefScreen.tsx       # AI grief counseling
│   ├── AccountScreen.tsx     # User profile & settings
│   ├── FirebaseProvider.tsx  # Firebase auth context
│   ├── Layout.tsx            # Navbar, Footer, FAB
│   └── hospital/             # Hospital coordination module
├── services/
│   ├── aiService.ts          # Google Gemini AI integration
│   └── firestoreService.ts   # Firebase Firestore operations
├── lib/                      # Utility functions
├── data.ts                   # Religions, regions, experts data
├── App.tsx                   # Main app with routing
└── main.tsx                  # Entry point
```

---

## 🌍 Supported Religions & Regions

**Religions:** Hindu • Muslim • Christian • Sikh • Jain • Buddhist • Other

**Regions:** North India • South India • East India • West India • Central India

---

## 👩‍💻 Author

<div align="center">

**Shalu Pandey**

[![Portfolio](https://img.shields.io/badge/Portfolio-shalupandey--12.github.io-D4AF37?style=for-the-badge&logo=github-pages&logoColor=white)](https://shalupandey-12.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shalu-pandey-2b90a9282/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/ShaluPandey-12)

*B.Tech CSE Student @ CMR Engineering College, Hyderabad*
*Smart India Hackathon Finalist | Runner-Up National Project Expo Vishesh 2025*

</div>

---

## 📄 License

This project was built as part of the **Summer SaaS 2025** challenge.

---

<div align="center">

Made with ❤️ and 🪔 by **Shalu Pandey**

⭐ *If you found this helpful, give it a star!* ⭐

</div>
