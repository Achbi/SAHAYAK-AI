## SAHAYK-AI 
An all-in-one solution that enhances customer interactions with automated AI chat, bookings, payments, and lead management. It integrates seamlessly into any website, providing customizable and white-labeled solutions for real-time chat, email marketing, and secure file uploads. Optimize sales and customer engagement with a minimal, modern UI, smart AI, and feature control settings.

## Features
Automated AI Sales Rep: AI chatbot that handles customer inquiries.
Appointment Booking: Automates scheduling and payment processing.
Easy Website Integration: Embed into any site with simple code.
Smart Question Linking: Intelligent question-response matching.
Real-time Chat: Allows switching between manual and automated chats.
White-labeling: Fully customizable interface for your brand.
Customizable Interface: Personalize UI elements to match your design.
Calendar Widget: Easy-to-use booking system.
Stripe Integration: Secure payment processing with Stripe.
Email Marketing: Simplified email marketing tools for outreach.
Financial Dashboard: Track and manage financial performance.
Lead Management: Save visitor data as leads for future marketing.
Custom Login/Signup: Secure authentication with OTP.
File/Image Uploads: Safely upload files and images.
SEO Optimized Blogging: In-built blog to enhance SEO.
Improved Architecture: Better scalability and performance.
Minimal UI: Clean, visually appealing user interface.
FAQ Section: Built-in section to answer common customer queries.
Light/Dark Mode: Toggle between light and dark themes.
Feature Control Settings: Manage and configure features.
Feature Restriction by Plan: Limit features based on subscription plans.


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





