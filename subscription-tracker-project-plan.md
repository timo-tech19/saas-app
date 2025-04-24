# SubTrackr

## Subscription Tracker SaaS App – Project Plan

## 1. Project Overview

A web-based SaaS application to help users track, manage, and optimize their recurring subscriptions. The app will provide reminders, analytics, and payment management, with a focus on integrating payment gateways for learning purposes.

## 2. Core Features

- User authentication (sign up, login, password reset)
- Dashboard with overview of all subscriptions
- Add, edit, and delete subscriptions
- Subscription categorization (e.g., streaming, utilities, software)
- Payment tracking and reminders (email/notification)
- Analytics: monthly/annual spend, upcoming renewals, trends
- Export data (CSV, PDF)
- Payment gateway integration (Fapshi) for premium features
- Responsive UI (mobile & desktop)

## 3. Technical Requirements

### Frontend

- Framework: React (with Vite for fast setup)
- UI Library: MUI or Chakra UI
- State Management: Redux Toolkit or Context API
- Authentication: JWT-based
- Form validation: Yup + Formik

### Backend

- Language: Node.js (Express)
- Database: PostgreSQL (with Prisma ORM)
- Authentication: JWT
- Payment Integration: Fapshi SDK/API
- Email Service: SendGrid or similar
- RESTful API design

### DevOps & Deployment

- Version Control: Git (GitHub)
- CI/CD: GitHub Actions
- Hosting: Vercel/Netlify (frontend), Railway/Heroku (backend)
- Environment variables for secrets

## 4. Milestones & Timeline

1. **Project Setup & Planning** (1 day)
   - Repo initialization, requirements, and architecture
2. **Authentication Module** (2 days)
   - User registration, login, JWT, password reset
3. **Subscription CRUD** (3 days)
   - Add/edit/delete subscriptions, categories
4. **Dashboard & Analytics** (2 days)
   - Overview, charts, export functionality
5. **Reminders & Notifications** (2 days)
   - Email reminders, notification scheduling
6. **Payment Gateway Integration** (3 days)
   - Fapshi setup, premium features
7. **UI/UX Polish & Responsiveness** (2 days)
   - Mobile-first design, accessibility
8. **Testing & QA** (2 days)
   - Unit/integration tests, bug fixes
9. **Deployment & Documentation** (1 day)
   - Deploy to cloud, write user/developer docs

## 5. Stretch Goals

- Multi-user/team support
- Subscription sharing
- AI-based spend optimization suggestions
- Browser extension for quick add

## 6. Learning Objectives

- End-to-end SaaS app development
- Payment gateway integration
- Secure authentication flows
- Modern frontend & backend best practices

---

_This plan is a living document. Adjust milestones and requirements as the project evolves._

- Learn to integrate Fapshi payment gateway
