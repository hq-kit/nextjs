# Next.js + Better Auth + Prisma Starter Kit

🚀 A starter kit for building modern web applications with **Next.js 16**, **Better Auth**, **Prisma**, and **hq-ui**.

## 📌 Features

- ✅ **Next.js 16** with App Router
- ✅ **Better Auth** for authentication
- ✅ **Prisma** for database management (Rust-Free Engine)
- ✅ **hq-ui** for UI components
- ✅ **Dashboard** for authenticated users
- ✅ TypeScript support

## 🆕 Recent Updates

- **Prisma 7**: Updated to the latest version `^7.1.0`.
- **Tailwind CSS v4**: Now running on Tailwind CSS v4.

## 📦 Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/hq-kit/nextjs.git
   cd nextjs-better-auth
   ```
2. Install dependencies:
   ```sh
   bun install
   ```
3. Set up environment variables:

   ```sh
   cp .env.example .env
   ```

   Fill in the necessary values in the `.env` file.

4. Set up the database:

   ```sh
   bunx prisma migrate dev
   ```

5. Start the development server:
   ```sh
   bun run dev
   ```

## 🚀 Usage

- Run `bun run dev` to start the development server.
- Use `bunx prisma studio` to manage your database visually.
- Customize authentication using Better Auth settings.

## 🛠️ Tech Stack

- **Next.js 16** - React framework
- **Better Auth** - Authentication
- **Prisma** - Database ORM (v7)
- **Tailwind CSS 4** - Utility-first CSS framework
- **hq-ui** - UI components
- **TypeScript** - Type safety

---

Made with ❤️ by [DQ AL HQ](https://github.com/dq-alhq)
