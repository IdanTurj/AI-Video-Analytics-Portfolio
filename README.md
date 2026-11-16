# AI Video Analytics — UI Portfolio

A **privacy-safe frontend portfolio demo** of an independently developed AI-powered video analytics application.

> **Project status:** The actual product and its original marketing landing page are still in development. This repository is **not** the product's public website, and the demo is not connected to a running AI backend.

## Explore the interface

- **[Open the frontend source (docs/index.html)](docs/index.html)** — a standalone responsive HTML/CSS/JavaScript demo.
- **[GitHub Pages setup](https://github.com/IdanTurj/AI-Video-Analytics-Portfolio/settings/pages)** — publish the static demo from `main` → `/docs` if you want a browser-accessible preview.
- **Expected Pages URL after deployment:** `https://idanturj.github.io/AI-Video-Analytics-Portfolio/` (not confirmed active).

### What you can explore

1. **Landing-page concept** — a marketing-style introduction to the application's capabilities and use cases.
2. **Customer workspace concept** — a responsive customer dashboard with site selection, camera placeholders, sample incidents, and permissions views.
3. **Engineering notes** — a high-level explanation of the independently developed application's software stack and its private implementation.

The static demo has navigable tabs and UI interactions. It **does not** show real footage, access camera feeds, authenticate customers, connect to a server, or execute AI inference. All customer and event data are synthetic.

## Engineering background: private application

The independently developed application integrates the following components:

| Area | Technologies & functionality |
| --- | --- |
| Computer vision | Python, Ultralytics YOLOv8, PyTorch, OpenCV, NumPy — video processing, object detection and tracking |
| Backend | FastAPI, Uvicorn, Pydantic, SQLite — camera/site management, monitoring rules, incident information |
| Security | Role-based access controls, encrypted camera credentials, multi-factor authentication |
| Engineering workflow | Claude Code, specialized coordinating subagents, Git, PowerShell |

**Important:** These are technologies used in the *private AI platform*. This public repository includes **frontend demonstration code only** and does not claim to implement those backend capabilities.

## Why this repository is public

It showcases frontend implementation, product experience design, responsive layouts, and the user journeys of a more complex private AI application **without exposing the application's name or proprietary implementation**.

**Privacy:** No production source code, credentials, customer identities, camera URLs, video clips, or live data are included.

---

Developed by [Idan Turjeman](https://github.com/IdanTurj) · Software Developer | AI Developer
