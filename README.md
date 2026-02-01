# 🎁 GiftAI — Your AI Powered Gift Discovery Companion

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Powered by Gemini](https://img.shields.io/badge/AI-Gemini%201.5%20Flash-blueviolet)](https://deepmind.google/technologies/gemini/)
[![Framework: React](https://img.shields.io/badge/Framework-React%2018-blue)](https://react.dev/)
[![Styling: Tailwind](https://img.shields.io/badge/Styling-Tailwind%20CSS-38b2ac)](https://tailwindcss.com/)

**GiftAI** is a premium, AI-driven platform designed to take the stress out of gift-giving. By combining the reasoning power of **Google Gemini** with real-time commerce data from **Amazon**, GiftAI finds the perfect, most thoughtful gifts for your loved ones in seconds.

---

## ✨ Key Features

- 🤖 **Dynamic AI Reasoning**: Unlike static lists, our AI analyzes the recipient's personality, interests, and the occasion to suggest truly meaningful gifts.
- 🛒 **Real-Time Amazon Integration**: No outdated products. We fetch live data from Amazon India including current prices, ratings, and Prime eligibility.
- 📝 **Heartfelt Message Generator**: Stuck on what to write? GiftAI crafts personalized, soulful messages to accompany your gift.
- 🎨 **Premium Visual Experience**: A sleek, modern dashboard built with Glassmorphism, smooth Framer Motion animations, and full Dark Mode support.
- 📂 **Collaborative Wishlists**: Save your discoveries to a "Cozy Gift Bag" and share them with friends or family.

---

## 🛠️ Tech Stack

### Frontend
- **React 18** (TypeScript)
- **Vite** (Build Tool)
- **Tailwind CSS** (Styling)
- **Framer Motion** (Animations)
- **Radix UI / Shadcn** (Accessible Components)
- **TanStack Query** (Server State)

### Backend
- **Node.js & Express**
- **Drizzle ORM**
- **PostgreSQL** (Neon Serverless)
- **Google Gemini 1.5 Flash API** (AI Engine)
- **RapidAPI** (Real-Time Amazon Data)

---

## 🚀 How It Works

1. **The Profile**: Tell us who you're buying for—their age, relationship, interests (e.g., "Enjoys minimal tech and birdwatching"), and your budget.
2. **AI Analysis**: Our Gemini-powered engine brainstorms a set of curated gift categories and specific search terms that match the recipient's soul, not just a keyword.
3. **Live Search**: The system performs sub-second searches across Amazon's catalog for those specific suggestions.
4. **The Result**: You get a tailored selection of available products, complete with AI reasoning on *why* each item is a perfect match.

---

## ⚙️ Setup & Installation

### Prerequisites
- Node.js (v18+)
- PostgreSQL Database (Local or Neon.tech)
- Google Gemini API Key
- RapidAPI Key (Amazon Search API)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/oki-dokii/Gift-AI.git
   cd Gift-AI
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Variables**
   Create a `.env` file in the root directory:
   ```env
   DATABASE_URL=postgresql://user:password@host/dbname
   GEMINI_API_KEY=your_gemini_key_here
   RAPIDAPI_KEY=your_rapidapi_key_here
   ```

4. **Prepare the Database**
   ```bash
   npm run db:push
   ```

5. **Start the Development Server**
   ```bash
   npm run dev
   ```

---

## 📸 Preview

*Check out the `attached_assets` folder for UI screenshots and design guidelines.*

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">Made with ❤️ for thoughtful givers everywhere.</p>
