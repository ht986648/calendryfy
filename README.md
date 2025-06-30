Here's a redesigned and visually appealing version of your `README.md` with improved structure, formatting, and emphasis on technologies used like **Clerk**, **Drizzle ORM**, **ShadCN**, and **Next.js App Router**:

---

# 📅 Calendar App

A modern **Next.js** 14+ full-stack calendar application to **create, manage, and book events** — featuring **Clerk authentication**, **Drizzle ORM**, **ShadCN UI**, and **App Router**.

![App Screenshot](https://github.com/user-attachments/assets/e502dd34-08f9-467b-9239-6fc00055c3c5)

---

## 🚀 Tech Stack

* ⚡ **Next.js (App Router)**
* 🔐 **Clerk Authentication**
* 🗃️ **Drizzle ORM** (PostgreSQL, MySQL, SQLite, etc.)
* 💅 **ShadCN UI** (based on Radix UI & Tailwind CSS)
* 🧠 **TypeScript**

---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/calendar-app.git
cd calendar-app
```

### 2. Install Dependencies

```bash
npm install
# or
yarn
# or
pnpm install
# or
bun install
```

> Ensure your `.env` file includes valid **Clerk keys** and **database credentials** for Drizzle ORM.

### 3. Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Visit [http://localhost:3000](http://localhost:3000) to view the app.

---

## 🧩 Features

* ✅ **Clerk Authentication** – secure sign-in/sign-up flow
* 🗓️ **Event CRUD** – create, read, update, delete calendar events
* 🔗 **Event Booking** – schedule and reserve events with intuitive UI
* 🎨 **Responsive UI** with ShadCN + Tailwind CSS
* ⚙️ **Drizzle ORM** – type-safe DB queries
* 🔄 **Auto Routing & Server Actions** – powered by Next.js App Router

---

## 📁 Project Structure

```
📦 app/            # App directory (Next.js routing)
┣ 📂 components/   # Reusable UI components (ShadCN)
┣ 📂 lib/          # Utilities (e.g., Clerk, Drizzle config)
┣ 📂 db/           # Drizzle ORM schema & queries
┣ 📂 styles/       # Tailwind configuration
┣ 📄 .env          # Environment variables
┣ 📄 drizzle.config.ts
┗ 📄 next.config.js
```

---

## 🛠️ Environment Variables

Here’s an example `.env` setup for Clerk and Drizzle:

```env
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/login
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/register
NEXT_PUBLIC_CLERK_SIGN_IN_FORCE_REDIRECT_URL=/events
NEXT_PUBLIC_CLERK_SIGN_UP_FORCE_REDIRECT_URL=/events

DATABASE_URL=your_database_url
```

---

## 🔗 Learn More

* 📘 [Next.js Docs](https://nextjs.org/docs)
* 🧪 [Clerk Docs](https://clerk.dev/docs)
* 🧬 [Drizzle ORM Docs](https://orm.drizzle.team/)
* 🖌️ [ShadCN Docs](https://ui.shadcn.dev/)

---

## ⚡ Deploy on Vercel

Deploy this app in seconds using the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

---

## 📸 Additional Screenshots

<img width="1706" alt="Screenshot 2025-06-30 at 6 27 34 PM" src="https://github.com/user-attachments/assets/af3eaad4-66d2-44f9-8f2d-5a3af5ec06d1" />

---

## 💬 Feedback & Contributions

Got feedback or feature suggestions? Open an issue or create a PR — contributions are welcome!

---

Let me know if you'd like a dark mode version, badges (for Vercel, Clerk, etc.), or installation instructions for specific databases (like PostgreSQL or SQLite).
