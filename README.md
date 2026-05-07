# Alexander Gabrichidze

CS student at UW-Madison, B.S. expected December 2026. I build backend-heavy web apps: APIs, databases, auth, media handling, tests, deployment, logs, and the UI paths that make the system usable.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alex-gab)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabrichteam@gmail.com)
[![MadDeals](https://img.shields.io/badge/MadDeals-9f1d2a?style=for-the-badge&logo=springboot&logoColor=white)](https://maddeals.app)
[![RecLive](https://img.shields.io/badge/RecLive-007772?style=for-the-badge&logo=python&logoColor=white)](https://reclive.netlify.app)

### Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=flat&logo=amazons3&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=111111)

### Featured Work

#### MadDeals

Campus marketplace for verified UW-Madison students, built around trusted accounts, searchable listings, and reliable photo uploads.

- Solo-built and deployed a Spring Boot + React app with 22 HTTP routes, 11 Flyway migrations, session auth, CSRF protection, media uploads, GitHub Actions automation, and observability.
- Split the backend into 8 domain modules across account, auth, listing, media, notification, abuse, outbox, and shared code.
- Built S3-compatible media workflows for listing and profile photos with staged upload slots, image validation, HEIC/HEIF support, cleanup jobs, and Cloudflare R2 storage.
- Maintained 115 test files across backend, frontend, integration, native HEIF, and ops checks before packaging the production JAR.

[![Live](https://img.shields.io/badge/Live-maddeals.app-9f1d2a?style=flat)](https://maddeals.app)

#### RecLive

Gym crowd app for UW-Madison students deciding whether Nick or Bakke is worth walking to right now.

- Built the FastAPI backend and data pipeline with Python, MySQL, live occupancy ingestion, forecast-serving APIs, and facility-hours scraping.
- Implemented backend aggregation that transforms raw gym location counts into section-level occupancy metrics.
- Added database-backed one-time web-push alerts for user-selected low-crowd thresholds.
- Used by 70 daily active users.

[![Live](https://img.shields.io/badge/Live-reclive.netlify.app-007772?style=flat)](https://reclive.netlify.app)

#### Time My Gate

Hackathon airport timing assistant that turned flight-status data, checkpoint waits, walking-time heuristics, and traveler buffers into a leave-now recommendation. Helped the team win Best Market Creation at Badger Build Fest 2025.

[![Event](https://img.shields.io/badge/Event-Badger_Build_Fest_2025-6b7280?style=flat)](https://techexplorationlab.wisc.edu/2025/11/17/badger-build-fest-2025-a-breakthrough-weekend-of-creativity-collaboration-and-venture-building/)

### Developer Setup

My dev environment is part of how I work: Arch Linux + Hyprland on Wayland, with configs for Neovim, tmux, Waybar, Rofi, Yazi, Alacritty, Mako, and shell tooling.

[![Repo](https://img.shields.io/badge/Repo-alexgabrichidze%2Fdotfiles-1793D1?style=flat&logo=github&logoColor=white)](https://github.com/alexgabrichidze/dotfiles)
