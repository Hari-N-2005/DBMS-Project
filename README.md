# 🗳️ EzyVote — College Clubs & Cells Voting System

A secure and scalable full-stack voting platform designed for managing elections within college clubs and cells.  
Ensures fair participation, role-based access control, and real-time analytics powered by a robust MySQL database.

---

## 🚀 Features

✔ Role-based access — Admin & Voter  
✔ One-vote-per-user enforcement via DB triggers  
✔ Real-time result visualization using interactive charts  
✔ Secure authentication using JWT  
✔ Voting logs & audit trails for transparency  
✔ Admin dashboard for election management  
✔ Fully normalized MySQL schema ensuring data integrity  

---

## 🛠️ Tech Stack

| Layer | Technology |
|------|------------|
| Frontend | React.js, HTML, CSS, Chart.js |
| Backend | Node.js + Express.js |
| Database | MySQL |
| Version Control | Git & GitHub |

---

## 📊 Database Design Concepts Used

- ER modeling & referential integrity
- Foreign keys, triggers, constraints
- Joins & aggregate queries for vote counts
- Transactions to avoid race conditions
- Views for result analytics

**Core Tables:** Users, Clubs, Elections, Candidates, Votes, Audit Logs
