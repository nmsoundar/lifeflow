# LifeFlow – Daily Task & Reminder

LifeFlow is a calm, minimal, offline-first Android app designed to help users manage daily life tasks and reminders without stress.

This repository serves as the **single source of truth** for product vision, UX principles, and future development.

---

## 🎯 App Purpose

LifeFlow helps users remember and manage:
- Daily life tasks
- One-time reminders
- Personal, family, and work-related activities

Examples:
- Pay school fees
- Attend functions
- Buy groceries
- Study reminders
- Health and fitness tasks

---

## 🧠 Core Philosophy

- Minimal & calm (non-stressful)
- Designed for daily life flow, not productivity pressure
- Offline-first
- Very fast task creation
- Visually pleasing floating task tiles

---

## 🏠 Home Screen (Main)

- White / off-white background
- Scrollable list of tasks (supports many tasks)
- Section header: **Today**
- Date shown in small, subtle text
- Minimal bottom navigation

### Bottom Navigation
- Today
- Week
- More

Advanced options live inside **More**:
- Tomorrow
- Month
- Custom date
- Completed tasks
- Settings

---

## 🧩 Task Card Design (Core Feature)

Each task is shown as a floating rounded card:

- Unique soft pastel background color (auto-generated)
- Rounded corners with light elevation
- Left: auto-selected icon
- Center: task title + date/time (e.g. `Today · 5:00 PM`)
- Right: completion indicator

---

## 🎨 Color & Theme

- Soft pastel task colors (mint, lavender, peach, light blue, soft yellow)
- Brand gradient: **orange → pink**
- Gradient is used sparingly:
  - Floating + button
  - Primary actions
  - Selected navigation item

---

## ➕ Floating Action Button

- Bottom-right
- Circular
- Brand gradient
- Opens task creation
- Supports:
  - Text input
  - Voice input

---

## 🧠 Icon Auto-Selection

Icons are assigned automatically based on task keywords:

- Study → book
- Gym → dumbbell
- Work / Meeting → briefcase
- Shopping / Buy → cart
- Family / Kids → people
- Payment / Fees → wallet
- Travel → bag

Fallback: generic task icon.

---

## ✅ Task Actions

Each task supports:
- Mark complete
- Reschedule
- Cancel

Completed tasks automatically move out of Today view.

---

## 🎙 Voice Task Creation

Users can create tasks by voice, e.g.:
> “Pay school fees tomorrow at 10 AM”

The app extracts:
- Task title
- Date
- Time

---

## 🚀 MVP Scope (Initial Release)

- Single-user only
- Offline-first local storage
- No login
- No cloud sync
- No family sharing

Advanced features will be added incrementally.

---

## 🧩 Branding

- App name: **LifeFlow – Daily Task & Reminder**
- Logo: rounded square with a soft flowing checkmark
- Warm gradient (orange → pink)
- Clean, flat, professional design

---

## 📌 Notes

This README is intentionally detailed so it can be reused as:
- AI master prompt
- Product reference
- Design guideline
