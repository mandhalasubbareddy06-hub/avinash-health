# AVI Health — Personal Health Copilot (Frontend)

A responsive React + Vite frontend prototype for a personal health dashboard. It includes an overview dashboard, health records, medication reminders, appointments, health tracking, an AI-copilot chat mockup, profile/settings modals, and a 3D-inspired sign-in screen.

## Requirements
- Node.js 20+ recommended
- npm

## Run in VS Code
1. Extract this ZIP and open the `avi-health-frontend` folder in VS Code.
2. Open **Terminal → New Terminal**.
3. Run `npm install`.
4. Run `npm run dev` and open the local URL Vite prints (usually `http://localhost:5173`).

## Production build
Run `npm run build`. The static production site will be generated in `dist/`. Preview it with `npm run preview`.

## Included screens
- Overview dashboard with wellness metrics and recent records
- Health records search/filter and add-record modal
- Medication checklist and add-reminder modal
- Appointment list and add-appointment modal
- Health tracking charts (sample data)
- AI Copilot chat UI with suggested prompts (mock response only)
- Profile and settings modals
- 3D-inspired login screen (demo sign-in only)

## Important limitations
This is **frontend-only**. Data is held in React state and resets on refresh. Login is not real authentication; records are not securely stored or uploaded; reminders do not send notifications; appointments are not booked with real providers; and the AI chat is a mock interaction, not connected to an AI model. Do not enter real patient data. Before real-world healthcare use, add a secure backend, validated authentication and authorization, encrypted storage, audit logs, consent controls, privacy/legal review, and a clinically reviewed AI integration. The UI is not a medical device and does not diagnose or treat conditions.

## Stack
- React
- Vite
- Lucide React icons
- Plain CSS (responsive; no Tailwind setup required)
