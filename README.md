# Project Setup

## Overview

This project is a self-contained document scanning and matching system with a built-in credit system. Each user has a daily limit of 20 free scans, and additional scans require requesting more credits.

### Tech Stack

- **Backend:** Node.js with Express
- **Database:** SQLite (or JSON for small-scale storage)

## Status Update

I was unable to fully implement the project within the given timeline. I sincerely apologize for this. I plan to complete the remaining parts of the project without React after my mid-term exam.

## Clone the Repository

```sh
git clone <repository-url>
cd <project-folder>
```

## Backend Setup

Run the following commands in the terminal:

```sh
cd backend
npx sequelize-cli db:migrate
npm start
```

> **Note:** In `server.js` (line 79) of the backend, replace the existing API with the **Gemini API** for better functionality.

## Frontend Setup

Open a new terminal and run:

```sh
cd frontend
npm run dev
```

Your application should now be running successfully!

