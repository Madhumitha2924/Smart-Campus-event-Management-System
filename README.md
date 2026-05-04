# 🎓 Smart Campus Event Management System

A full-stack web application that digitalizes and automates campus event 
management for colleges and universities. Built using **Spring Boot**, 
**Spring MVC**, **Spring Data JPA**, **Spring Security**, **Thymeleaf**, 
and **MySQL**.

## 🚀 Live Features

### 👨‍💼 Admin Side
- Secure login via Spring Security form authentication
- Create, Edit, Delete events (full CRUD)
- Search events by keyword
- Filter events by department and event type
- View registration statistics on dashboard
- View all students registered per event

### 🎓 Student Side
- Create student account with full validation
- Session-based login (Student ID + Email)
- Browse upcoming events with filters and search
- Register for events with capacity management
- Duplicate registration prevention
- View and cancel registered events

### 🔌 REST API
- `GET /api/events` — All events as JSON
- `GET /api/events/upcoming` — Upcoming events
- `GET /api/events/available` — Events with seats
- `GET /api/events/search?keyword=` — Search events
- `GET /api/events/filter?department=&type=` — Filter events

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Java 17 |
| Framework | Spring Boot 4 |
| Web Layer | Spring MVC |
| Database | Spring Data JPA + Hibernate 7 + MySQL 8 |
| Security | Spring Security + HttpSession |
| Frontend | Thymeleaf + HTML5 + CSS3 |
| Build Tool | Maven |
| Server | Embedded Apache Tomcat |

Author:
C.Madhumitha
