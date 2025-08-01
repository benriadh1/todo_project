# Todo App AI Suite - Documentation

## Overview
This project is a full-featured AI-powered task management platform with:
- Task management (CRUD, stages, labels, attachments)
- Calendar and Kanban views
- AI Copilot (OpenAI)
- Team-based roles, permissions, chat, notifications
- Multilingual support
- PWA & offline functionality
- Admin dashboard & reporting

---

## Backend (Laravel)
### Setup
1. `cd backend`
2. Copy `.env.example` to `.env`
3. Run `composer install`
4. `php artisan key:generate`
5. `php artisan migrate --seed`

---

## Frontend (Vue 3)
### Setup
1. `cd frontend`
2. Copy `.env.example` to `.env`
3. `npm install`
4. `npm run dev`

---

## Docker
```bash
docker compose up --build
```

Access the app at `http://localhost:5173`

---

## AI Setup
Set your OpenAI API key in `.env`:
```
OPENAI_API_KEY=your-key-here
```

---

## PWA
The app is installable and works offline.

---

## Multi-language
Edit language files in `frontend/src/locales/`.

---

## Credits
Generated with 💬 by ChatGPT.
