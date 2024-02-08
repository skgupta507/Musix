# Musix
Music streaming next.js app
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
Create env file in root dir.
```
MONGODB_URL = mongodb URL
DB_NAME = database name
JWT_SECRET = jwt secret
NEXTAUTH_URL= next auth url (http://localhost:3000 or your domain)
GOOGLE_CLIENT_ID = Google client id
GOOGLE_CLIENT_SECRET = Google client secret
First, run the development server:
MAIL_HOST = mail host (smtp.gmail.com)
MAIL_USER = mail user
MAIL_PASS = mail password
```

Run the development server:

```bash
npm install
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.
