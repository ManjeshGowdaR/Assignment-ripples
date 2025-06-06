# Survey Platform

A modern, feature-rich survey platform built with Next.js, TypeScript, and Tailwind CSS.

## Features

- 📝 Create and manage surveys
- 🎯 Multiple question types
- 📊 Real-time analytics and response tracking
- 🔒 Secure authentication
- 📱 Responsive design
- 🎨 Modern UI with Tailwind CSS
- 🔄 Real-time data updates

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v18 or higher)
- npm or yarn
- Git

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd survey-platform
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Create a `.env.local` file in the root directory and add your environment variables:
```env
NEXT_PUBLIC_API_URL=your_api_url_here
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Project Structure

```
survey-platform/
├── app/                    # Next.js app directory
│   ├── api/               # API routes
│   ├── lib/               # Utility functions and API client
│   ├── surveys/           # Survey-related pages
│   └── components/        # Reusable components
├── public/                # Static assets
├── styles/               # Global styles
└── types/                # TypeScript type definitions
```

