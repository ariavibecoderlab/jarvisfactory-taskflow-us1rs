# TaskFlow

We're building TaskFlow — a clean, browser-based to-do list app where users sign up once and can manage their tasks from any device. Tasks are color-coded by priority (High in red, Medium in orange, Low in green) and sorted automatically so the most urgent work is always at the top. Users can add tasks in seconds, mark them complete, and delete what they don't need. The whole thing is built on Supabase so data saves instantly and persists across sessions. This is a well-scoped, fast-to-build app with zero unnecessary complexity — exactly the kind of foundation you can launch, learn from, and grow. (saved 5:24:24 AM)

> Built with **[JarvisFactory.ai](https://jarvisfactory.ai)** — your personal AI developer.

## Run locally

Open `index.html` in a browser. That's it.


## Overview

We're building TaskFlow, a clean and intuitive web-based to-do list app that lets everyday users sign up, create tasks, and organize their day with priority-based color coding. It's designed for anyone who wants a simple, no-clutter way to stay on top of what matters — no app download required, just open a browser and go. The unfair advantage is simplicity: most task apps are bloated with features nobody uses; TaskFlow does the core job beautifully and gets out of the way. Built on Supabase for instant, reliable data sync across every device the user opens it on.


## Features

- Users sign up with email and password and stay logged in for 30 days — no need to log back in every session
- Users can create a new task in under 5 seconds by typing a title and hitting Enter
- Each task gets a priority level — High (red), Medium (orange), or Low (green) — so urgent work stands out immediately
- Tasks are displayed in a clean list, automatically sorted so High priority tasks appear at the top
- Users can mark any task as complete with a single click, which moves it to a 'Done' section at the bottom
- Users can delete tasks they no longer need, keeping their list clean and focused


## Tech

- Frontend: Single-page HTML/CSS/JS app with dynamic task rendering — priority color coding handled via CSS classes, no page reloads needed
- Backend: Supabase (Postgres + Auth via Jarvis library) — handles user accounts and real-time task data persistence
- AI: Not required for MVP — TaskFlow is a clean utility app; no AI features planned at this stage


## License

MIT — you own this code.
