# Market Dashboard

A modern, interactive market analytics dashboard built with React, Vite, TypeScript, and shadcn/ui. Visualize market data with charts, cards, and a polished responsive UI — everything runs client-side.

## Features

- Interactive market-data dashboard with rich visualizations
- Built on React 18 + TypeScript with Vite for fast builds
- shadcn/ui component library (Radix primitives, Tailwind CSS)
- Dark/light theme support (next-themes)
- Data fetching with TanStack React Query
- Charts, tables, forms, and dashboard widgets
- Responsive design for desktop and mobile
- Client-side only — no backend required

## Tech Stack

- **Framework:** React 18 + TypeScript
- **Build tool:** Vite
- **UI:** shadcn/ui (Radix UI), Tailwind CSS
- **State/Data:** TanStack React Query
- **Icons:** Lucide React

## Quick Start

```bash
npm install
npm run dev
```

Open the dev URL shown in the terminal in your browser.

## Build

```bash
npm run build        # outputs to dist/
npm run preview      # preview the production build
```

## Project Structure

```
├── src/
│   ├── components/   # UI components (shadcn/ui based)
│   ├── pages/        # Page-level views
│   ├── hooks/        # Custom React hooks
│   ├── utils/        # Helper functions
│   ├── App.tsx       # App entry
│   └── main.tsx      # Vite entry
├── public/           # Static assets
├── index.html        # HTML entry
└── vite.config.ts    # Vite config
```

## Environment Variables

None — the app runs fully client-side.

## Deploy

This is a static Vite build. Deploy the `dist/` folder to any static host (Cloudflare Pages, Netlify, Vercel, GitHub Pages).

---

Built by Girish Lade — https://ladestack.in
