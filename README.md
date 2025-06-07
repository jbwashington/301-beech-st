# 301 Beech St - Advanced Microfactory and Robotics Integration Hub

A comprehensive web application for managing an advanced microfactory facility with integrated robotics, AI-powered systems, and tenant management capabilities.

## 🏭 Project Overview

This Next.js application serves as the central management platform for a state-of-the-art microfactory facility located at 301 Beech Street. The platform integrates multiple systems including:

- **Facility Management**: Tenant management, booking systems, and resource allocation
- **Robotics Integration**: AGV pathing, drone test lanes, and robotics job tracking
- **AI & ML Systems**: Machine vision inspection, predictive maintenance, and digital twin modeling
- **IoT & Sensors**: Environmental monitoring and sensor network integration
- **Business Operations**: Stripe billing integration, analytics, and reporting

## 🚀 Tech Stack

- **Frontend**: Next.js 15 with App Router, React 19, TypeScript
- **Styling**: Tailwind CSS 4, ShadCN UI components
- **Backend**: Supabase (Database, Auth, Real-time)
- **Payments**: Stripe integration
- **Infrastructure**: SST (Serverless Stack), Cloudflare Workers
- **AI/ML**: Custom machine learning pipelines
- **Code Quality**: ESLint, Prettier, Husky pre-commit hooks

## 🛠️ Development Setup

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm
- Git

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd 301-beech-st
   ```

2. **Install dependencies**

   ```bash
   pnpm install
   ```

3. **Set up environment variables**

   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```

4. **Run the development server**

   ```bash
   pnpm dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📝 Available Scripts

- `pnpm dev` - Start development server with Turbopack
- `pnpm build` - Build the application for production
- `pnpm start` - Start the production server
- `pnpm lint` - Run ESLint
- `pnpm lint:fix` - Run ESLint with auto-fix
- `pnpm format` - Format code with Prettier
- `pnpm format:check` - Check code formatting

## 🏗️ Project Structure

```
301-beech-st/
├── app/                    # Next.js App Router pages and layouts
├── components/             # Reusable React components
│   └── ui/                # ShadCN UI components
├── lib/                   # Utility functions and configurations
├── public/                # Static assets
├── .husky/                # Git hooks configuration
└── ...config files
```

## 🔧 Key Features

### Facility Management

- Multi-tenant facility management
- Resource booking and scheduling
- Access control and security

### Robotics Integration

- AGV (Automated Guided Vehicle) path management
- Drone test lane coordination
- Robotics job tracking and logging
- Digital twin workflow modeling

### AI & Machine Learning

- Computer vision for quality inspection
- Predictive maintenance algorithms
- Real-time sensor data analysis

### Business Operations

- Stripe payment processing
- Comprehensive analytics and reporting
- Webhook notifications for tenants
- Training modules and documentation

## 🔒 Security & Compliance

The application implements enterprise-grade security features including:

- Supabase authentication and authorization
- Role-based access control (RBAC)
- Data encryption and secure API endpoints
- Compliance monitoring and reporting

## 🚀 Deployment

The application is designed for deployment using:

- **Frontend**: Vercel or similar Next.js hosting
- **Backend**: Supabase cloud infrastructure
- **Edge Functions**: Cloudflare Workers
- **Infrastructure**: SST for serverless backend services

## 📊 Monitoring & Analytics

- Real-time facility usage tracking
- Equipment performance monitoring
- Tenant activity analytics
- Predictive maintenance alerts

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Code Quality

This project uses automated code quality tools:

- **ESLint** for code linting
- **Prettier** for code formatting
- **Husky** for pre-commit hooks
- **lint-staged** for staged file processing

All commits are automatically checked for code quality before being accepted.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support and questions, please contact the development team or create an issue in the repository.

---

**Built with ❤️ for the future of manufacturing and robotics**
