# 🧠 AI/ML Mastery Tracker

> An interactive, zero-dependency roadmap and habit tracker designed to take learners from math foundations to production ML, transformers, and global competitions.

---

## 📌 Overview

**AI/ML Mastery Tracker** is a comprehensive, browser-based dashboard built for machine learning engineers and data scientists. It provides a curated, phase-by-phase curriculum, daily study logs, Pomodoro focus tools, habit tracking, and cloud sync via Supabase.

Everything runs from a single HTML file—featuring zero build steps, hardware-accelerated zero-G aesthetic UI, and real-time cloud data persistence.

---

## ✨ Features

- **8-Phase Structured Curriculum**: 50+ topics covering Linear Algebra, Calculus, Core ML, Deep Learning, Transformers, MLOps, System Design, and Research.
- **Solo & Integration Capstones**: Hands-on projects tied directly to learned skills, from scratch implementations to cloud pipelines.
- **Full-Screen Authentication Gate**: Secure Email/Password registration along with OAuth support (Google, GitHub, Discord).
- **Cloud State Synchronization**: Real-time progress syncing to Supabase PostgreSQL (`profiles` table) with debounced background saves.
- **Gamified Progression**: Dynamic Leveling & XP tracking, achievement badges, and streak mechanics.
- **Productivity Cockpit**:
  - Built-in Pomodoro timer and stopwatch with direct study log integration.
  - Interactive calendar heatmap for study streaks.
  - Quick note-taking with categorised tagging.
  - Curated AI research paper feeds, lab blogs, and notification setup guides.
- **Zero-G Cockpit Interface**: Dynamic particle canvas, tactile Web Audio API sound effects, and frosted-glass HUD styling.

---

## 🛠️ Tech Stack

- **Frontend**: Pure Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Backend / Auth / DB**: [Supabase](https://supabase.com/) (Auth & PostgreSQL JSON storage)
- **Audio & Physics**: Web Audio API & HTML5 Canvas
- **Typography**: Inter, Plus Jakarta Sans, Space Mono

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/](https://github.com/)<your-username>/aiml-tracker.git
cd aiml-tracker
