## SAHAYK-AI 
An all-in-one solution that enhances customer interactions with automated AI chat, bookings, payments, and lead management. It integrates seamlessly into any website, providing customizable and white-labeled solutions for real-time chat, email marketing, and secure file uploads. Optimize sales and customer engagement with a minimal, modern UI, smart AI, and feature control settings.

## Features
The Automated AI Sales Rep is an all-in-one solution that enhances customer interaction by providing an AI chatbot capable of handling customer inquiries. It simplifies appointment booking by automating scheduling and payment processing, and easily integrates with any website using simple code. Its smart question linking feature enables intelligent question-response matching, ensuring efficient communication. The system supports real-time chat, allowing seamless switching between manual and automated conversations.

With white-labeling options, the interface is fully customizable to match your brand, offering a personalized user experience. It also includes a calendar widget that provides an easy-to-use booking system for scheduling. Secure payment processing is integrated through Stripe, while the email marketing feature simplifies outreach efforts. A financial dashboard helps you track and manage financial performance effortlessly, and the lead management functionality allows you to save visitor data for future marketing efforts.

The platform provides secure authentication with custom login/signup options that include OTP verification. It also supports safe file and image uploads. To boost visibility, the in-built blog is optimized for SEO, while the system's improved architecture ensures better scalability and performance. The minimal UI provides a clean, visually appealing interface that users will find intuitive and easy to navigate.

Additionally, the system includes a built-in FAQ section for addressing common queries, and a light/dark mode toggle to enhance user experience. Feature control settings allow you to manage and configure features, and the ability to restrict features based on subscription plans provides flexibility in offering different levels of service. Overall, this solution is designed to automate and streamline customer interactions while offering customizable features to fit your business needs.

## Environment Variables

Before running the application, set up the environment variables. Rename `.env.example to .env ` and set your own variables.

```bash
mv .env.example .env
nano .env  # (or use any text editor to modify .env)
```

### .env.example

Here is an example of the environment variables needed for the project. Replace the placeholder values with your actual credentials.

```bash
# NodeMailer Configuration
NODE_MAILER_EMAIL=your_email@gmail.com
NODE_MAILER_GMAIL_APP_PASSWORD=your_gmail_app_password

# Pusher Configuration
NEXT_PUBLIC_PUSHER_APP_CLUSTOR=your_app_cluster
NEXT_PUBLIC_PUSHER_APP_SECRET=your_app_secret
NEXT_PUBLIC_PUSHER_APP_KEY=your_app_key
NEXT_PUBLIC_PUSHER_APP_ID=your_app_id

# OpenAI Configuration
OPEN_AI_KEY=your_openai_key

# UploadCare Configuration
NEXT_PUBLIC_UPLOAD_CARE_PUBLIC_KEY=your_uploadcare_public_key
UPLOAD_CARE_SECRET_KEY=your_uploadcare_secret_key

# Clerk Configuration
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/auth/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/auth/sign-up

# Stripe Configuration
STRIPE_SECRET=your_stripe_secret_key
NEXT_PUBLIC_STRIPE_PUBLISH_KEY=your_stripe_publish_key

# Prisma Configuration
DATABASE_URL='your_database_url'


```

Make sure to fill in the necessary environment variables in the .env file.

## Chatdocrepo File Structure

ChatDoc uses a monorepo setup managed by Turborepo and includes a Next.js application. Below is an overview of the file structure:

````bash
# corinna-ai

SAHAYAK -AI is a cutting-edge web application designed to provide seamless user experiences with robust backend support. This repository houses the core of corinna-ai, including its frontend, backend, and associated configurations.

## Project Structure

Below is the structure of the main folders and files:

```plaintext
corinna-ai/
│
├── prisma/                         # Prisma ORM setup and schema files
├── public/                         # Public assets (images, fonts, etc.)
├── src/                            # Source code for the application
│   ├── actions/                    # Actions and logic for interacting with services
│   ├── app/                        # Main application folder, including pages and routes
│   ├── components/                 # Reusable UI components
│   ├── constants/                  # Application constants and configurations
│   ├── context/                    # React context for global state management
│   ├── hooks/                      # Custom React hooks
│   ├── icons/                      # Icon components and assets
│   ├── lib/                        # Libraries and utility functions
│   ├── schemas/                    # Validation schemas
│   ├── middleware.ts               # Middleware functions
├── .eslintrc.json                  # ESLint configuration file
├── .gitignore                      # Files and directories to be ignored by Git
├── README.md                       # Project documentation
├── components.json                 # Configuration for components
├── next-env.d.ts                   # TypeScript environment settings for Next.js
├── next.config.mjs                 # Next.js configuration file
├── package-lock.json               # Auto-generated file for package version locking
├── package.json                    # Node.js dependencies and scripts
├── postcss.config.js               # PostCSS configuration
├── tailwind.config.ts              # Tailwind CSS configuration
├── tsconfig.json                   # TypeScript configuration
├── yarn.lock                       # Yarn dependency lock file

````





