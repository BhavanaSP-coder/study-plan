# 🗓️ Study Plan Chatbot

> Turn your subject and deadline into a simple daily study plan.

A browser-based prototype that creates a short study schedule from a free-text description. Review the suggested sessions and check them off as you go.

## ✨ Features

- **Quick plan generation** — creates daily study activities from your description.
- **Deadline-aware demo** — recognizes simple day or week counts in the input.
- **Progress checkboxes** — mark sessions complete during your current visit.
- **No setup required** — runs directly in your browser.

## 🚀 Run the app

1. Download and extract the project.
2. Open `index.html` in a modern web browser.
3. Enter your subject, deadline, and available study time.
4. Select **Build my plan**.

Example: `Biology exam in 3 weeks, genetics is my focus.`

## 🧰 Built with

- HTML
- CSS
- Vanilla JavaScript

## 📁 Project files

| File | Purpose |
|---|---|
| `index.html` | App interface and schedule-generation logic |
| `style.css` | Responsive visual styling |
| `README.md` | Project overview and instructions |

## ⚙️ How it works

The app uses simple, deterministic rules to create a sample sequence of study activities. It does not use an AI model, read calendar availability, or save your progress after the page closes.

## 🔭 Ideas for the next version

- Replace free-text parsing with structured subject, date, and availability fields.
- Add topic priorities and workload estimates.
- Support rescheduling and editing sessions.
- Save progress and sync with a calendar.
- Test date parsing, missed sessions, and conflicting commitments.

## ⚠️ Prototype limitations

The generated plan is a starting point, not a personalized academic recommendation. Review it and adjust the schedule to match your course, workload, and available time.
