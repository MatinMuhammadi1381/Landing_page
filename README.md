# EdgeAI Landing Page

**English** · [فارسی](#فارسی)

A modern AI SaaS landing page built with React, TypeScript, Tailwind CSS, and Vite. The interface is designed to introduce an AI business platform through a polished, responsive, and conversion-oriented single-page experience.

## Sections

- Hero section with AI-focused messaging and call-to-action
- Trusted brands and partner logos
- AI services overview
- About and mission section
- Pricing plans with feature lists
- Final call-to-action section
- Responsive navigation and footer
- Theme state management with Zustand

## Tech Stack

- React 19
- TypeScript
- Vite
- Tailwind CSS 4
- Zustand
- ESLint

## Getting Started

~~~bash
git clone https://github.com/MatinMuhammadi1381/Landing_page.git
cd Landing_page
npm ci
npm run dev
~~~

Open the local URL shown by Vite, usually http://localhost:5173.

On Windows, run `INSTALL-DEPENDENCIES.bat` to install the dependencies from the committed lockfile.

## Available Scripts

~~~bash
npm run dev       # Start the development server
npm run build     # Type-check and create a production build
npm run preview   # Preview the production build
npm run lint      # Run ESLint
~~~

## Project Structure

~~~text
src/
├── components/
│   ├── sections/ # Hero, services, pricing, brands, and about sections
│   ├── cards/    # Reusable information and service cards
│   ├── elements/ # Navbar and footer elements
│   └── shared/   # Buttons, titles, paragraphs, and containers
├── store/        # Theme state
├── utils/        # Services and pricing data
├── App.tsx       # Page composition
└── main.tsx      # Application entry point
~~~

## Scope

This repository is a front-end landing page. The forms, pricing buttons, and marketing content are presentation components and are not connected to a production SaaS backend or billing system.

---

## فارسی

یک صفحهٔ فرود واکنش‌گرا برای معرفی یک پلتفرم هوش مصنوعی با نام EdgeAI. این نمونه با React، TypeScript، Tailwind CSS 4 و Vite ساخته شده است.

### بخش‌ها

- معرفی اصلی و دکمهٔ اقدام، لوگوهای برندها و خدمات هوش مصنوعی
- بخش‌های معرفی، قیمت‌گذاری و دعوت به اقدام
- پیمایش واکنش‌گرا و وضعیت پوسته با Zustand

### فناوری‌ها و راه‌اندازی

React 19، TypeScript، Vite، Tailwind CSS 4، Zustand و ESLint. به Node.js و npm نیاز دارید:

~~~bash
git clone https://github.com/MatinMuhammadi1381/Landing_page.git
cd Landing_page
npm ci
npm run dev
~~~

در ویندوز، `INSTALL-DEPENDENCIES.bat` را اجرا کنید. نشانی محلی معمولاً `http://localhost:5173` است. `npm run build` بررسی TypeScript و ساخت نسخهٔ تولید را انجام می‌دهد؛ برای پیش‌نمایش از `npm run preview` استفاده کنید.

### محدوده

این مخزن نمونهٔ رابط کاربری است؛ فرم‌ها، قیمت‌ها و دکمه‌ها به سرویس واقعی هوش مصنوعی، حساب کاربری یا پرداخت متصل نیستند.