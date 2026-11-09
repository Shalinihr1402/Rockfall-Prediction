# Rockfall Prediction Dashboard

A web dashboard for visualizing rockfall-related monitoring information. The interface brings risk visualization, alerts, sensor readings, and predictive analytics into one place.

> **Status:** This repository currently contains a dashboard UI. Verify the data source, prediction model, and alerting integrations before using it for operational or safety decisions.

## Dashboard features

- **Risk heatmap** for viewing areas of elevated rockfall risk
- **Alerts panel** for surfacing monitoring alerts
- **Sensor data cards** for reviewing sensor readings
- **Predictive analytics** section for presenting analysis and forecasts
- Responsive layout built with Next.js, React, and TypeScript

## Tech stack

- [Next.js](https://nextjs.org/) 14
- [React](https://react.dev/) 18
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Recharts](https://recharts.org/) and [Lucide](https://lucide.dev/) among the UI dependencies

## Getting started

### Prerequisites

- Node.js (use a current LTS release)
- pnpm (the repository includes a `pnpm-lock.yaml`)

### Install and run

From the repository root, enter the application directory and start the development server:

```bash
cd rockfall-dashboard
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

You can also use npm if preferred:

```bash
cd rockfall-dashboard
npm install
npm run dev
```

## Available scripts

Run these commands from `rockfall-dashboard/`:

| Command | Description |
| --- | --- |
| `pnpm dev` | Start the local development server |
| `pnpm build` | Create a production build |
| `pnpm start` | Run the production server after building |
| `pnpm lint` | Run the configured lint command |

## Project structure

```text
rockfall-dashboard/
├── app/          # Next.js application routes
├── components/   # Dashboard and UI components
├── public/       # Static assets
├── styles/       # Global styles
└── package.json  # Scripts and dependencies
```

## Safety note

Rockfall monitoring is safety-critical. Treat dashboard output as informational unless the underlying measurements, model performance, thresholds, and alert delivery have been validated by qualified experts. Do not rely on this interface as the sole basis for safety or evacuation decisions.
