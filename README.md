
# 🍽️ Servd — An AI Recipe Platform

**Full Stack React Project (An AI Recipe Platform)**  
(Built with **Next.js, Tailwind CSS, Strapi, Neon DB, Shadcn UI, Clerk, and Arcjet**)

Servd  is a modern, full stack AI-powered recipe and pantry management platform that helps users discover recipes, manage pantry items, and cook smarter using artificial intelligence. The platform integrates secure authentication, scalable database, and production-grade security.

---

## 🌐 Live Preview

🚀 **Live Preview:**  

[Servd-AI_Recipe_Platform-Live Demo](https://servd-ai-recipe-platform.vercel.app)



## 📸 Screenshots


<img width="1894" height="875" alt="Screenshot 2026-02-05 223059" src="https://github.com/user-attachments/assets/cc046cf9-17ab-48e9-a966-3ae488bbd79b" />



---

## 🚀 Features

### 🤖 AI-Powered Recipes
- AI-based recipe generation
- Recipe suggestions based on pantry ingredients
- Smart ingredient substitutions
- Personalized cooking recommendations

### 🧺 Pantry Management
- Add, update, and delete pantry items
- Track ingredient availability
- Smart usage suggestions
- Reduce food waste with AI insights

### 📌 Recipe Management
- Save and bookmark favorite recipes
- Search and filter recipes
- View detailed cooking instructions
- Categorized recipe browsing

### 🔐 Authentication (Clerk)
- Secure authentication using **Clerk**
- Email / social login support
- Protected routes and user sessions
- User-specific pantry and saved recipes

### 🛡️ Security (Arcjet)
- Bot protection
- Rate limiting
- Request shielding
- Production-grade API security

### 🎨 Modern UI/UX
- Responsive design
- Tailwind CSS + Shadcn UI components
- Smooth animations & loading states
- Mobile-friendly layout

---

## 🛠️ Tech Stack

### Frontend
- Next.js (App Router)
- React
- Tailwind CSS
- Shadcn UI
- Lucide Icons

### Backend & CMS
- Strapi (Headless CMS)
- Next.js Server Actions
- REST / API Integration

### Database
- Neon DB (PostgreSQL)

### Authentication
- Clerk

### Security
- Arcjet

### AI
- Gemini AI

---

## 📁 Project Structure

```
Servd-AI_Recipe_Platform/
├── frontend/                # Next.js Frontend (App Router)
│   ├── app/                 # Next.js app directory
│   ├── components/          # Reusable UI components
│   ├── actions/             # Server actions
│   ├── hooks/               # Custom React hooks
│   ├── lib/                 # Utilities & helpers
│   ├── public/              # Static assets
│   ├── styles/              # Global styles
│   ├── .env.example         # Frontend env variables
│   └── package.json         # Frontend dependencies
│
├── backend/                 # Strapi Backend (Headless CMS)
│   ├── config/              # Strapi configuration
│   ├── database/            # Migrations & DB setup
│   ├── src/
│   │   └── api/             # Strapi APIs
│   │       ├── recipe/      # Recipe content type & logic
│   │       ├── pantry-item/ # Pantry items API
│   │       ├── saved-recipe/# Saved recipes API
│   │       └── user/        # User-related APIs
│   ├── .env.example         # Backend env variables
│   └── README.md            # Backend-specific README
│
├── screenshots/             # Project screenshots
└── README.md                # Main project README

```

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/devansh934/Servd-AI_Recipe_Platform.git
cd Servd-AI_Recipe_Platform
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_APP_URL=http://localhost:3000

# Strapi
STRAPI_API_URL=your_strapi_url
STRAPI_API_TOKEN=your_strapi_token

# Neon DB
DATABASE_URL=your_neon_database_url

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up


# Arcjet
ARCJET_KEY=your_arcjet_key

# AI
GEMINI_API_KEY=your_gemini_api_key

# Unsplash Key
UNSPLASH_ACCESS_KEY=your_unsplash_api_key

```

---

### 4️⃣ Run the App

```bash
npm run dev
```

Open: http://localhost:3000

---

## 🧪 Scripts

```bash
npm run dev       # Start development server
npm run build     # Build for production
npm run start     # Start production server
npm run lint      # Run ESLint
```

---

## 🎯 Resume / Portfolio Highlights

- Built a full stack AI-powered recipe platform using Next.js and Strapi
- Integrated Neon PostgreSQL for scalable cloud database
- Implemented secure authentication with Clerk
- Added production-grade security using Arcjet
- Designed modern UI with Tailwind CSS and Shadcn UI
- Developed AI-powered recipe generation and pantry intelligence
- Implemented user-specific saved recipes and pantry management

---

## 🚀 Deployment

Recommended deployment setup:

- **Frontend:** Vercel  
- **Backend CMS:** Strapi Cloud  
- **Database:** Neon DB  
- **Auth:** Clerk  
- **Security:** Arcjet  

---

## 🤝 Contributing

Contributions are welcome !

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Open a Pull Request  

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Devansh Patel**  
GitHub: https://github.com/devansh934  

---

⭐ If you like this project, don’t forget to give it a star!
