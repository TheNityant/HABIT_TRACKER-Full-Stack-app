# 🌟 Habit Tracker

<p align="center">
  <strong>A cross-platform habit and productivity application built with Flutter, Spring Boot, PostgreSQL, and AI-assisted journaling.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=google&logoColor=white" alt="Gemini API">
</p>

---

## 🎥 Demo

<p align="center">
  <img
    src="GIF/Habit_Tracker_README_demo_ultra.gif"
    width="100%"
    alt="Habit Tracker application demo"
  />
</p>

<p align="center">
  <sub>Habit management, calendar history, journaling, priority tasks, analytics, and the Command Center workflow.</sub>
</p>

---

## 🧭 Overview

Habit Tracker is a full-stack productivity application for managing **habits, tasks, journals, calendar history, and personal progress** across supported platforms.

The application uses a Flutter client connected to a Spring Boot REST API, with PostgreSQL providing persistent storage and Gemini supporting AI-assisted journal processing.

> 🟢 **Current repository:** stable cloud-backed implementation.

---

## ✨ Highlights

| | Capability | Description |
|---|---|---|
| 🎯 | **Habit Management** | Create, update, delete, check in, and track habits |
| ✅ | **Task Management** | Manage tasks with priorities and completion states |
| 📅 | **Calendar History** | Review activity across previous dates |
| 📝 | **Journaling** | Create and manage personal journal entries |
| 🤖 | **AI Assistance** | Gemini-powered journal processing |
| 📊 | **Analytics** | Inspect progress and historical activity |
| 📁 | **Media Uploads** | Upload and serve media through the backend |
| 🌐 | **Cross-Platform** | Android, iOS, Web, Linux, macOS, and Windows |

---

## 🏗️ Architecture

```text
                    ┌───────────────────────┐
                    │     Flutter Client    │
                    │                       │
                    │ Habits · Tasks        │
                    │ Analytics · Journal   │
                    │ Calendar · UI         │
                    └───────────┬───────────┘
                                │
                                │ REST API
                                ▼
                    ┌───────────────────────┐
                    │    Spring Boot API    │
                    │                       │
                    │ Auth · Habits         │
                    │ Tasks · Journal       │
                    │ Uploads               │
                    └───────────┬───────────┘
                                │
                                ▼
                    ┌───────────────────────┐
                    │      PostgreSQL       │
                    └───────────────────────┘
                                │
                                │ AI-assisted
                                │ journal processing
                                ▼
                         ┌──────────────┐
                         │  Gemini API  │
                         └──────────────┘
```

---

## 🧩 Product Areas

### Command Center
A consolidated workspace for habits, task priorities, daily activity, and progress.

### Calendar
Navigate previous dates and review historical activity.

### Journal
Record notes and journal entries alongside daily productivity data.

### Analytics
Inspect habit completion and other historical progress indicators.

### AI-Assisted Journaling
Use Gemini-backed processing to augment the journaling workflow.

---

## 🎯 Project Goal

The project explores what happens when a habit tracker is treated as a real full-stack system rather than a local-only UI exercise:

```text
cross-platform client
        ↓
REST backend
        ↓
persistent relational data
        ↓
AI-assisted features
        ↓
history + analytics
```

---

## 📌 Status

The repository represents the stable cloud-backed implementation of the application.

---

<div align="center">

**Track consistently. Understand the pattern. Improve deliberately.**

</div>
