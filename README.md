<div align="center">

# 🔧 Habit Tracker — Backend

**REST API for the Habit Tracker system**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

</div>

---

## About

Backend API service for the [Habit Tracker](https://github.com/foxnaim/habit-tracker) system. Provides RESTful endpoints for habit management, user authentication, and analytics.

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Register new user |
| POST | `/api/auth/login` | User login |
| GET | `/api/habits` | Get all habits |
| POST | `/api/habits` | Create new habit |
| PUT | `/api/habits/:id` | Update habit |
| DELETE | `/api/habits/:id` | Delete habit |
| POST | `/api/habits/:id/check` | Check-in habit |

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Runtime | Node.js |
| Framework | Express.js |
| Database | MongoDB + Mongoose |
| Language | JavaScript |

## Getting Started

```bash
git clone https://github.com/foxnaim/habit-tracker-back.git
cd habit-tracker-back
yarn install
yarn start
```

## Related

- [habit-tracker](https://github.com/foxnaim/habit-tracker) — Monorepo
- [habit-tracker-front](https://github.com/foxnaim/habit-tracker-front) — Frontend
- [habit-tracker-bottg](https://github.com/foxnaim/habit-tracker-bottg) — Telegram Bot

## License

MIT © [foxnaim](https://github.com/foxnaim)
