# Frontend Interview — Blog Application

A React + TypeScript blog application built as a frontend engineering assignment. It demonstrates server-state management, responsive UI, reusable components, and CRUD-style blog workflows.

## ✨ Features

- Blog list and blog detail views
- Create new blog posts
- TanStack Query for server-state management
- JSON Server development API
- Responsive Tailwind CSS interface
- Reusable UI components
- Loading and error states
- TypeScript-based development

## 🧰 Tech Stack

- React
- TypeScript
- Vite
- TanStack Query
- Tailwind CSS
- shadcn/ui-style components
- JSON Server
- Framer Motion
- Lucide React

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install

```bash
git clone https://github.com/shivamsharmakr04/Frontend-Interview.git
cd Frontend-Interview
npm install
```

### Start the API

In one terminal:

```bash
npm run server
```

The JSON Server API runs on `http://localhost:3001`.

### Start the frontend

In a second terminal:

```bash
npm run dev
```

Open the Vite URL shown in the terminal.

## 🔌 API

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/blogs` | List blogs |
| GET | `/blogs/:id` | Read a blog |
| POST | `/blogs` | Create a blog |

## 🏗️ Development

The project uses TanStack Query for fetching and cache management. Keep API access isolated from presentation components and handle loading/error states at the UI boundary.

## 📌 Portfolio Note

This repository contains my completed implementation of the interview assignment; the README intentionally documents the implementation rather than reproducing the original hiring instructions.

## 👨‍💻 Author

**Shivam Kumar** — Full-Stack Developer

[GitHub](https://github.com/shivamsharmakr04) · [LinkedIn](https://linkedin.com/in/shivam-kumar-b0aab2209)
