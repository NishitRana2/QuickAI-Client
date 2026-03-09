# QuickAI – Full Stack AI SaaS Application

This project is a **Full Stack AI SaaS Web Application** built using the **PERN Stack (PostgreSQL, Express.js, React.js, Node.js)**. It allows users to access multiple AI-powered tools through a single platform with **secure authentication and subscription-based premium features**.

The application integrates multiple **AI utilities** such as article generation, image generation, resume analysis, and image editing tools. It also includes **user authentication and subscription billing**, making it a complete SaaS-style product.

<img width="1792" height="929" alt="QuickAI App Screenshot" src="https://github.com/user-attachments/assets/placeholder-image.png" />

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [AI Tools](#ai-tools)
- [Installation](#installation)
- [Requirements](#requirements)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [Contributing](#contributing)

---

## Overview

**QuickAI** is a modern **AI-powered SaaS platform** that provides users with multiple productivity tools powered by artificial intelligence.

The platform allows users to **generate articles, blog titles, images, analyze resumes, and edit images using AI**. It also includes **subscription billing**, allowing premium users to unlock advanced AI tools.

The application is built using the **PERN stack** with a **serverless PostgreSQL database hosted on Neon** and **Clerk authentication** for secure user management.

---

## Features

- **User Authentication**
  - Secure sign-up and sign-in using Clerk
  - User profile management
  - Protected routes for authenticated users

- **Subscription Billing**
  - Premium subscription plans
  - Access control for premium AI features

- **Serverless PostgreSQL Database**
  - Database hosted using Neon
  - Efficient and scalable backend data management

- **Modern Full Stack Architecture**
  - React frontend
  - Node.js + Express backend
  - REST APIs for communication
  - PostgreSQL database

---

## AI Tools

The platform includes several AI-powered tools designed to improve productivity.

### Article Generator
Generate full-length articles using AI by providing:
- Article Title
- Desired Article Length

### Blog Title Generator
Generate multiple blog title ideas using:
- Keyword
- Blog Category

### Image Generator
Generate AI images by simply entering a **prompt description**.

### Background Remover
Upload an image and the AI will automatically **remove the background** and generate a transparent image.

### Image Object Remover
Upload an image and specify the **object name** you want removed from the image.

### Resume Analyzer
Upload a resume and get:
- Resume quality score
- Skill analysis
- Improvement suggestions

---

## Installation

To run this project locally, follow these steps:

### 1 Clone the repository

```bash
git clone https://github.com/your-username/quickai-saas-app.git
cd quickai-saas-app
```


### 2 Install frontend dependencies

```bash
cd client
npm install
```

### 3 Setup environment variables

Create a `.env` file in the server directory and configure the following:

```
DATABASE_URL=your_neon_postgres_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
AI_API_KEY=your_ai_api_key
```


### 4 Run frontend application

```bash
cd client
npm start
```

The application will run on:

```
http://localhost:3000
```

---

## Requirements

Make sure the following tools are installed on your system:

- **Node.js (v18 or higher)**
- **npm or yarn**
- **PostgreSQL (or Neon serverless database)**

Install required packages via:

```bash
npm install
```

---

## Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3

### Backend
- Node.js
- Express.js

### Database
- PostgreSQL
- Neon Serverless Postgres

### Authentication
- Clerk

### AI Services
- AI APIs for text generation
- AI APIs for image generation and editing

---

## Usage

After starting the application:

1. Create an account or sign in.
2. Choose from the available **AI tools**.
3. Enter the required inputs such as prompts, keywords, or images.
4. The AI will generate results instantly.

Premium users can access **advanced AI tools and higher usage limits** through the subscription system.

---

## Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Submit a Pull Request

Feel free to open an issue for suggestions, improvements, or bug reports.
