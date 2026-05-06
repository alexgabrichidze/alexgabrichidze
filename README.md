# Alexander Gabrichidze

CS student at UW-Madison, B.S. expected December 2026. I am looking for software engineering and backend engineering internships.

I build backend-heavy web apps and the less glamorous pieces that make them hold up: data models, API contracts, auth, media handling, tests, deployment, logs, and the UI paths around them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alex-gab)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gabrichteam@gmail.com)
[![MadDeals](https://img.shields.io/badge/MadDeals-9f1d2a?style=for-the-badge&logo=springboot&logoColor=white)](https://maddeals.app)
[![RecLive](https://img.shields.io/badge/RecLive-007772?style=for-the-badge&logo=python&logoColor=white)](https://reclive.netlify.app)
[![Dotfiles](https://img.shields.io/badge/Dotfiles-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)](https://github.com/alexgabrichidze/dotfiles)

### Currently

- Working on MadDeals: auth, listings, media uploads, background jobs, and production ops.
- Daily-driving an Arch + Hyprland setup and keeping the config public.

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

#### MadDeals [![Live](https://img.shields.io/badge/Live-maddeals.app-9f1d2a?style=flat-square)](https://maddeals.app)

Campus marketplace for verified UW-Madison students, built around trusted accounts, searchable listings, and reliable photo uploads.

- Solo-built and deployed a Spring Boot + React app with PostgreSQL, Flyway, session auth, CSRF protection, media uploads, GitHub Actions automation, and observability.
- Designed an 8-module modular monolith across account, auth, listing, media, notification, abuse, outbox, and shared modules.
- Built S3-compatible media workflows for listing and profile photos with staged upload slots, image validation, HEIC/HEIF support, cleanup jobs, and Cloudflare R2 storage.

#### RecLive [![Live](https://img.shields.io/badge/Live-reclive.netlify.app-007772?style=flat-square)](https://reclive.netlify.app)

Gym crowd app for UW-Madison students who want to know whether Nick or Bakke is worth walking to right now.

- Built the FastAPI backend and data pipeline with Python, MySQL, live occupancy ingestion, forecast-serving APIs, and facility-hours scraping.
- Implemented backend aggregation that transforms raw gym location counts into section-level occupancy metrics.
- Added DB-backed one-time web-push alerts for user-selected low-crowd thresholds.
- Used by 70 daily active users.

#### Time My Gate

Hackathon-built airport timing assistant that helps travelers decide when to head to security and their gate.

- Owned backend architecture and FastAPI recommendation services for combining flight-status data, checkpoint wait estimates, walking-time heuristics, and traveler buffers.
- Normalized messy airport timing inputs into a mobile-friendly leave-now recommendation.
- Helped the team win Best Market Creation at Badger Build Fest 2025.

### Dotfiles [![Repo](https://img.shields.io/badge/Repo-alexgabrichidze%2Fdotfiles-1793D1?style=flat-square&logo=github&logoColor=white)](https://github.com/alexgabrichidze/dotfiles)

My dev environment is part of how I work: Arch Linux + Hyprland on Wayland, with configs for Neovim, tmux, Waybar, Rofi, Yazi, Alacritty, Mako, and shell tooling.

### Technical Focus

- Backend: Java, Spring Boot, Spring MVC, Spring Security, Spring Data JPA, Hibernate, FastAPI, REST APIs
- Data: PostgreSQL, MySQL, Redis, Flyway, SQL indexing, query debugging
- Cloud/infra: Docker, GitHub Actions, Linux, NGINX, Cloudflare R2, Amazon Web Services S3, DigitalOcean
- Frontend: React, TypeScript, Vite, Tailwind CSS, TanStack Query, React Hook Form
- Testing/quality: JUnit, Mockito, Spring Boot Test, MockMvc, Testcontainers, Vitest, CI checks
- Systems interests: authentication, authorization, observability, background jobs, outbox patterns, developer tooling
