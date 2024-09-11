This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Project Structure

```
/my-fullstack-app
│
├── /backend # Node.js + Express backend
│ ├── /config # Configuration files (e.g., Firebase admin SDK)
│ │ └── firebase.js
│ ├── /controllers # Express route handlers
│ │ └── authController.js
│ ├── /routes # Express route definitions
│ │ └── authRoutes.js
│ ├── /middlewares # Express middlewares (e.g., authentication checks)
│ ├── /models # Mongoose models (if using MongoDB)
│ ├── app.js # Main entry point for the Express server
│ ├── package.json # Node.js dependencies and scripts
│ └── .env # Environment variables
│
├── /frontend # React + Next.js frontend
│ ├── /components # React components
│ │ ├── Login.js
│ │ ├── Register.js
│ │ └── Navbar.js
│ ├── /pages # Next.js pages
│ │ ├── \_app.js # Custom App component
│ │ ├── index.js # Home page
│ │ ├── login.js # Login page
│ │ └── register.js # Register page
│ ├── /public # Static files (e.g., images)
│ ├── /styles # CSS/SCSS files
│ ├── /utils # Utility functions (e.g., Firebase client SDK setup)
│ │ └── firebase.js
│ ├── package.json # React + Next.js dependencies and scripts
│ └── next.config.js # Next.js configuration
│
├── /scripts # Optional scripts (e.g., build scripts)
│
├── /docs # Documentation (e.g., API docs)
│
└── README.md # Project overview and instructions
```
