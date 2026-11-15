<img src="banner.png" alt="Backend · Full-stack developer — Python, FastAPI, PostgreSQL" width="100%">

### Hi, I'm Karasai 👋

4th-year **Computer Engineering** student at Al-Farabi Kazakh National University (KazNU), looking for a **junior backend / full-stack** role or internship.
I like building things people actually use: from the database schema and API to a clean interface and deployment.

**Русский:** студент 4 курса КазНУ, «Компьютерная инженерия». Ищу работу или стажировку junior backend / fullstack разработчиком.

---

### ⭐ Featured project — [AI Finance Tracker](https://github.com/Karasai69/ai-finance-tracker)

<a href="https://github.com/Karasai69/ai-finance-tracker"><img src="https://raw.githubusercontent.com/Karasai69/ai-finance-tracker/main/docs/screenshots/demo.gif" alt="AI Finance Tracker demo" width="100%"></a>

Personal finance tracker where you type expenses in plain text — *"taxi 1 200, lunch 1 500, my brother sent 10 000"* — and an LLM turns them into categorized entries. Replaced the Google Sheet I filled by hand every day.

- **Backend:** Python, FastAPI, SQLAlchemy 2.0, Alembic migrations, PostgreSQL
- **AI:** LLM via an OpenAI-compatible API with validation and a rule-based fallback; the app computes every number, the model only phrases them
- **Auth & security:** JWT in httpOnly cookies, scrypt, rate limiting, logout on all devices after a password change
- **Frontend:** vanilla JS calendar, spreadsheet view, mobile screens, PWA, voice input
- **DevOps:** Docker, GitHub Actions (tests on SQLite and PostgreSQL), auto-deploy to Render + Neon

**[▶ Live demo](https://ai-finance-tracker-05rj.onrender.com)** (one-click demo account) · **[Code & README](https://github.com/Karasai69/ai-finance-tracker)**

---

### 💈 Second project — [Barber Booking](https://github.com/Karasai69/barber-booking)

<a href="https://github.com/Karasai69/barber-booking"><img src="https://raw.githubusercontent.com/Karasai69/barber-booking/main/docs/screenshots/admin-schedule.png" alt="Barber Booking: a barber's day on a time axis next to a barber pole" width="100%"></a>

Online booking for a barbershop: clients book through a Telegram bot, barbers mark visits in a web dashboard, the admin sees load and revenue. Built to learn what the first project didn't cover: background jobs, roles and concurrency.

- **No double booking, enforced by the database:** a PostgreSQL `EXCLUDE` constraint on overlapping time ranges; a test fires 10 parallel requests at one slot and exactly one wins
- **Background jobs:** Celery + Redis send reminders 2 hours before a visit and a daily report to the admin, without duplicates
- **Telegram bot:** aiogram 3 — pick a service, barber and free slot, see and cancel your bookings
- **Roles:** admin and barber accounts, JWT for the API and in an HttpOnly cookie for the dashboard
- **DevOps:** Docker Compose with 7 services, GitHub Actions (lint, migration check, tests on PostgreSQL, image build)

**[Code & README](https://github.com/Karasai69/barber-booking)** · **[Design decisions](https://github.com/Karasai69/barber-booking/blob/main/DECISIONS.md)**

---

### 🛠 Tech

**Languages:** Python · C++ · JavaScript · SQL
**Backend:** FastAPI · SQLAlchemy · Alembic · Pydantic · REST APIs · Celery · aiogram
**Databases:** PostgreSQL · SQLite · Redis
**Tools:** Git · Docker · GitHub Actions · Linux · PyCharm · Google Colab

### 📫 Contact

Open to junior backend / full-stack positions and internships — feel free to reach out via GitHub.
