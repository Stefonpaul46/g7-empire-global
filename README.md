# G7 Empire Global

A Next.js application integrated with Vercel Speed Insights for performance monitoring.

## Features

- ⚡ Next.js 14 with App Router
- 📊 Vercel Speed Insights integration
- 🎨 TypeScript support
- 🔍 ESLint configuration

## Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm, pnpm, yarn, or bun

### Installation

Install the dependencies:

```bash
npm install
# or
pnpm install
# or
yarn install
# or
bun install
```

### Development

Run the development server:

```bash
npm run dev
# or
pnpm dev
# or
yarn dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Build

Build the application for production:

```bash
npm run build
# or
pnpm build
# or
yarn build
# or
bun build
```

### Start Production Server

Start the production server:

```bash
npm start
# or
pnpm start
# or
yarn start
# or
bun start
```

## Vercel Speed Insights

This application is configured with Vercel Speed Insights to track performance metrics. 

### Setup

Speed Insights has been integrated following the official Vercel documentation:

1. The `@vercel/speed-insights` package is installed
2. The `<SpeedInsights />` component is added to the root layout (`app/layout.tsx`)
3. The component will automatically start tracking performance metrics once deployed to Vercel

### Enabling Speed Insights in Vercel

To enable Speed Insights for your deployment:

1. Go to your [Vercel dashboard](https://vercel.com/dashboard)
2. Select your project
3. Navigate to the **Speed Insights** tab
4. Click **Enable**

Once enabled and deployed, Speed Insights will add routes at `/_vercel/speed-insights/*` and begin collecting performance data.

### Viewing Your Data

After deployment and user visits:

1. Go to your [Vercel dashboard](https://vercel.com/dashboard)
2. Select your project
3. Click the **Speed Insights** tab to view your metrics

## Deployment

### Deploy to Vercel

The easiest way to deploy this Next.js app is to use the [Vercel Platform](https://vercel.com/new).

#### Option 1: Deploy via CLI

```bash
npm install -g vercel
vercel deploy
```

#### Option 2: Deploy via Git

Connect your repository to Vercel, and it will automatically deploy on every push to the main branch.

[Learn more about deploying Next.js apps](https://nextjs.org/docs/deployment)

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Vercel Speed Insights Documentation](https://vercel.com/docs/speed-insights)
- [React Documentation](https://react.dev)

## License

This project is private and proprietary.
