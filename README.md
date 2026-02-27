# Internship Recruitment Management System

## 📌 Overview
The **Internship Recruitment Management System** is a dual-user web platform designed to streamline the internship recruitment lifecycle. It bridges the gap between **companies (Interviewers)** and **students (Candidates)** by providing tools for job posting, application tracking, technical assessments, and interview scheduling—all within a unified interface.

---

## 👥 User Roles

### 1. Interviewer (Company/Recruiter)
The **Interviewer Interface** acts as the administrative control center for managing the hiring pipeline.

#### Core Modules
- **Dashboard**
  - Real-time metrics: Applications Received, Shortlisted, Rejected, Active Job Postings.
  - Donut chart breakdown of application statuses.
  - Upcoming Interviews preview.

- **Interview Calendar**
  - Monthly scheduling tool to avoid overlapping interviews.
  - Supports planning for face-to-face rounds.

- **Interview Questions**
  - Create quizzes with titles, durations, and CSV bulk import.
  - Repository of quizzes with options to edit, delete, or download.

- **Internships**
  - Post new internships with details (role, type, field, required skills, salary).
  - Manage active postings with deadlines and linked quizzes.
  - Track applications via Kanban-style board (Pending, Accepted, Rejected).
  - Resume viewing and candidate status updates.

- **Face-to-Face**
  - Final stage for qualified candidates.
  - Schedule interviews with integrated Zoom links.
  - Performance summary categorizing candidates into Outstanding, Excellent, and Good.

- **Message Center**
  - Real-time chat with candidates (WebSockets/Socket.io).
  - File attachments, quick reply templates, bulk messaging.
  - Search and filter conversations by status or job role.
  - Notifications for unread messages.

- **Analytics & Reports**
  - Funnel charts showing drop-off rates across stages.
  - Time-to-hire tracker.
  - Assessment performance breakdown.
  - Candidate sourcing analysis.
  - Export reports as PDF/CSV.

- **Talent Pool**
  - Save strong candidates for future roles.
  - Advanced search and tagging system.
  - Direct outreach via Message Center.
  - Recruiter notes and historical application tracking.

- **Candidate Timeline & Activity Log**
  - Chronological log of all candidate interactions.
  - Tracks automated and manual actions with timestamps.
  - Supports multi-recruiter collaboration and audit trails.

---

### 2. Candidate (Student/Applicant)
The **Candidate Portal** provides a clean, user-friendly interface for job seekers.

#### Core Modules
- **Dashboard**
  - Metrics: Applied, Approved, Rejected applications.
  - Donut chart visualization of progress.
  - Upcoming Interviews reminder.

- **Calendar**
  - Monthly/weekly views for interview and assessment scheduling.
  - Notes feature for personal reminders.

- **Internship (Job Discovery)**
  - Search and filter internships by role, company, or type.
  - Job cards with details: company, role, type, duration, salary, and status.
  - Applied badge to prevent duplicate applications.

- **Applied Internship**
  - Track application lifecycle and assessment requirements.
  - View quiz details, results, and eligibility for next rounds.
  - "View Results" option for detailed performance review.

- **My Profile (Digital Portfolio Builder)**
  - Profile card with avatar, name, education, and headline.
  - About Me section for career goals.
  - Tech stack & skills grid with searchable tags.
  - GitHub, LinkedIn, and portfolio links.
  - Resume upload with secure storage and preview.
  - "View as Recruiter" toggle for profile preview.

---

## 🔧 Technical Highlights
- **Frontend:** React (TypeScript), TailwindCSS  
- **Backend:** Node.js/Django (with support for WebSockets/Socket.io)  
- **Database:** SQL with advanced queries, triggers, and audit logs  
- **File Storage:** Cloud storage integration (AWS S3/Firebase)  
- **Charts & Reports:** Chart.js, Recharts, or ApexCharts for visual analytics  
- **Security:** Role-based access, secure file uploads, and real-time communication  

---

## 🚀 Workflow Summary
1. **Creation:** Interviewer posts an internship and links a quiz.  
2. **Application:** Candidate applies and completes the quiz.  
3. **Screening:** Interviewer reviews applications and quiz scores.  
4. **Selection:** High-scoring candidates move to Face-to-Face.  
5. **Interviewing:** Final interviews scheduled via integrated calendar and Zoom.  
6. **Decision:** Candidates accepted or added to Talent Pool for future roles.  

---

## 🌟 Future Enhancements
- AI-powered screening & proctoring during assessments.  
- Leaderboards & rankings for candidates.  
- Document center for secure offer letters and contracts.  
- Saved jobs/bookmarking for candidates.  
- Company profile management with branding and team accounts.  

---

## 📄 License
This project is intended for educational and portfolio purposes.  
You may adapt and extend it for your own use cases.
