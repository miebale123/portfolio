# Miebale Nigus — Portfolio

Full-stack and mobile engineer in Addis Ababa, Ethiopia. I shipped an offline-first learning app to 6,500+ learners and now build multi-tenant platforms for schools and support teams.

[LinkedIn](https://www.linkedin.com/in/mr-miebale-nigus-b9ba89330/) · miebalen@gmail.com

## Case studies

| Project | What it shows |
| --- | --- |
| [Ahazawi: offline-first learning app](ahazawi.md) | Offline downloads and sync, encrypted media, and speed on low-end Android phones |
| [Multi-tenant e-learning and school platform](e-learning-platform.md) | Tenant isolation built into the data layer, refresh-token reuse detection, one sign-in across web and mobile |
| [Help desk / ITSM platform](help-desk.md) | Moving background jobs into PostgreSQL, restructuring a large codebase, and knowledge suggestions that deflect tickets |
| [Lumina Houses: real-estate marketplace](lumina-houses.md) | A listing lifecycle that keeps unverified brokers from publishing, and the tests around it |
| [Procurement and invoicing tool](procurement-tool.md) | Leading two interns from slipping deadlines to independent delivery |

These projects belong to my employers, so the pages describe the problems and the design, not the source code.

## Public code

[meal-card-system](https://github.com/miebale123/meal-card-system): student QR cards, an Expo app that staff use to scan them, and an API that allows one meal per student per day. The database enforces the limit with a composite primary key on `(student_id, meal_date)`, so it holds even if two scanners read the same card at the same moment. This app later became the campus module of the e-learning platform.

## Other work

- **AI-powered terminal** (BSc thesis, 2025): a terminal in the spirit of Warp. A Rust backend drives the shell and PTY; a React frontend renders the session with an AI assistant that turns natural-language requests into shell commands and explains errors inline.
- **JavaScript course** (2026): I volunteered to record a full JavaScript course, now live on Ahazawi.

## Education

BSc in Computer Science and Engineering, Mekelle Institute of Technology, Mekelle University, 2025. CGPA 3.62/4.00.
