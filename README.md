# Ax’s Portfolio

A personal developer portfolio built with Django, designed to showcase my coding projects, experience, and personality. This site blends professionalism with a touch of who I am — an organised, methodical full-stack developer with a background in criminology, catering, and a lifelong love of heavy music. The goal is simple: present my work clearly, confidently, and authentically.

---

## Table of Contents

- [Ax’s Portfolio](#axs-portfolio)
  - [Table of Contents](#table-of-contents)
  - [1. Introduction](#1-introduction)
    - [1.1 Aim, Purpose and Goal of the Site](#11-aim-purpose-and-goal-of-the-site)
    - [1.2 Target Audience](#12-target-audience)
  - [2. Features](#2-features)
    - [2.1 Home](#21-home)
    - [2.2 About](#22-about)
    - [2.3 Projects](#23-projects)
    - [2.4 Blog](#24-blog)
    - [2.5 CV](#25-cv)
    - [2.6 Contact](#26-contact)
    - [2.7 Footer](#27-footer)
  - [3. Tech Stack](#3-tech-stack)
    - [Backend](#backend)
    - [Frontend](#frontend)
    - [Database](#database)
    - [Deployment \& Version Control](#deployment--version-control)
  - [4. Planning and Development](#4-planning-and-development)
    - [4.1 Development Notes](#41-development-notes)
    - [4.2 User Stories](#42-user-stories)
      - [4.2.1 Home Page](#421-home-page)
      - [4.2.2 About Page](#422-about-page)
      - [4.2.3 Projects Section](#423-projects-section)
      - [4.2.4 Blog](#424-blog)
      - [4.2.5 CV Page](#425-cv-page)
      - [4.2.6 Contact Page](#426-contact-page)
    - [4.3 Agile Methodology](#43-agile-methodology)
    - [4.4 Branding](#44-branding)
    - [4.5 Testing](#45-testing)
  - [5. Future Enhancements](#5-future-enhancements)
  - [6. Getting Started](#6-getting-started)
    - [6.1 Clone the Repository](#61-clone-the-repository)
    - [6.2 Install Dependencies](#62-install-dependencies)
    - [6.3 Run the Server](#63-run-the-server)
  - [6.4 Deployment (Render)](#64-deployment-render)
    - [6.4.1 Pre-Deployment Setup](#641-pre-deployment-setup)
    - [6.4.2 Render Configuration](#642-render-configuration)
    - [6.4.3 Deployment Steps](#643-deployment-steps)
    - [6.4.4 Post-Deployment Verification](#644-post-deployment-verification)
    - [6.4.5 Summary](#645-summary)
  - [7. Credits and Acknowledgements](#7-credits-and-acknowledgements)
    - [7.1 Credits](#71-credits)
    - [7.2 Acknowledgements](#72-acknowledgements)

---

## 1. Introduction

### 1.1 Aim, Purpose and Goal of the Site

The purpose of Ax’s Portfolio is to provide a clear, professional, and authentic presentation of my work as a junior full-stack developer. It showcases my Code Institute projects, documents my learning journey through a personal blog, and offers a polished snapshot of who I am — in both personality and skill.

The goal is to create a personal platform that reflects my growth, confidence, and evolving developer identity.

### 1.2 Target Audience

This portfolio is aimed at:
- Employers reviewing my coding ability  
- Recruiters looking for clean, professional examples of work  
- Tutors and mentors assessing my growth  
- Fellow developers and students  
- Anyone interested in my development journey  

---

## 2. Features

### 2.1 Home
A clean landing page introducing the site and providing direct navigation to key areas.

### 2.2 About
A personal introduction covering:
- My background and career transition  
- My learning style and problem-solving approach  
- A voice-recorded version of the About page (coming soon — iframe embedded)

### 2.3 Projects
Showcases all four Code Institute portfolio projects with:
- Project summary  
- Key features  
- Tools used  
- Learning outcomes  

### 2.4 Blog
A simple blog system including:
- Individual blog detail pages  
- Learning reflections  
- Behind-the-scenes notes  
- Personal workflow commentary  

### 2.5 CV
A dedicated CV page displaying:
- Both sides of my CV  
- On-page previews  
- Downloadable **PDF** and **.doc** files  

### 2.6 Contact
A direct contact page for enquiries with form validation.

### 2.7 Footer
Footer links include:
- GitHub  
- LinkedIn  

---

## 3. Tech Stack

### Backend
- Django  
- Python  

### Frontend
- HTML  
- CSS  
- (JavaScript coming soon — for embedded audio playback)

### Database
- PostgreSQL (Render deployment)  
- SQLite (local development)

### Deployment & Version Control
- GitHub  
- Render  

---

## 4. Planning and Development

### 4.1 Development Notes

This project follows clean, well-structured Django practices:

- Template inheritance  
- Static file handling  
- Database-backed content (projects & blog)  
- Separate development and production settings  
- Maintainable and readable folder structure  

---

### 4.2 User Stories

#### 4.2.1 Home Page  
As a **visitor**, I want to **immediately understand what the site is about**, so that I **know I’ve reached a developer portfolio**.

#### 4.2.2 About Page  
As a **recruiter**, I want to **quickly learn who Ax is**, so that I **understand his background and personality**.

#### 4.2.3 Projects Section  
As a **potential employer**, I want to **view Ax’s completed projects**, so that I **can evaluate his coding ability and project experience**.

#### 4.2.4 Blog  
As a **developer or tutor**, I want to **read Ax’s reflections and progress**, so that I **can understand his learning journey**.

#### 4.2.5 CV Page  
As a **recruiter**, I want to **view and download Ax’s CV**, so that I **can assess his experience and save the file for review**.

#### 4.2.6 Contact Page  
As a **visitor**, I want to **easily get in touch**, so that **I can contact Ax for opportunities or questions**.

---

### 4.3 Agile Methodology

*(…your full Agile section here — unchanged…)*

---

### 4.4 Branding

*(…your full Branding section here — unchanged…)*

---

### 4.5 Testing

*(…your full Testing section here — unchanged…)*

---

## 5. Future Enhancements

Planned improvements include:

- Embedded voice-recorded “About Me” section  
- Improved UI components and layout refinements  
- Expanded blog system with categories  
- Interactive project timelines  
- Portfolio gallery for future work  

---

## 6. Getting Started

This section outlines how to set up Ax’s Portfolio for local development, installation, and deployment testing.

### 6.1 Clone the Repository

To clone this project from GitHub, run:

`git clone https://github.com/AxDeKlerk/axs-portfolio.git`

### 6.2 Install Dependencies

Once cloned, install the required Python packages using:

`pip install -r requirements.txt`

This installs all necessary dependencies, including Django and the supporting libraries required for development and deployment.

### 6.3 Run the Server

To start the Django development server:

`python manage.py runserver`

The site will be accessible at:

`http://127.0.0.1:8000/`

---

## 6.4 Deployment (Render)

Ax’s Portfolio is deployed on **Render**, using SQLite for local development and PostgreSQL for production. Deployment has been intentionally streamlined due to the lightweight nature of this project.

### 6.4.1 Pre-Deployment Setup

Before deploying, the following steps were completed:

- Installed all dependencies listed in `requirements.txt`  
- Created separate development and production settings files  
- Enabled WhiteNoise for production static file handling  
- Created a `build.sh` script for Render  
- Configured `ALLOWED_HOSTS` and `CSRF_TRUSTED_ORIGINS`  
- Verified static and media file paths  

### 6.4.2 Render Configuration

Render was set up with the following configuration:

- **Service Type:** Web Service  
- **Environment:** Python 3  
- **Build Command:** `pip install -r requirements.txt`  
- **Start Command:** `gunicorn config.wsgi`  
- **Database:** Render PostgreSQL instance  

**Environment Variables:**
- `SECRET_KEY`  
- `DATABASE_URL`  
- `DEBUG=False`  
- `ALLOWED_HOSTS`  
- `CSRF_TRUSTED_ORIGINS`  

### 6.4.3 Deployment Steps

1. Pushed project code to GitHub  
2. Connected the Render service to the GitHub repository  
3. Triggered the first automated deployment  
4. Ran database migrations using Render Shell (`python manage.py migrate`)  
5. Created a Django superuser (`python manage.py createsuperuser`)  
6. Verified static files were collected correctly  
7. Performed full smoke-testing with `DEBUG=False`  

### 6.4.4 Post-Deployment Verification

After deployment, the following checks were successfully completed:

- Navbar and routing functional across all pages  
- Blog detail pages load correctly using slugs  
- Static files (CSS and images) load with no debug mode issues  
- Contact form functions correctly in production  
- CV files download correctly (PDF and DOC)  
- External footer links operate as expected  
- Admin panel accessible with correct credentials  

### 6.4.5 Summary

Deployment to Render was smooth and stable. With WhiteNoise managing static files and PostgreSQL serving production data, the site performs reliably with `DEBUG=False` and demonstrates consistent behaviour in a live environment.

---

## 7. Credits and Acknowledgements

### 7.1 Credits

This project was created independently but draws on the support and documentation of the following resources:

- Django documentation  
- Bootstrap documentation  
- VS Code  
- Render documentation  
- W3Schools  
- Stack Overflow  
- ChatGPT (for debugging assistance and conceptual clarity)

### 7.2 Acknowledgements

Special thanks to:

- **Julia** — for constant support  
- **Friends** — for honest and constructive feedback  
- **Barry** — for ensuring I take breaks and maintain balance  

