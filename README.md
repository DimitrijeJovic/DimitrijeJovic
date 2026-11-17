# Dimitrije Jović

Junior software developer in Niš, Serbia, working mainly with **C# / .NET**, **Python** and **SQL**. I build database-backed web applications and pay particular attention to access control, data consistency and automated tests.

## Education

- **Master's studies, Information Technologies and Systems** (in progress), Academy of Applied Technical and Preschool Studies Niš
- **Undergraduate applied studies, Modern Computer Technologies** (completed 2026), Academy of Applied Technical and Preschool Studies Niš, Niš Department

## Focus

- Backend development with ASP.NET Core and Flask, REST APIs, and relational database design in MySQL
- Software testing: unit and integration tests (xUnit, Python unittest), tests against a real MySQL server, and checking that a test fails when the rule it covers is broken

## Selected projects

**[AIspit](https://github.com/DimitrijeJovic/aispit-academic-platform)** · Python, Flask, MySQL · bachelor's thesis  
Online exam and assignment-submission platform, designed and developed for my bachelor's thesis. Four user roles (administrator, professor, assistant, student), a Flask application split into four role-based modules, and a normalised 23-table MySQL schema. Deployed and publicly accessible, but not currently in active use. The repository contains the documentation, database design and screenshots; the source code is not published.

**[WatchSphere](https://github.com/DimitrijeJovic/WatchSphere)** · C#, ASP.NET Core, Entity Framework Core, MySQL, Vue 3  
Media catalogue and personal watch tracker. Layered ASP.NET Core Web API with EF Core migrations on MySQL, JWT authentication, BCrypt password hashing, role-restricted admin endpoints, rate-limited sign-in and Swagger documentation. Imports titles from TMDB, TVmaze and Kitsu through one provider interface. 21 xUnit tests cover authentication, authorization, validation, rate limiting and library rules. The frontend is Vue 3 with JavaScript.

**[Clinic Management System](https://github.com/DimitrijeJovic/flask-medical-management-system)** · Python, Flask, MySQL · academic project  
An exam project and one of my first independent applications, later revised with AI-assisted security fixes and tests. Role- and relationship-based access to records for administrators, doctors and nurses. 39 unit and security tests and 10 integration tests against a real MySQL 8 server. Never deployed and never used with real patient data.

**[Millionaire City HTML5](https://github.com/DimitrijeJovic/millionaire-city-html5)** · TypeScript, Phaser 3, Python  
Educational fan-made restoration of a discontinued Flash game, started from a community rebuild: reverse engineering of the original game files, bug fixing, a reimplementation in TypeScript and Phaser 3, Python tools for converting the original SWF files, and 131 automated tests. The original game and its assets belong to their rights holders.

## Technologies

| Area | Technologies |
|---|---|
| Languages | C#, Python, SQL, JavaScript, TypeScript |
| Backend | ASP.NET Core Web API, Entity Framework Core, Flask, REST, JWT |
| Databases | MySQL, relational schema design, transactions |
| Frontend | Vue 3, HTML, CSS, Jinja2, Bootstrap |
| Testing | xUnit, Python unittest, Node.js test runner, integration testing with MySQL |
| Tools | Git, GitHub, Swagger / OpenAPI |

Also studied during coursework: C and Java.

## How I use AI tools

I use AI coding assistants (Claude Code) in development. I set the requirements and the data model, make the key decisions, and verify the result with tests that I first check can fail. Each repository's README states where AI assistance was used.

## Contact

[LinkedIn](https://www.linkedin.com/in/dimitrije-jovic-7b7a8a410/)
