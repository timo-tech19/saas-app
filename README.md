# SubTrackr

A SaaS application for tracking and managing all your subscriptions in one place. SubTrackr helps users monitor spending, receive reminders for upcoming payments, and gain insights into their subscription habits.

## Features

- User authentication (sign up, login, password reset)
- Dashboard overview of all subscriptions
- Add, edit, and delete subscriptions
- Categorize subscriptions (streaming, utilities, software, etc.)
- Payment tracking and reminders (email/notification)
- Analytics: monthly/annual spend, upcoming renewals, trends
- Export data (CSV, PDF)
- Payment gateway integration (Fapshi) for premium features
- Responsive UI (mobile & desktop)

## Tech Stack

### Frontend

- React (with Vite)
- UI Library: MUI or Chakra UI
- State Management: Redux Toolkit or Context API
- Form validation: Yup + Formik

### Backend

- Node.js (Express)
- PostgreSQL (with Prisma ORM)
- JWT Authentication
- Payment Integration: Fapshi SDK/API
- Email Service: SendGrid or similar

### DevOps & Deployment

- Version Control: Git (GitHub)
- CI/CD: GitHub Actions
- Hosting: Vercel/Netlify (frontend), Railway/Heroku (backend)

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/subtrackr.git
   cd subtrackr
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up environment variables:**
   - Copy `.env.example` to `.env` and fill in required values.
4. **Run the development server:**
   ```bash
   npm run dev
   ```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)
