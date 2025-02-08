# Blog Platform

A full-stack blog platform built using Next.js for both frontend and backend, PostgreSQL via Supabase for data storage, and deployed on Vercel.

## Features
- User authentication with JWT or Supabase Auth
- Create, read, update, and delete blog posts
- Commenting system on blog posts
- Secure password hashing using bcrypt
- Automatic CI/CD deployment via GitHub and Vercel

## Tech Stack
- **Frontend & Backend:** Next.js
- **Database:** PostgreSQL via Supabase
- **Authentication:** JWT / Supabase Auth
- **Password Hashing:** bcrypt
- **Deployment:** Vercel

## Architecture Overview

- **Next.js Frontend:** Handles rendering, user interactions, and client-side routing.
- **Next.js Backend:** Provides APIs for posts, authentication, and comments.
- **PostgreSQL via Supabase:** Stores user data, blog posts, and comments.
- **Vercel:** Hosts the application with automatic CI/CD from GitHub.

![Screenshot 2025-02-08 054337](https://github.com/user-attachments/assets/2130e8dc-5af9-4b52-85cd-78e7f32f762a)


## Database Schema

![Screenshot 2025-02-08 054504](https://github.com/user-attachments/assets/a0d65efc-a3f6-4ff5-a6fd-743faa26adbd)


## API Documentation

![Screenshot 2025-02-08 054429](https://github.com/user-attachments/assets/d1aa6335-ccf5-49bf-b0b8-c31bd107f6fb)


## Deploy Workflow

![Screenshot 2025-02-08 054519](https://github.com/user-attachments/assets/3b185fb6-2755-4dab-8789-fa3fdf7a41e0)


## Getting Started

### Prerequisites
- Node.js v14+
- PostgreSQL via Supabase account
- Vercel account

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blog-platform.git
   cd blog-platform
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables in a `.env.local` file:
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
   JWT_SECRET=your-jwt-secret
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

