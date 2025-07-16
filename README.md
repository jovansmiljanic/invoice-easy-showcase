# Invoice Easy — Next.js Invoice Management System

**Invoice Easy** is a simple yet powerful invoicing app that lets individuals and businesses create, edit, and manage invoices with ease—all in one place. Its intuitive interface and smart features streamline your invoicing process, making it perfect for freelancers and small businesses who need professional invoicing in minutes.

🔗 **[View Live Demo](https://invoice-easy.com)**    |    📧 **[Contact for Demo](mailto:smiljanicjovan9@gmail.com)**

## 📊 Current Status

- **Development Stage:** Beta
- **Active Users:** 20+ real businesses in 3 countries
- **Performance Score:** 95+ (Lighthouse)
- **Security Audit:** Passed

## ✨ Features

- 📱 Fully responsive dashboard UI optimized for all devices
- 🌍 Internationalization (i18n) with Next-Intl
- 🔐 Secure authentication (NextAuth v5) with 2FA support
- 📄 Dynamic invoice management with real-time editing and preview
- 🎨 Professional PDF invoice generation with React PDF Renderer
- ⚡ Real-time toast notifications (Sonner) and comprehensive form validation
- 🌗 Light/dark mode toggle with Next-Themes
- 📧 Professional email templates with React Email + Resend
- 🧩 Modern UI components built with Radix UI
- 💾 Robust data persistence with Prisma ORM
- 📊 Interactive charts and analytics with Recharts
- 🎬 Smooth animations powered by Framer Motion
- ☁️ Cloud file storage with Backblaze B2
- 🤖 AI-powered features with OpenAI integration
- 📈 Performance monitoring with Vercel Analytics
- 🧪 Comprehensive testing with Vitest

## 🛠️ Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS + Tailwind Animate
- **UI Components:** Radix UI (Alert Dialog, Avatar, Checkbox, Dialog, Dropdown, etc.)
- **Authentication:** NextAuth.js v5 (Beta) with Prisma Adapter
- **Forms:** React Hook Form with Zod validation
- **Charts:** Recharts for data visualization
- **Database:** PostgreSQL with Prisma ORM
- **Email:** React Email Components + Resend
- **PDF Generation:** React PDF Renderer
- **File Storage:** Backblaze B2 Cloud Storage
- **Animations:** Framer Motion
- **Testing:** Vitest + React Testing Library + Jest DOM
- **Analytics:** Vercel Analytics + Speed Insights
- **Internationalization:** Next-Intl
- **Theming:** Next-Themes (Light/Dark mode)
- **AI Integration:** OpenAI API
- **Date Handling:** Date-fns + React Day Picker
- **Icons:** Lucide React + React Icons
- **Utilities:** Class Variance Authority, CLSX, Tailwind Merge

## 📸 Screenshots

### 🏠 Dashboard Overview
![Dashboard](https://www.invoice-easy.com/dashboard-light.webp)
*Clean, intuitive dashboard showing invoice metrics and recent activity*

### 📄 Invoice Creation
![Invoice Creation](https://www.invoice-easy.com/feature1.webp)
*Real-time invoice editor with live preview and professional templates*

### 👥 Client Management
![Client Management](https://www.invoice-easy.com/feature3.webp)
*Comprehensive client database with contact history and filtering*

> **Note:** Screenshots show demo data for privacy and security reasons

## 🔧 Key Features in Detail

### Invoice Management
- Create, edit, and duplicate invoices with ease
- Real-time preview with professional templates
- Automatic tax calculations and currency formatting
- PDF generation with branded templates

### Client & Product Management
- Comprehensive client database with contact history
- Product catalog with pricing and tax configurations
- Advanced search and filtering capabilities
- Bulk operations for efficiency

### PDF Generation & Export
- Professional invoice templates with React PDF Renderer
- Custom branding and styling options
- Automatic PDF generation and download
- Email PDF attachments with Resend integration

### Cloud Storage & File Management
- Secure file uploads with Backblaze B2
- Image compression and optimization
- Efficient file management system
- Scalable cloud storage solution

### AI-Powered Features
- OpenAI integration for smart invoice suggestions
- Automated content generation
- Intelligent data processing
- Enhanced user experience with AI assistance

## 🏗️ Architecture

The application follows a modular architecture with clear separation of concerns:

```
├── app/                  # Next.js App Router with file-based routing
├── components/           # Reusable UI components and domain-specific modules
├── data/                 # Data access layer and business logic
├── hooks/                # Custom React hooks for state and side effects
├── lib/                  # Utility functions and third-party integrations
├── types/                # TypeScript type definitions
└── i18n/                 # Internationalization configuration
```

## 🚀 Development Highlights

### Performance Optimizations
- Server-side rendering with static generation where possible
- Optimized bundle splitting and code lazy loading
- Image optimization and caching strategies
- Database query optimization with proper indexing

### Developer Experience
- Comprehensive TypeScript coverage
- ESLint and Prettier configuration
- Hot reload development environment
- Detailed error handling and logging

## 🗺️ Roadmap

### Phase 1 (Current)
- ✅ Core invoice management functionality
- ✅ User authentication and authorization
- ✅ Responsive dashboard UI
- 🔄 Advanced reporting and analytics

### Phase 2 (Next Quarter)
- 📋 PDF invoice export with custom branding
- 💳 Payment integration (Stripe, PayPal)
- 👥 Team collaboration features
- 📱 Mobile app companion

### Phase 3 (Future)
- 🌐 Public client portal
- 🔄 Advanced workflow automation
- 📊 Advanced business intelligence
- 🔌 Third-party integrations (QuickBooks, Xero)

## 🔐 Security & Privacy

This application handles sensitive financial data with enterprise-grade security:
- End-to-end encryption for sensitive data
- GDPR compliance with data protection measures
- Secure API design with rate limiting

## 🤝 Contributing

While this is a private project, I welcome feedback and suggestions:

1. Open an issue for bug reports or feature requests
2. Discussion of architecture and implementation approaches
3. Code review and best practice suggestions

## 📞 Contact & Demo

**Developer:** Jovan Smiljanic

📧 **Email:** smiljanicjovan9@gmail.com  
💼 **LinkedIn:** [linkedin.com/in/jovansmiljanic](https://linkedin.com/in/jovansmiljanic)  
🌐 **Portfolio:** [inno-web-solutions.vercel.app](https://inno-web-solutions.vercel.app)

> **Interested in seeing a live demo?** Contact me to schedule a walkthrough of the application's features and architecture.

---

*This project showcases modern web development practices with a focus on security, performance, and user experience. Built with scalability and maintainability in mind.*
