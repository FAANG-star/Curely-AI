# 🏥 Curely - Your AI Medical Companion

<div align="center">

![Curely Banner](https://img.shields.io/badge/Healthcare-AI_Powered-ff00ff?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-15.5.5-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-blue?style=for-the-badge&logo=typescript)

**Healthcare that actually listens! 🎧**

_Get 24/7 medical advice from AI doctors who won't judge your midnight pizza choices_

</div>

---

## 🌟 What is Curely?

Curely is a next-generation AI-powered medical consultation platform that brings healthcare into the 21st century. Forget waiting rooms and awkward small talk—just talk to an AI specialist who's always available, always attentive, and never judges your lifestyle choices! 🤖💙

### Why Curely?

- 🕐 **24/7 Availability** - Your AI doctor never sleeps (literally!)
- 🎤 **Voice-First Interface** - Just talk, no typing required
- 🧠 **Specialist AI Doctors** - Cardiologists, Neurologists, and more
- 📊 **Beautiful Reports** - Medical reports that actually look good
- 🔒 **Fort Knox Security** - Your secrets are safe with us
- 🎯 **No Judgment Zone** - We don't judge your 3 AM health concerns

---

## ✨ Features

### 🗣️ Voice Consultations

Talk naturally with specialized AI medical agents. No typing, no forms—just conversation!

### 🤖 Specialized AI Doctors

- **Cardiologist AI** - Heart health expert
- **Neurologist AI** - Brain and nervous system specialist
- **Dermatologist AI** - Skin care professional
- **General Physician AI** - Your all-around health buddy
- And many more!

### 📋 Smart Medical Reports

Get beautifully designed medical reports with:

- **PDF Export** - Download and share easily (Working! ✅)
- **Share Functionality** - Send to your doctor or save for records (Working! ✅)
- **Detailed Analysis** - Chief complaints, symptoms, duration, severity
- **Actionable Recommendations** - Clear next steps for your health

### 🎨 Premium UI/UX

- **Vibrant Gradients** - Eye-catching, modern design
- **Smooth Animations** - Powered by Framer Motion
- **Responsive Design** - Works flawlessly on all devices
- **Humorous Copy** - Health care with a smile 😊

---

## 🚀 Quick Start

### Prerequisites

- **Node.js** 18+ installed
- **npm** or **yarn** package manager
- **Git** for version control

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/FAANG-star/Curely-AI.git
   cd Curely-AI
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env.local` file:

   ```env
   # Clerk Authentication
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key

   # Database (Neon)
   DATABASE_URL=your_neon_database_url

   # OpenAI/OpenRouter
   OPENROUTER_API_KEY=your_openrouter_api_key

   # VAPI (Voice API)
   NEXT_PUBLIC_VAPI_API_KEY=your_vapi_api_key
   ```

4. **Set up the database**

   ```bash
   npm run db:push
   ```

5. **Run the development server**

   ```bash
   npm run dev
   ```

6. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000) 🎉

---

## 🏗️ Tech Stack

### Frontend

- **Next.js 15.5.5** - React framework with App Router
- **React 19.2.0** - UI library
- **TypeScript 5.9.3** - Type-safe JavaScript
- **Tailwind CSS 4.1.14** - Utility-first CSS
- **Framer Motion 12.23.24** - Smooth animations
- **Radix UI** - Accessible components

### Backend

- **Next.js API Routes** - Serverless functions
- **Drizzle ORM** - TypeScript-first ORM
- **Neon PostgreSQL** - Serverless database

### AI & Voice

- **OpenAI GPT-4** - Medical AI intelligence
- **VAPI** - Voice consultation API
- **OpenRouter** - AI model routing

### Authentication & PDF

- **Clerk** - User authentication
- **jsPDF** - PDF generation ✨ NEW!
- **html2canvas** - HTML to PDF conversion ✨ NEW!

---

## 📁 Project Structure

```
Curely-AI/
├── app/
│   ├── (auth)/               # Auth pages (sign-in, sign-up)
│   ├── (routes)/dashboard/   # Main dashboard
│   │   ├── _components/      # Dashboard components
│   │   │   ├── ViewReportDialogue.tsx  ✨ ENHANCED
│   │   │   ├── AddNewSessionDialog.tsx
│   │   │   ├── HistoryList.tsx
│   │   │   └── DoctorsAgentList.tsx
│   │   ├── medical-agent/[sessionId]/  # Voice consultation
│   │   ├── billing/
│   │   └── history/
│   ├── api/                  # API routes
│   │   ├── medical-report/   # Report generation
│   │   ├── session-chat/     # Session management
│   │   └── suggest-doctors/  # AI recommendations
│   ├── globals.css           ✨ ENHANCED
│   ├── page.tsx              ✨ ENHANCED (humorous!)
│   └── provider.tsx
├── components/
│   ├── ui/                   # Reusable UI components
│   └── ErrorBoundary.tsx     # Error handling
├── config/                   # Configuration
│   ├── db.tsx
│   ├── OpenAiModel.tsx
│   └── schema.tsx
└── package.json
```

---

## 🎯 Key Features (In Detail)

### 1. Working PDF Export! 🎨

- **High-quality PDF generation** using jsPDF & html2canvas
- **Beautiful formatting** with proper layout
- **Automatic download** with smart naming
- **Toast notifications** for user feedback

### 2. Working Share Functionality! 🚀

- **Native Web Share API** for modern browsers
- **Fallback to clipboard** for older browsers
- **Toast notifications** for feedback
- **Share text includes** report details and link

### 3. Premium UI with Humor 😄

- **Funny, engaging copy** throughout the app
- **Emoji usage** for personality
- **Vibrant gradients** and colors
- **Smooth animations** on everything
- **Responsive design** that works on all screens

### 4. Medical AI Intelligence 🧠

- **OpenAI GPT-4** powered consultations
- **Specialized AI doctors** for different health areas
- **Voice conversations** with real-time transcription
- **Smart recommendations** based on symptoms

---

## 🎨 What's New?

### ViewReportDialogue Enhancements

- ✅ **Working PDF Export** - Actually generates PDFs now!
- ✅ **Working Share Button** - Uses Web Share API
- ✅ **Vibrant Colors** - Premium gradients everywhere
- ✅ **Humorous Text** - "Medicine Cabinet 💊" instead of "Current Medications"
- ✅ **Smooth Animations** - Framer Motion throughout
- ✅ **Fully Responsive** - Perfect on mobile, tablet, desktop
- ✅ **Text Truncation** - No more overflow issues

### Landing Page Updates

- ✅ **Funny Hero** - "Your Personal AI Doctor (Who Never Sleeps!)"
- ✅ **Engaging Copy** - Healthcare with personality
- ✅ **Better Features** - "Fort Knox Secure 🔒" and more
- ✅ **Animated Gradients** - Moving backgrounds

### Dashboard Improvements

- ✅ **Humorous Headings** - "Your Health Hub 🏥✨"
- ✅ **Better Empty States** - "Nothing here... yet! 🌱"
- ✅ **Engaging Descriptions** - Fun, readable copy

---

## 🐛 Known Issues & Solutions

### PDF Export Issues

```bash
# If PDF export doesn't work, reinstall:
npm install jspdf html2canvas --force
```

### Database Connection

```bash
# Verify your DATABASE_URL in .env.local
# Then push schema:
npx drizzle-kit push
```

---

## 🚀 Deployment

### Vercel (Recommended)

1. Push to GitHub
2. Import to Vercel
3. Add environment variables
4. Deploy!

```bash
vercel --prod
```

---

## 🤝 Contributing

1. Fork the repo
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Open Pull Request

---

## 📝 License

MIT License - see LICENSE file

---

## 👥 Team

Built with ❤️ by [FAANG-star](https://github.com/FAANG-star)
