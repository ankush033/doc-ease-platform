🩺 Doc Ease Platform

A production-ready full-stack Doctor Appointment Booking Platform built using modern web technologies.

This application enables patients to book appointments with doctors while allowing doctors to manage schedules, appointments, and consultation records efficiently.

🌐 Live Application:
https://doc-ease-platform.vercel.app

📂 Source Code:
https://github.com/ankush033/doc-ease-platform

✨ Key Highlights

✔ Role-Based Authentication (Doctor / Patient)
✔ Credit-Based Booking System
✔ Real-Time Appointment Management
✔ Secure Database Transactions
✔ Fully Deployed on Vercel
✔ Clean & Scalable Code Architecture

🧠 Problem It Solves

Managing medical appointments manually can be inefficient and error-prone.
Doc Ease Platform digitizes appointment booking with a structured credit-based system ensuring secure transactions and organized scheduling.

🏗 System Architecture

Frontend → Next.js 14 (App Router)
Backend Logic → Server Actions
Database → PostgreSQL
ORM → Prisma
Authentication → Clerk
Deployment → Vercel

The application follows a clean separation of concerns with modular folders for actions, components, and database logic.

🔐 Authentication & Authorization

• Clerk-based secure authentication
• Role-based dashboard rendering
• Protected routes
• Session-based access control

👨‍⚕️ Doctor Capabilities

• Set and manage availability
• View scheduled appointments
• Add consultation notes
• Mark appointments as completed
• Cancel appointments
• Credit tracking system

👤 Patient Capabilities

• Browse verified doctors
• Book appointments using credits
• Cancel bookings
• Automatic credit refund on cancellation

💳 Credit-Based Booking System

The platform uses a custom-built credit transaction model:

• Credits deducted during booking
• Credits refunded upon cancellation
• Atomic database transactions using Prisma
• Data consistency ensured via transactional queries

🗄 Database Management

Prisma ORM is used for:

• Schema modeling
• Database migrations
• Relationship management
• Transaction handling

Doctor verification is handled via Prisma Studio for demonstration purposes.
In a production-scale system, this would be replaced by a dedicated Admin Panel.

⚙️ Local Setup Instructions

Clone the repository:

git clone https://github.com/ankush033/doc-ease-platform.git

cd doc-ease-platform

Install dependencies:

npm install

Create a .env file and add:

DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

Run database migration:

npx prisma migrate dev

Start development server:

npm run dev

🚀 Deployment

The project is successfully deployed on Vercel:

https://doc-ease-platform.vercel.app

📈 Future Enhancements

• Admin dashboard for automated doctor verification
• Stripe payment gateway integration
• Email & SMS notifications
• Appointment reminders
• Analytics dashboard
• Multi-role expansion (Admin role)

🎯 Project Status

✔ Fully Functional MVP
✔ End-to-End Feature Complete
✔ Database Integrated
✔ Authentication Integrated
✔ Deployed & Live

👨‍💻 Author

Ankush
GitHub: https://github.com/ankush033

Live Project: https://doc-ease-platform.vercel.app

Built with ❤️ by Ankush
