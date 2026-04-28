# Career Relocation Planner 🌍

An AI-powered full stack web application that helps professionals evaluate and plan international career relocation opportunities with realistic, data-driven guidance.

This platform enables users to create an account, generate personalized relocation plans, save them securely, and revisit them anytime. It combines deterministic backend logic for critical decision-making with AI-generated personalized recommendations.

---

## 🚀 Features

* 🔐 Secure user authentication using JWT
* 🌐 Personalized relocation plans based on:

  * Current country
  * Destination country
  * Target role
  * Salary expectations
  * Timeline
  * Sponsorship / work authorization needs
* 📊 Feasibility scoring (High / Medium / Low)
* ⚙️ Deterministic checks for:

  * Salary threshold conflicts
  * Timeline feasibility
  * Missing market data
* 🤖 AI-generated personalized action roadmap
* 💾 Save plans and revisit later
* 📱 API-first architecture ready for future mobile apps

---

## 🛠 Tech Stack

### Frontend

* Next.js
* TypeScript
* Tailwind CSS

### Backend

* Node.js
* Next.js API Routes

### Database

* PostgreSQL
* Prisma

### Authentication

* JWT

### AI Integration

* Google Gemini API

---

## 📂 Project Structure

```text
/app
  /api
  /login
  /register
  /dashboard
  /new-plan

/lib
/data
/prisma
/components
README.md
DECISIONS.md
Dockerfile
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone <your-github-repo-url>
cd career-relocation-planner
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Setup Environment Variables

Create `.env` file:

```env
DATABASE_URL=
JWT_SECRET=
GEMINI_API_KEY=
```

### 4️⃣ Run Prisma Migration

```bash
npx prisma migrate dev
```

### 5️⃣ Start Development Server

```bash
npm run dev
```

---

## 🌍 Example Use Cases

### Scenario A

India → Germany → Senior Backend Engineer

### Scenario B

India → United Kingdom → Product Manager

Each scenario generates a unique personalized roadmap.

---

## 🧠 Engineering Highlights

* Deterministic logic used for correctness-sensitive decisions
* AI used only for summaries and action planning
* Scalable architecture for adding new countries via data config
* Production-style API structure
* Secure authentication flow

---

## 🚀 Deployment

* Frontend: Vercel
* Database: Railway

---

## 📌 Future Improvements

* Async queue processing for high traffic
* Email notifications
* Resume analyzer integration
* Country comparison dashboard
* Admin analytics panel

---

## 👨‍💻 Author

Built by Tanmoy Sarkar as a Full Stack + AI Engineering project.

---

## ⭐ If you found this useful

Give the repo a star ⭐
