This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Railway

1. **Create a GitHub repo** (if you don’t have one), then add it as a remote and push:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/chatcrm.git
   git push -u origin main
   ```

2. **Connect Railway**: Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub repo → select `chatcrm`.

3. **Set env vars** in the Railway project: **Variables** → Add `OPENAI_API_KEY`, `TELEGRAM_API_ID`, `TELEGRAM_API_HASH` (same as `.env.local`).

4. Railway will run `npm run build` and `npm start`. After deploy, open the generated URL (e.g. `https://chatcrm-production.up.railway.app`). Use that URL in my.telegram.org when creating your app if needed.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
