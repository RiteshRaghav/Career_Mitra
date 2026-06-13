# 🎓 Career Mitra — Mentorship & Career Guidance Platform

> Connect students with industry mentors for 1:1 sessions, webinars, and career growth.

🔗 **Live Demo:** [carrier-1-0-3.onrender.com](https://carrier-1-0-3.onrender.com)
&nbsp;&nbsp;|&nbsp;&nbsp;
📁 **GitHub:** [github.com/RiteshRaghav/Carrier_1.0](https://github.com/RiteshRaghav/Carrier_1.0)

---

## 📌 About the Project

**Career Mitra** is a full-stack web platform where students can find and book sessions with real industry mentors. Mentors can manage their availability, host webinars, and track earnings. An admin panel gives complete control over users, bookings, and payments.

The platform supports **three roles** — Student, Mentor, and Admin — each with their own dashboard and features.

---

## 🖼️ Screenshots


---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🔐 Role-based Login | Separate dashboards for Student, Mentor, and Admin |
| 🔍 Mentor Search | Filter by name, skills, domain, experience, and price |
| 📅 Session Booking | Students book 1:1 sessions with available time slots |
| 💳 Online Payment | Razorpay payment gateway for session and webinar fees |
| 🎙️ Webinars | Mentors host group workshops; students register and join |
| 📹 Video Calls | Live sessions via Jitsi Meet integration |
| 📊 Dashboards | Real-time stats for students, mentors, and admin |
| 💰 Earnings Tracker | Mentors track income with full payment history |
| 🛡️ Admin Panel | Manage users, mentors, bookings, and payments |
| 📧 Email Notifications | Automated emails for booking confirmations |

---

## 🛠️ Tech Stack

### Frontend
| Technology | Purpose |
|---|---|
| React.js 18 | UI framework |
| Vite | Build tool and dev server |
| Tailwind CSS | Styling |
| Redux Toolkit | Global state management |
| React Router v6 | Page routing |
| Axios | API calls to backend |
| Razorpay SDK | Payment integration |
| Framer Motion | Animations |
| Jitsi Meet | Video call integration |

### Backend
| Technology | Purpose |
|---|---|
| Java + Spring Boot | REST API server |
| Spring Security + JWT | Authentication and authorization |
| MySQL | Database |
| JPA / Hibernate | Database ORM |
| JavaMailSender | Email service |
| Maven | Build tool |

---

## 📁 Project Structure

```
career-mitra/
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── student/        # Student dashboard, bookings, mentor listing
│   │   │   ├── mentor/         # Mentor dashboard, earnings, webinars
│   │   │   ├── admin/          # Admin panel pages
│   │   │   └── auth/           # Login, signup, forgot password
│   │   ├── components/         # Reusable UI components
│   │   ├── context/            # Auth context
│   │   ├── services/           # Axios API service calls
│   │   ├── hooks/              # Custom React hooks
│   │   └── utils/              # Helper functions
│   └── package.json
│
└── backend/
    └── src/main/java/com/careermitra/
        ├── controller/         # REST API endpoints
        ├── service/            # Business logic
        ├── repository/         # Database queries
        ├── entity/             # Database models
        ├── dto/                # Data transfer objects
        ├── config/             # Security, CORS, DB seeder
        └── exception/          # Global error handling
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- Java 17+
- MySQL 8+
- Maven

### Frontend Setup

```bash
cd career-mitra/frontend
npm install
cp .env.example .env
npm run dev
```

### Backend Setup

```bash
cd career-mitra/backend
mvn spring-boot:run
```

### Environment Variables (Frontend `.env`)

```env
VITE_API_BASE_URL=http://localhost:8080/api
VITE_RAZORPAY_KEY=your_razorpay_key_here
```

---

## 👤 Default Test Accounts

| Role | Email | Password |
|---|---|---|
| Admin | admin@careermitra.com | admin123 |
| Student | student@careermitra.com | student123 |
| Mentor | rajesh@careermitra.com | mentor123 |

---

## 🔗 API Overview

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/auth/login` | User login |
| POST | `/api/auth/signup` | User registration |
| GET | `/api/mentors` | Get all mentors |
| POST | `/api/bookings` | Book a session |
| POST | `/api/payments/verify` | Verify Razorpay payment |
| GET | `/api/admin/dashboard` | Admin stats |
| GET | `/api/webinars` | List all webinars |

---

## 🌐 Deployment

- **Frontend** — Deployed on [Render](https://render.com)
- **Backend** — Deployed on [Render](https://render.com)
- **Database** — MySQL (hosted)
- **Payments** — Razorpay (test mode)
- **Video Calls** — Jitsi Meet (no setup needed)

---

## 👨‍💻 Developer

**Ritesh Raghav**
B.Tech CSE | Galgotias University

[![GitHub](https://img.shields.io/badge/GitHub-RiteshRaghav-black?style=flat&logo=github)](https://github.com/RiteshRaghav/Carrier_Mitra)

---

