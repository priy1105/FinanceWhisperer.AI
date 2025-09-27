
# FinanceWhisperer.AI
# 🔥 Full Stack AI Finance Platform 

FinanceWhisperer.AI is a full-stack, AI-powered finance platform designed to provide intelligent financial management. It allows users to track income and expenses, manage budgets, and gain insights into their spending habits through an intuitive interface and powerful analytics.

## Tech Stack 🛠️
Framework: Next.js - JavaScript
Database: Supabase with Prisma
Authentication: Clerk
Styling: Tailwind CSS with Shadcn UI
AI: Google Generative AI (Gemini)
Background Workflows: Inngest
Email: Resend
Security: Arcjet

## Key Features ✨
AI-Powered Insights: Get smart, actionable insights into your spending patterns with AI-powered analytics.   
Receipt Scanning: Automatically extract transaction data from receipts using AI by scanning an image of the receipt.   
Budget Planning: Create and manage budgets with intelligent recommendations, and get alerts when you're approaching your limit.   
Multi-Account Support: Manage all your financial accounts in one centralized location.    
Recurring Transactions: Set up and manage recurring transactions for automated financial tracking.    
Monthly Reports: Receive detailed monthly reports via email, complete with AI-generated insights to help you understand your financial health.    
Secure Authentication: User authentication is handled by Clerk, providing a secure and reliable login experience.     


## Getting Started 🚀
Follow these steps to get the project up and running on your local machine.

## Installation
Clone the repository:

Bash
```
git clone https://github.com/priy1105/financewhisperer.ai.git
cd financewhisperer.ai
code .
```

## Install dependencies:

Bash
```
npm install
```
Set up the database:   
Make sure your PostgreSQL server is running.   
Run the Prisma migrations to create the database schema:   

Bash
```
npx prisma migrate dev
```


### Make sure to create a `.env` file with following variables -

```
# MongoDB Connection
DATABASE_URL="mongodb+srv://<user>:<password>@<cluster-url>/<database-name>?retryWrites=true&w=majority"

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```

### Run the development server:

Bash
```
npm run dev
```

The application will be available at http://localhost:3000.
