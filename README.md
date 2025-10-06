# Tech Titans E-commerce 🛍️

> A modern full-stack e-commerce platform built with Next.js, featuring secure authentication and integrated payments.

![Next.js](https://img.shields.io/badge/Next.js-14-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)
![Tailwind](https://img.shields.io/badge/Tailwind-3.0-38bdf8)

## ✨ Key Features

- 🔐 **Secure Authentication**
  - JWT token-based auth
  - Social login integration
  - Role-based access control

- 🛍️ **Shopping Experience** 
  - Product search & filtering
  - Cart management with Zustand
  - Secure Stripe checkout
  
- 📱 **Modern UI/UX**
  - Responsive design
  - Dark/Light themes
  - Loading states
  - Toast notifications

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/ARASIF1-6/tech-titans_frontend.git

# Install dependencies
cd tech-titans
npm install

# Setup environment variables
cp .env.example .env.local

# Start development server
npm run dev
```

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| Frontend | Next.js 14, React, TypeScript |
| Styling | Tailwind CSS, Shadcn UI |
| State | Zustand |
| Forms | React Hook Form, Zod |
| Payments | Stripe |
| Authentication | NextAuth.js, JWT |

## 📁 Project Structure

```
tech-titans/
├── src/
│   ├── app/              # Next.js app router
│   ├── components/       # Reusable components
│   ├── lib/             # Utilities & configs
│   └── store/           # Zustand stores
├── public/              # Static assets
└── tests/              # Test suites
```

## 🔑 Environment Variables

Create a `.env.local` file:

```env
NEXT_PUBLIC_API_URL=
STRIPE_SECRET_KEY=
NEXTAUTH_SECRET=
```

## 👥 User Roles

### Customer
- Browse products
- Manage cart & wishlist
- Place orders
- Track deliveries

### Seller
- Manage products
- Process orders
- View analytics

### Admin
- User management
- System settings
- Monitor platform

## 💻 Development

```bash
# Run tests
npm test

# Build for production
npm run build

# Start production server
npm start
```
