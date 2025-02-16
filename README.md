# AI Career Coach

## 🚀 Overview
An AI-powered career coach that helps users enhance their professional journey with features like AI-driven resume building, mock interview preparation, salary insights, and intelligent cover letter generation. The platform is designed with a **modern, responsive UI** and leverages **LLM technology** to provide tailored career guidance.

## 🔥 Features
- **User Onboarding & Dashboard**
  - Interactive dashboard displaying in-demand skills and salary trends (updated weekly).
- **AI-Powered Resume Builder**
  - Generates ATS-optimized resumes based on user industry & skills.
  - Fully customizable markdown-based resume generation.
  - Option to download resumes as PDFs.
- **Mock Interview Preparation**
  - AI-generated role-specific interview questions.
  - Performance tracking with AI-generated improvement tips.
- **Cover Letter Generator**
  - Analyzes job descriptions to generate personalized cover letters.
- **Modern UI/UX**
  - Fully responsive design using **Next.js** and **ShadCN UI**.
  - Engaging scroll animations & intuitive navigation.

## 🛠️ Tech Stack
- **Frontend:** React 19, Next.js 15, Tailwind CSS, ShadCN UI
- **Backend:** NeonDB, Prisma, FastAPI
- **Authentication:** Clerk
- **AI Integration:** Gemini API
- **Task Automation:** Inngest
- **Deployment:** [Specify platform, e.g., Vercel/AWS]

## 📌 Setup & Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Shrashti04/AI-Career-Coach.git
   cd AI-Career-Coach
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in `.env.local`:
   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-key
   CLERK_SECRET_KEY=your-key
   DATABASE_URL=your-database-url
   GEMINI_API_KEY=your-key
   INNGEST_API_KEY=your-key
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📂 Project Structure
```
├── components/        # Reusable UI components
├── pages/             # Next.js pages & routes
├── api/               # API handlers
├── utils/             # Helper functions
├── styles/            # Global styles
├── prisma/            # Database models
└── public/            # Static assets
```

## 🛠️ Key Functionalities
### 1. **User Authentication & Onboarding**
- Custom **login/signup** page using Clerk.
- Stores user data in **NeonDB** using **Prisma**.

### 2. **AI-Powered Insights & Resume Builder**
- Integrates with **Gemini API** to generate career insights.
- AI-generated **ATS-optimized resume** with markdown support.
- PDF export functionality.

### 3. **Mock Interviews & Performance Tracking**
- Generates AI-based **mock interview questions**.
- Tracks performance over time and provides **improvement tips**.

### 4. **Cover Letter Generator**
- Analyzes **job descriptions** to create **personalized cover letters**.

### 5. **Automated Weekly Insights**
- Uses **Inngest** to **fetch and update industry trends weekly**.

## 🚀 Deployment
1. Build the project:
   ```bash
   npm run build
   ```
2. Deploy using **Vercel/AWS** (update deployment instructions based on your platform).

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit PRs.
