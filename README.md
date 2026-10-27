# FairShift Workers

FairShift is a worker-focused workplace wellbeing and safety web app with a separate Employer Portal.

## Features
- Worker workspace for logging work activity and wellbeing/safety concerns
- Safety reporting interface and report history
- Employer dashboard with workforce/attendance demo metrics
- Employer safety-report view and open-shift management
- Workplace wellbeing checklist
- Responsive layout for desktop and mobile

## Live demo
https://fairshift-workers.higgsfield.app

## Tech stack
- React + TypeScript
- TanStack Start / Vite
- CSS
- Bun workspaces

## Run locally
1. Install Bun (https://bun.sh).
2. From the `app` directory, install dependencies with `bun install`.
3. Start the dev server with `bun run dev`.

> Note: employer dashboard metrics are demonstration data. Worker reports and shifts use browser local storage in this demo; they are not synchronized across different devices without a shared backend.

## Project layout
- `app/src/routes/index.tsx` — main worker/employer portal
- `app/src/styles.css` — responsive UI styling
- `app/package.json` — application scripts and dependencies
