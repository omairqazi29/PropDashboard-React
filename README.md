# Prop Trading Dashboard

A personal dashboard for tracking prop trading firm accounts, expenses, and progress.

## Features

- Track accounts across multiple prop firms (Apex, Lucid, etc.)
- Monitor expenses and calculate ROI
- View statistics and account breakdowns
- Payout projections with monthly forecasts
- Daily task tracking
- User authentication with Supabase

## Tech Stack

- React + Vite
- Supabase (Auth + Database)
- GitHub Pages (Hosting)

## Setup

1. Clone the repo
2. Copy `.env.example` to `.env` and add your Supabase credentials:
   ```
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```
3. Install dependencies: `npm install`
4. Run locally: `npm run dev`

## Deployment

Automatically deploys to GitHub Pages on push to `main` branch.

Live: https://omairqazi29.github.io/PropDashboard-React/
