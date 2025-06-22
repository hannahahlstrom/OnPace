# OnPace

**OnPace** is a personal project focused on leveraging AI and modern technologies to reimagine personal finance tracking — with an emphasis on pacing, progress, and positive reinforcement. It’s designed specifically for new grads and budgeting beginners who want smart guidance without spreadsheets or guilt.

---

## Overview

OnPace helps users:
- Track flexible spending categories like dining, shopping, and fitness
- Visualize progress using Apple Watch–style “pace rings”
- Receive AI-powered insights and pacing forecasts
- Get encouraging nudges and badges for staying on track
- Learn how to adjust their budget in real time based on spending behavior

---

## Why I Built This

As a recent grad, I found most finance apps overwhelming, spreadsheet-heavy, or anxiety-inducing. I wanted a tool that feels more like a wellness app for your wallet — something supportive, smart, and motivating.

---

## Tech Stack (MVP)

- Frontend: React + TypeScript + Tailwind CSS + Framer Motion  
- Backend: Node.js + Express  
- Database: PostgreSQL (via Supabase or Prisma)  
- AI Integration: OpenAI API (GPT-4 Turbo) for budget coaching and pacing predictions  
- Auth: Supabase Auth or Clerk  
- Deployment: Vercel (frontend) + Render or Supabase (backend/database)

---

## Key Features

- Budget Dashboard – Track category-based spending and pacing
- Activity Rings – Weekly and monthly visuals to show "on pace" progress
- AI Budget Coach – Natural-language insights and suggestions
- Smart Forecasts – AI-based predictions for category end-of-month totals
- Positive Reinforcement – Badges for on-track behavior and helpful nudges
- Notifications – Weekly check-ins, overspending alerts, and encouragement

---

## Installation

```bash
git clone https://github.com/hannahahlstrom/onpace.git
cd onpace
npm install
npm run dev
