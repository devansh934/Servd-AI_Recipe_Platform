🍽️ Servd — An AI Recipe Platform
Built with Next.js, Tailwind CSS, Strapi, Neon DB, Shadcn UI, Clerk, and Arcjet

Servd AI is a modern, full stack AI-powered recipe and pantry management platform that helps users discover recipes, manage pantry items, and cook smarter using artificial intelligence. The platform integrates secure authentication, scalable database, and production-grade security.

🌐 Live Preview

🚀 Live Demo:
👉 Add your deployed link here (Vercel / Netlify)

https://your-live-demo-link.vercel.app

📸 Screenshots

Add screenshots here for better presentation.

Create a folder named screenshots/ in your project root and add images like:

screenshots/
  ├── home.png
  ├── pantry.png
  ├── ai-recipe.png
  ├── saved-recipes.png
  └── auth.png


Then reference them like this in README:

![Home Page](./screenshots/home.png)
![Pantry Dashboard](./screenshots/pantry.png)
![AI Recipe Generator](./screenshots/ai-recipe.png)
![Saved Recipes](./screenshots/saved-recipes.png)
![Authentication](./screenshots/auth.png)

🚀 Features
🤖 AI-Powered Recipes

AI-based recipe generation

Recipe suggestions based on pantry ingredients

Smart ingredient substitutions

Personalized cooking recommendations

🧺 Pantry Management

Add, update, and delete pantry items

Track ingredient availability

Smart usage suggestions

Reduce food waste with AI insights

📌 Recipe Management

Save and bookmark favorite recipes

Search and filter recipes

View detailed cooking instructions

Categorized recipe browsing

🔐 Authentication (Clerk)

Secure authentication using Clerk

Email / social login support

Protected routes and user sessions

User-specific pantry and saved recipes

🛡️ Security (Arcjet)

Bot protection

Rate limiting

Request shielding

Production-grade API security

🎨 Modern UI/UX

Responsive design

Tailwind CSS + Shadcn UI components

Smooth animations & loading states

Mobile-friendly layout

🛠️ Tech Stack
Frontend

Next.js (App Router)

React

Tailwind CSS

Shadcn UI

Lucide Icons

Backend & CMS

Strapi (Headless CMS)

Next.js Server Actions

REST / API Integration

Database

Neon DB (PostgreSQL)

Authentication

Clerk

Security

Arcjet

AI

AI / LLM-based recipe generation

📁 Project Structure
Servd-AI_Recipe_Platform/
├── app/                # Next.js App Router
├── components/         # Reusable UI components
├── actions/            # Server actions
├── hooks/              # Custom React hooks
├── lib/                # Utilities & helpers
├── public/             # Static assets
├── screenshots/        # Project screenshots
├── styles/             # Global styles
├── .env.example        # Environment variables template
└── README.md

⚙️ Getting Started
1️⃣ Clone the Repository
git clone https://github.com/devansh934/Servd-AI_Recipe_Platform.git
cd Servd-AI_Recipe_Platform

2️⃣ Install Dependencies
npm install

3️⃣ Environment Variables

Create a .env.local file:

NEXT_PUBLIC_APP_URL=http://localhost:3000

# Strapi
STRAPI_API_URL=your_strapi_url
STRAPI_API_TOKEN=your_strapi_token

# Neon DB
DATABASE_URL=your_neon_database_url

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Arcjet
ARCJET_KEY=your_arcjet_key

# AI
OPENAI_API_KEY=your_openai_api_key

4️⃣ Run the App
npm run dev


Open: http://localhost:3000

🧪 Scripts
npm run dev       # Start development server
npm run build     # Build for production
npm run start     # Start production server
npm run lint      # Run ESLint

🎯 Resume / Portfolio Highlights

Built a full stack AI-powered recipe platform using Next.js and Strapi

Integrated Neon PostgreSQL for scalable cloud database

Implemented secure authentication with Clerk

Added production-grade security using Arcjet

Designed modern UI with Tailwind CSS and Shadcn UI

Developed AI-powered recipe generation and pantry intelligence

Implemented user-specific saved recipes and pantry management

🚀 Deployment

Recommended deployment setup:

Frontend: Vercel

Backend CMS: Strapi Cloud / Render / Railway

Database: Neon DB

Auth: Clerk

Security: Arcjet

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch

Commit your changes

Open a Pull Request

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Devansh Patel
GitHub: https://github.com/devansh934

⭐ If you like this project, don’t forget to give it a star!

If you want, I can now:
