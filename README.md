# 🎁 GiftAI — Your AI Powered Gift Discovery Companion

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Powered by Gemini](https://img.shields.io/badge/AI-Gemini%201.5%20Flash-blueviolet)](https://deepmind.google/technologies/gemini/)
[![Framework: React](https://img.shields.io/badge/Framework-React%2018-blue)](https://react.dev/)
[![Styling: Tailwind](https://img.shields.io/badge/Styling-Tailwind%20CSS-38b2ac)](https://tailwindcss.com/)

**GiftAI** is a premium, AI-driven platform designed to take the stress out of gift-giving. By combining the reasoning power of **Google Gemini** with real-time commerce data from **Amazon**, GiftAI finds the perfect, most thoughtful gifts for your loved ones in seconds.

---

## 🧩 The Problem It Solves

Gift-giving is often a source of "decision paralysis" and anxiety. GiftAI addresses several key pain points:

### 1. Decision Paralysis
Most people spend hours scrolling through generic "Gift Guides for Men/Women" that don't actually fit the recipient. GiftAI replaces endless scrolling with **curated reasoning**, suggesting items that match a person's soul, not just a category.

### 2. The "Impersonal" Gift
Traditional e-commerce filters are rigid (Price, Category, Rating). GiftAI uses **Natural Language Understanding** to bridge the gap between a vague personality trait (e.g., *"they love quiet mornings and mechanical watches"*) and a physical product.

### 3. Outdated Recommendations
Generic blog posts often link to discontinued products. By integrating with the **live Amazon API**, we ensure every recommendation is currently in stock, priced accurately, and ready for Prime delivery.

### 4. The Message Mystery
Finding the gift is only half the battle. GiftAI's **Soulful Message Generator** solves the "blank card" problem by drafting heartfelt, personalized notes that explain the thought behind the gift.

---

## 💡 Practical Use Cases

- **Milestone Birthdays**: Find a gift that reflects a decade of growth and specific hobbies.
- **Relatable Anniversaries**: Discover something that celebrates a shared interest or a unique personality trait of your partner.
- **The "Hard to Buy For" Person**: Use AI to brainstorm niche interests that you might have overlooked.
- **Last-Minute Gifting**: Quickly identify high-rated Prime-eligible items that still feel deeply personal rather than rushed.

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
