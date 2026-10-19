# ChronosEdu — Intelligent School Timetable & Academic Operations Platform

ChronosEdu is an intelligent, human-in-the-loop school scheduling platform built with a 3-layer scheduling architecture:
- **Layer A (Facts Setup):** 10-step school configuration wizard, school profile, multi-tier bell schedules, rooms & capacities, subject requirements, and 1-to-1 Class + Subject teacher assignments.
- **Layer B (Rule Solver Engine):** Conflict-free slot placement respecting hard & soft constraints, locked/pinned lessons, room capacities, and teacher daily/weekly limits.
- **Layer C (Interactive Studio & Lifecycle):** Real-time clash detection, rule overrides with audit logging, 5-tier ranked substitute suggestions, version publishing, and exports.

## Tech Stack
- HTML5, Vanilla JavaScript, Tailwind CSS (CDN)
- LocalStorage persistence & JSON export/import

## Local Development
Open \index.html\ directly in any browser, or run:
\\\ash
npx serve .
\\\

## Deployment on Vercel
Deploy seamlessly via Vercel CLI or by importing the GitHub repository into your Vercel Dashboard.
