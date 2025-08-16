# 🚗 Quick Parking App

Developed by **Chandresh Kumari**

The **Quick Parking App** is a smart parking management solution built with [Next.js](https://nextjs.org/).  
It helps users quickly find, book, and pay for parking spaces with seamless integration of maps, payments, and authentication.  

---

## 🔑 Environment Keys
You must configure these before running the app.

```env
NEXT_PUBLIC_MAPS_API_KEY=<GOOGLE_MAPS>

MONGODB_URI=<MONGODB>

NEXT_PUBLIC_STRIPE_APPLICATION_ID=<STRIPE_PUBLIC_KEY>
STRIPE_SECRET_KEY=<STRIPE_PRIVATE_KEY>

RESEND_API_KEY=<RESEND>

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<CLERK_PUBLIC>
CLERK_SECRET_KEY=<CLERK_PRIVATE>
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
````

---

## 🚀 Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

You can start editing the app by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

---

## 📚 Learn More

To learn more about Next.js, check out:

* [Next.js Documentation](https://nextjs.org/docs) – learn about Next.js features and API.
* [Learn Next.js](https://nextjs.org/learn) – an interactive tutorial.

You can also explore the [Next.js GitHub repository](https://github.com/vercel/next.js/) – contributions and feedback are welcome!

---

## ☁️ Deploy on Vercel

The easiest way to deploy the **Quick Parking App** is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

---