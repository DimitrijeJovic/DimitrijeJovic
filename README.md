# Dimitrije Jović

**Computer Science Student & Software Developer**  
Focused on backend engineering, relational database design, application security, and full-stack web systems.

---

## About Me

I am a Computer Science student focused on software engineering, web application development, database systems, and practical problem-solving.

I enjoy building structured applications, designing backend systems, working with relational databases, and exploring modern development workflows. My work emphasizes architectural clarity, data integrity, secure authentication, and thorough technical documentation.

---

## 🌟 Featured Project

### [AIspit — Academic Examination & Assignment Management Platform](https://github.com/DimitrijeJovic/aispit-academic-platform)

**AIspit** is a full-stack academic examination and coursework submission platform engineered to manage university-level examinations, assignment workflows, and integrity verification.

- **Technology Stack:** Python, Flask, MySQL 8 (InnoDB), Jinja2, HTML5, CSS3, JavaScript
- **Role-Based Access Control:** Four distinct personas with strict boundary enforcement:
  - **Administrator:** Complete platform governance, academic program scoping, curriculum management, and user lifecycle administration.
  - **Professor:** Exam authoring, modular question bank management, test scheduling, code activation, and grade finalization.
  - **Assistant:** Grading support, candidate submission review, and evaluation notes.
  - **Student:** Time-bounded online examination interface with client-side anti-cheat detection, plus assignment submission workflows.
- **System Architecture:** 5-tier production deployment request pipeline:  
  `Browser ⇄ Nginx (Reverse Proxy & TLS) ⇄ Gunicorn (WSGI) ⇄ Flask Application (6 Modular Blueprints) ⇄ MySQL 8.0`
- **Database Engineering:** Normalized relational schema comprising **23 operational tables** across 4 functional domains, featuring immutable snapshot execution tables for tamper-evident exam history.
- **Application Security:** Cryptographic submission verification via **HMAC-SHA256 (MAC)**, password hashing with **bcrypt**, session protection, role enforcement decorators, and parameterized SQL queries eliminating SQL injection.
- **Quality Assurance:** Comprehensive test suite of **88 unit and integration tests** validating authentication, role access, and end-to-end exam state machines.

👉 **Explore the full architectural specifications, schema diagrams, and security documentation:**  
[**View the AIspit Repository →**](https://github.com/DimitrijeJovic/aispit-academic-platform)

---

## Technical Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Backend & Languages** | Python, Flask, C, Java, JavaScript |
| **Databases & Storage** | MySQL 8.0, Relational Schema Design, SQL Prepared Statements, Query Optimization |
| **Frontend Development** | HTML5, CSS3, JavaScript, Jinja2 Templates, Responsive UI |
| **Architecture & Security** | RESTful Architecture, Role-Based Access Control (RBAC), HMAC-SHA256, bcrypt, Session Security |
| **Tools & Platforms** | Git, GitHub, Linux / Nginx Deployment, WSGI (Gunicorn), VS Code |

---

## Other Projects

- **[WatchSphere](https://github.com/DimitrijeJovic/WatchSphere)** — Full-stack media catalogue and personal watch tracker for anime, movies, and series built with ASP.NET Core (.NET 10), Vue 3, and MySQL. Features multi-provider search integration (TMDB, TVmaze, Kitsu), progress tracking, and background sync.
- **[Flask Medical Management System](https://github.com/DimitrijeJovic/flask-medical-management-system)** — Healthcare management web application built with Flask, MySQL, Bootstrap, and role-based authentication for clinical scheduling and patient records.
- **[Millionaire City HTML5](https://github.com/DimitrijeJovic/millionaire-city-html5)** — Independent clean-room HTML5 reimplementation of the classic city-building simulation game using TypeScript and Phaser 3.

---

## GitHub Highlights

- **Flagship Project:** [aispit-academic-platform](https://github.com/DimitrijeJovic/aispit-academic-platform)
- **Primary Focus:** Backend Development, Relational Databases & Application Architecture
