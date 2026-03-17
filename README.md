# REFORGE — 20-Week Body Recomposition System

A premium, interactive web application for comprehensive body transformation tracking. Built as a single HTML file with JSON database files for GitHub Pages deployment.

## 🚀 Live Demo

Deploy to GitHub Pages or open `index.html` directly in any modern browser.

## 📁 File Structure

```
├── index.html              # Main application (single self-contained file)
├── db_individuals.json     # Individual athlete profiles database
├── db_foods.json           # Complete food/nutrition database
├── db_exercises.json       # Exercise library with progressions
├── db_plans.json           # Meal plans & training programs by phase
└── README.md               # This file
```

## 🗄️ Database Architecture

### `db_individuals.json`
Stores athlete profiles including: height, weight, targets, athletic history, health conditions, dietary restrictions, macro targets, IF progression schedules, performance milestones, supplement protocols, and weekly progress logs.

### `db_foods.json`
Complete food database with: names (English + Spanish), category, per-100g macros (calories, protein, fat, net carbs, fibre, sodium), cooking methods, seasoning suggestions, tier ranking, and dietary compliance flags.

### `db_exercises.json`
Exercise library with: muscle groups, equipment needed, full descriptions, coaching cues, phase assignments, sets/reps prescriptions, and progression chains.

### `db_plans.json`
Combined meal plans and training programs organized by phase (1–4), with day-by-day meal structures, macro breakdowns, circuit configurations, and recovery protocols.

## ⚙️ How It Works

1. **On first load**, the app seeds IndexedDB with embedded default data
2. **If JSON files are accessible** (GitHub Pages), richer data is merged in automatically
3. **All user data** (new individuals, daily logs, custom foods/exercises) is persisted in IndexedDB
4. **No server required** — everything runs client-side

## 🎯 Features

- **Dashboard** — At-a-glance view with weight tracking, performance targets, nutrition summary, workout status, and AI-powered daily advice
- **Daily Log** — Track meals (with macros), exercises (sets/reps/weight), and body metrics (weight, waist, BP, energy, sleep)
- **Progress** — Weight trajectory charts, strength radar, macro averages
- **Nutrition Plan** — Phase-by-phase meal planning with IF schedules and food databases
- **Training Plan** — Progressive exercise programs with phase timelines
- **Individuals** — Multi-athlete support with independent profiles and plans
- **Food Database** — Searchable, filterable, extensible food library
- **Exercise Database** — Complete movement library with coaching cues
- **Knowledge Base** — Full plan reference adapted to the active individual

## 🔧 Keyboard Shortcuts

- `Ctrl + +` — Advance current week (for testing/demo)
- `Ctrl + -` — Go back one week

## 📱 Responsive

Works on desktop, tablet, and mobile with collapsible sidebar navigation.

## 🏋️ Designed For

Athletes returning to training after extended breaks who need structured diet and exercise programming with comprehensive tracking.

## License

Open source. Use freely for personal transformation tracking.
