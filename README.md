<img src="https://github.com/Yusuprozimemet/projects/blob/main/mermaid-typorax.svg" alt="Mermaid Typorax Diagram" style="width:100%;">

# TyporaX

TyporaX is a modular web app for **language learning** and **content management** with a scalable Flask backend and a browser-based UI.

---

## Overview

- Interactive language learning with AI integration  
- Supports user authentication, practice, audio, and admin tools

---

## Architecture

- **Client:** Browser UI using HTML, CSS, JavaScript; communicates via REST API  
- **Backend:** Flask with modular blueprints (`admin`, `audio`, `auth`, `practice`, `word bank`)  
- **Database:** SQLite (local), PostgreSQL (production)  
- **Storage:** Local file system or Google Cloud Storage  
- **External Services:** OpenAI (LLM), PayPal (payments), SMTP/email providers

---

## Deployment

- Containerized using Docker, with `Procfile` and `render.yaml` for cloud deployment  
- Supports one-command setup on Render, Railway, or Docker environments

---

## Design Principles

- Modular architecture with clear separation of concerns  
- Secure authentication and scalable cloud-ready design  
- Easy switching between local and production databases

---

