<div align="center">
  <h1>🚀 Next.js 14 Shadcn UI Dashboard Template</h1>
  <p><strong>A modern, production-ready admin dashboard template built with Next.js App Router</strong></p>
  <p>
    <img src="https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js" alt="Next.js">
    <img src="https://img.shields.io/badge/TypeScript-5.x-blue?style=flat-square&logo=typescript" alt="TypeScript">
    <img src="https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=flat-square&logo=tailwindcss" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/Shadcn%2Fui-Components-000?style=flat-square" alt="Shadcn/ui">
    <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
  </p>
</div>

## ✨ Features

- **⚡ Next.js 14** - App Router, Server Components, and latest features
- **🎨 Shadcn/ui** - Beautiful and accessible React components
- **🎯 TypeScript** - Full type safety throughout the application
- **🎭 Tailwind CSS** - Utility-first CSS framework
- **🔐 NextAuth.js** - Complete authentication solution
- **📊 Data Tables** - Advanced tables with TanStack Table
- **📝 Forms** - React Hook Form with Zod validation
- **🎨 Dark Mode** - Built-in theme switching
- **📱 Responsive** - Mobile-first responsive design
- **🎯 State Management** - Zustand for global state
- **🔍 Search Params** - Type-safe URL state with Nuqs
- **🎪 Animations** - Beautiful animations and transitions
- **📦 File Upload** - UploadThing integration
- **📈 Charts** - Recharts for data visualization
- **🎨 Icons** - Lucide React icons
- **🧪 Code Quality** - ESLint, Prettier, Husky

## 🏗️ Tech Stack

### **Core**
- **Framework:** [Next.js 14](https://nextjs.org) - React framework with App Router
- **Language:** [TypeScript](https://www.typescriptlang.org) - Static type checking
- **Styling:** [Tailwind CSS](https://tailwindcss.com) - Utility-first CSS
- **Components:** [Shadcn/ui](https://ui.shadcn.com) - Reusable component library

### **Authentication & Security**
- **Auth:** [NextAuth.js v5](https://authjs.dev) - Authentication library
- **Validation:** [Zod](https://zod.dev) - Schema validation

### **State & Data Management**
- **Global State:** [Zustand](https://zustand-demo.pmnd.rs) - Lightweight state management
- **URL State:** [Nuqs](https://nuqs.47ng.com) - Type-safe search params
- **Tables:** [TanStack Table](https://tanstack.com/table) - Powerful data tables
- **Forms:** [React Hook Form](https://react-hook-form.com) - Performant forms

### **UI & UX**
- **Icons:** [Lucide React](https://lucide.dev) - Beautiful icons
- **Charts:** [Recharts](https://recharts.org) - Chart library
- **Drag & Drop:** [DND Kit](https://dndkit.com) - Modern drag and drop
- **File Upload:** [UploadThing](https://uploadthing.com) - File uploads
- **Toast:** [Sonner](https://sonner.emilkowal.ski) - Toast notifications

### **Development Tools**
- **Linting:** [ESLint](https://eslint.org) - Code linting
- **Formatting:** [Prettier](https://prettier.io) - Code formatting
- **Hooks:** [Husky](https://typicode.github.io/husky) - Git hooks
- **Staging:** [Lint Staged](https://github.com/okonet/lint-staged) - Pre-commit checks

## 📋 Prerequisites

- **Node.js** 18.17 or later
- **pnpm** (recommended) or npm/yarn
- **Git** for version control

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/alpredovandy/next-shadcn-dashboard-template.git
cd next-shadcn-dashboard-template
```

### 2. Install Dependencies

```bash
pnpm install
# or
npm install
# or
yarn install
```

### 3. Environment Setup

```bash
# Copy environment variables
cp env.example.txt .env.local
```

Add your environment variables to `.env.local`:

```env
# Authentication
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your-secret-key-here

# GitHub OAuth (optional)
GITHUB_ID=your-github-id
GITHUB_SECRET=your-github-secret
```

### 4. Start Development Server

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📜 Available Scripts

| Script | Description |
|--------|-------------|
| `pnpm dev` | Start development server |
| `pnpm build` | Build for production |
| `pnpm start` | Start production server |
| `pnpm lint` | Run ESLint |
| `pnpm format` | Format code with Prettier |
| `pnpm prepare` | Setup Husky hooks |

## 📁 Project Structure

```
next-shadcn-dashboard-template/
├── app/                    # Next.js App Router
│   ├── (auth)/            # Authentication routes
│   │   └── (signin)/      # Sign in page
│   ├── dashboard/         # Dashboard routes
│   │   ├── employee/      # Employee management
│   │   ├── product/       # Product management
│   │   ├── profile/       # User profile
│   │   ├── kanban/        # Kanban board
│   │   └── layout.tsx     # Dashboard layout
│   ├── globals.css        # Global styles
│   └── layout.tsx         # Root layout
├── components/            # Reusable components
│   ├── ui/               # Shadcn/ui components
│   ├── layout/           # Layout components
│   └── modal/            # Modal components
├── lib/                  # Utility functions
├── public/               # Static assets
├── auth.config.ts        # NextAuth configuration
├── auth.ts              # NextAuth setup
├── middleware.ts        # Next.js middleware
└── tailwind.config.js   # Tailwind configuration
```

## 🎯 Pages & Features

### **Authentication**
- **Sign In** - Social login (GitHub) and email authentication
- **Protected Routes** - Automatic redirect for unauthenticated users
- **Session Management** - Persistent authentication state

### **Dashboard**
- **Analytics Cards** - Key metrics display
- **Charts & Graphs** - Data visualization with Recharts
- **Responsive Layout** - Mobile-friendly design

### **Data Management**
- **Employee Table** - CRUD operations with server-side features
- **Product Table** - Inventory management interface
- **Advanced Filtering** - Search, sort, and pagination
- **Bulk Actions** - Multi-select operations

### **User Experience**
- **Profile Management** - Multi-step form with validation
- **Kanban Board** - Drag-and-drop task management
- **File Upload** - Image and document handling
- **Dark/Light Mode** - Theme switching

### **Additional Features**
- **Toast Notifications** - User feedback system
- **Loading States** - Enhanced UX during operations
- **Error Handling** - Graceful error management
- **404 Page** - Custom not found page

## 🎨 Customization

### **Theme Configuration**

Customize colors in `tailwind.config.js`:

```js
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: {
          50: '#eff6ff',
          // ... more colors
        },
      },
    },
  },
}
```

### **Adding Components**

Install new Shadcn/ui components:

```bash
pnpx shadcn-ui@latest add [component-name]
```

### **Environment Variables**

| Variable | Description | Required |
|----------|-------------|----------|
| `NEXTAUTH_URL` | Application URL | ✅ |
| `NEXTAUTH_SECRET` | Auth encryption key | ✅ |
| `GITHUB_ID` | GitHub OAuth Client ID | ❌ |
| `GITHUB_SECRET` | GitHub OAuth Client Secret | ❌ |

## 🚢 Deployment

### **Vercel (Recommended)**

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

### **Docker**

```dockerfile
FROM node:18-alpine AS base

# Install dependencies
FROM base AS deps
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=production

# Build the app
FROM base AS builder
WORKDIR /app
COPY . .
COPY --from=deps /app/node_modules ./node_modules
RUN npm run build

# Run the app
FROM base AS runner
WORKDIR /app
COPY --from=builder /app/.next ./.next
COPY --from=builder /app/public ./public
COPY --from=builder /app/package.json ./package.json
COPY --from=deps /app/node_modules ./node_modules

EXPOSE 3000
CMD ["npm", "start"]
```

### **Other Platforms**
- **Netlify** - Set build command to `npm run build`
- **Railway** - Connect GitHub repo and deploy
- **DigitalOcean** - Use App Platform

## 🔧 Development Guidelines

### **Code Style**
- Use TypeScript for all files
- Follow ESLint and Prettier configurations
- Use functional components with hooks
- Implement proper error boundaries

### **Component Guidelines**
- Keep components small and focused
- Use composition over inheritance
- Implement proper TypeScript interfaces
- Add JSDoc comments for complex functions

### **State Management**
- Use Zustand for global state
- Use React Hook Form for form state
- Use Nuqs for URL state management
- Avoid prop drilling with context when needed

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### **Development Setup**

```bash
# Clone your fork
git clone https://github.com/your-username/next-shadcn-dashboard-template.git

# Install dependencies
pnpm install

# Start development
pnpm dev
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **[Shadcn](https://github.com/shadcn)** - For the amazing component library
- **[Vercel](https://vercel.com)** - For Next.js and hosting platform
- **[Radix UI](https://www.radix-ui.com)** - For unstyled, accessible components
- **[Tailwind CSS](https://tailwindcss.com)** - For the utility-first CSS framework
