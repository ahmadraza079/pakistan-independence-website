# Pakistan Independence Day Website

## Overview

This is a multi-page patriotic website commemorating Pakistan's Independence Day (August 14th). The application features a celebratory design showcasing Pakistani national heroes, beautiful destinations, cultural history, and an interactive greeting card system. Built as a full-stack web application with React frontend and Express backend, it provides an immersive experience celebrating Pakistan's heritage and independence.

## User Preferences

Preferred communication style: Simple, everyday language.

## Recent Changes

**January 8, 2025**
- Enhanced homepage colors with dynamic green gradients and golden accents
- Replaced all hero images with authentic historical photographs from verified sources
- Updated place images with user-provided custom photographs
- Added comprehensive technical documentation
- All images now properly load and display authentic Pakistani heritage content

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern development practices
- **Routing**: Wouter for lightweight client-side routing between pages (Home, Heroes, Places, History, Contact)
- **UI Components**: Radix UI primitives with shadcn/ui component library for consistent, accessible design
- **Styling**: Tailwind CSS with custom Pakistan-themed color variables (green #01411C, gold #FFD700)
- **State Management**: TanStack Query for server state management and data fetching
- **Forms**: React Hook Form with Zod validation for the greeting card contact form
- **Build Tool**: Vite for fast development and optimized production builds

### Backend Architecture
- **Runtime**: Node.js with Express.js framework
- **Language**: TypeScript with ES modules for modern JavaScript features
- **Development**: tsx for TypeScript execution in development mode
- **Production**: esbuild for fast bundling and deployment
- **API Design**: RESTful API structure with /api prefix routing
- **Error Handling**: Centralized error middleware with structured error responses

### Data Storage Solutions
- **Database**: PostgreSQL with Neon Database serverless platform
- **ORM**: Drizzle ORM for type-safe database operations and schema management
- **Migrations**: Drizzle Kit for database schema versioning and migrations
- **Session Storage**: connect-pg-simple for PostgreSQL-backed session management
- **In-Memory Fallback**: Memory storage implementation for development/testing scenarios

### Authentication and Authorization
- **User Schema**: Basic user model with username/password fields and UUID primary keys
- **Session Management**: Express sessions with PostgreSQL storage backend
- **Password Security**: Prepared for hashing implementation (bcrypt ready)
- **Validation**: Zod schemas for input validation and type inference

### External Dependencies
- **Database Hosting**: Neon Database (@neondatabase/serverless) for serverless PostgreSQL
- **Font Service**: Google Fonts (Playfair Display, Noto Sans) for typography
- **Icons**: Lucide React for consistent iconography throughout the application
- **Image Assets**: Unsplash for placeholder images of heroes and Pakistani landmarks
- **Development Tools**: Replit integration for cloud development environment
- **Email Integration**: Prepared for EmailJS integration for greeting card functionality

### Design System
- **Component Library**: Custom hero cards and place cards with hover effects
- **Timeline Component**: Custom timeline implementation for historical events
- **Responsive Design**: Mobile-first approach with Tailwind breakpoints
- **Theme**: Pakistan flag colors (green, gold, white) with CSS custom properties
- **Navigation**: Fixed header with mobile hamburger menu using Radix UI Sheet component
- **Accessibility**: Radix UI primitives ensure WCAG compliance and keyboard navigation