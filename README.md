# @rotarsebastian/inhale

A Next.js application with Tailwind CSS integration.

## Features

- 🎨 Built with Next.js 15 and Tailwind CSS
- 🚀 Modern and responsive design
- 🌗 Dark mode support
- 📦 Easy to integrate

## Installation

```bash
npm install @rotarsebastian/inhale
```

## Usage

```jsx
import { Home } from '@rotarsebastian/inhale';

export default function YourPage() {
  return (
    <div>
      <Home />
    </div>
  );
}
```

## Development

To start the development server:

```bash
npm run dev
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build the package
- `npm run test` - Run tests
- `npm run lint` - Run linting

### Version Management

To create a new version:

```bash
npm run version:patch  # For bug fixes (0.1.0 → 0.1.1)
npm run version:minor  # For new features (0.1.0 → 0.2.0)
npm run version:major  # For breaking changes (0.1.0 → 1.0.0)
```

## Requirements

- Node.js >= 18.18.0
- React >= 19.0.0
- Next.js >= 15.2.2

## License

MIT

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

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
