# EduMentor AI - Specification

## 🧑‍🎓 User Stories

### Student
- As a student, I want to upload my homework/assignments so I can receive feedback.
- As a student, I want to view past feedback and track my progress over time.
- As a student, I want to book tutoring sessions easily.

### Tutor
- As a tutor, I want to review student submissions and add personalized feedback.
- As a tutor, I want to track student performance and flag areas of concern.
- As a tutor, I want to see my schedule and session history.

### Admin
- As an admin, I want to manage users and monitor platform activity.
- As an admin, I want to oversee referral usage, billing, and analytics.

---

## 👥 Roles

- **Student**: Uploads work, receives feedback, views dashboard.
- **Tutor**: Reviews submissions, gives feedback, manages sessions.
- **Admin**: Manages users, system settings, and platform metrics.

---

## 📌 Core Features

### Authentication & Roles
- JWT-based login system
- Role-based routing (student/tutor/admin)

### Assignment & Feedback
- Upload assignments (PDF, DOCX, images, or text)
- AI-generated feedback using **Google Gemini API**
- Manual feedback from tutors
- Feedback history per assignment

### AI Integration (via Gemini)
- Writing analysis (clarity, grammar, structure)
- Math-based hints from question content
- Custom prompt tuning per subject type

### Tutor Dashboard
- View list of students
- Submission queue with feedback tools
- Analytics on each student’s progress

### Student Dashboard
- Upload interface with preview
- Feedback viewer
- Progress graph (scores, flags, hints used)

### Booking & Billing
- Session calendar (FullCalendar or custom)
- Biweekly billing export (PDF)
- Referral discount tracker

### Admin Panel
- View active users and platform stats
- Adjust access and monitor usage
- Review system logs and analytics

---

## 🧱 MVP Scope (Minimum Viable Product)

- Auth system
- Assignment upload + AI feedback using Gemini
- Student and tutor dashboards
- Basic analytics (line/bar charts)
- Booking calendar (tutor view)
- Exportable invoices (manual)

---

## 📅 Milestones (High-Level)

1. Project Setup & Auth (2–3 days)
2. Core Models & Gemini Feedback API (5–7 days)
3. Frontend Dashboards (7–10 days)
4. Analytics & Reports (3–4 days)
5. Booking & Invoicing (4–5 days)
6. Deployment & CI/CD (3–4 days)
