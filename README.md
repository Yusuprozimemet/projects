<img src="https://github.com/Yusuprozimemet/projects/blob/main/mermaid-typorax.svg" alt="Mermaid Typorax Diagram" style="width:100%;">

# TyporaX

TyporaX is a modular web application for **language learning** and **content management**.  
It is designed with scalability and modularity in mind, combining a Flask backend, RESTful API endpoints, and a clean browser-based interface.

---

## Overview

TyporaX enables users to learn and manage language content interactively through a combination of web modules and AI integration.  
It supports user authentication, practice exercises, audio handling, and administrative tools.

---

## Architecture

### Client
- Browser-based UI built with **HTML**, **CSS**, and **JavaScript**
- Communicates via REST API with Flask backend

### Backend
- **Flask** application structured using **blueprints** for modularity:
  - `admin`
  - `audio`
  - `auth`
  - `practice`
  - `word bank`
- Implements business logic, authentication, email notifications, and external API integration

### Database
- **SQLite** for local development and testing  
- **PostgreSQL** for production deployments

### Storage
- User-generated and text files stored either **locally** or in **Google Cloud Storage**

### External Services
- **OpenAI** integration for language model features  
- **PayPal** for payment processing  
- **SMTP** or third-party email providers for notification delivery

---

## DevOps and Deployment

TyporaX supports cloud and containerized deployments for easy scaling and continuous integration.

- **Containerization:** Docker, Procfile  
- **Deployment Configuration:** `render.yaml`, `requirements.txt`, deployment documentation  
- Supports one-command setup for Render, Railway, or Docker-based environments

---

## Key Design Principles

- Modular architecture via Flask blueprints  
- Clear separation of concerns  
- Secure authentication and data handling  
- Scalable and cloud-ready configuration  
- Easy switching between local (SQLite) and production (PostgreSQL) databases

---

## Summary

**TyporaX** combines robust backend engineering with educational practicality, offering a complete platform for interactive language learning, secure user management, and scalable deployment in modern web infrastructure.
