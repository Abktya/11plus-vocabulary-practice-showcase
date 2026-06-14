# 11+ Vocabulary Practice 📚

> iOS vocabulary app for UK 11+ exam preparation — live on the App Store with 92+ active users.

## Overview

A production iOS app helping UK children prepare for the 11+ exam with 2,200+ vocabulary words, intelligent quiz modes, and parental progress tracking. Built end-to-end as a solo engineer using AI-assisted development throughout.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Mobile | React Native (Expo SDK 54) |
| Backend | Django REST Framework |
| Database | PostgreSQL |
| Auth | Google Sign-In, Apple Sign-In |
| Build | EAS Build, App Store Connect |
| AI Tools | Claude Code, Cursor, GitHub Copilot |

## Key Features

- **2,200+ vocabulary words** with definitions, examples and difficulty tiers
- **Multiple quiz modes** — multiple choice, fill-in-the-blank, spelling
- **Exam Mode** — timed, exam-condition practice sessions
- **Spaced repetition** — smart scheduling based on performance
- **Parental progress tracking** — detailed stats and session history
- **Streak system** — daily practice motivation
- **Google & Apple Sign-In** — frictionless onboarding

## AI-Assisted Development

This project was built using AI coding tools throughout the development lifecycle:

- **Claude Code** — feature development, architecture decisions, debugging
- **Cursor** — refactoring and code completion
- **GitHub Copilot** — boilerplate and test generation

AI tools enabled a solo engineer to ship a production-quality app with features typically requiring a full team.

## Architecture

```
iOS App (React Native / Expo)
    ↓ HTTPS
Django REST Framework API (self-hosted, Ubuntu)
    ↓
PostgreSQL Database
    ↑
Nginx + Gunicorn + Cloudflare Tunnel
```

## Status

🟢 **Live on the Apple App Store** — 92+ active users

---
*Built by Ahmet Baktiaya · BKTY LTD · [bktyconsultancy.co.uk](https://bktyconsultancy.co.uk)*
