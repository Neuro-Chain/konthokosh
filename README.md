# Kontho Kosh - Bengali Cultural Platform

A modern Bengali cultural platform built with cutting-edge web technologies, designed for writers, poets, and literature enthusiasts. The platform leverages blockchain technology for content ownership protection and implements AI-powered Text-to-Speech (TTS) functionality to convert written content into audiobooks.

## 🚀 Core Features

### 📝 Content Creation & Publishing

- Real-time MDX Editor: Advanced editor with markdown support and rich text formatting
- Tag-based Categorization: Comprehensive tagging system for content classification (Poetry, Stories, Essays, History, etc.)
- AI Cover Generation: Automated cover image generation using AI models
- Blockchain Integration: IPFS storage with on-chain metadata for immutable content ownership

### 🎧 Audiobook System

- ElevenLabs TTS Integration: High-quality Bengali voice synthesis with customizable parameters
- Advanced Audio Player: Full-featured player with playback controls, shuffle, repeat, and volume management
- Synchronized Playback: Line-by-line text synchronization with audio playback
- Caching System: Intelligent audio caching for improved performance and offline capability

### 👥 Community & Interaction

- Feed System: Dynamic content feed with pagination and real-time updates
- Comment System: Threaded discussions and community engagement
- Advanced Search: Full-text search with tag filtering and keyword highlighting
- User Dashboard: Personal content management and analytics

### 🔐 Security & Privacy

- Clerk Authentication: Secure user authentication with social login integration
- Plagiarism Protection: Blockchain-based content verification and ownership tracking
- Data Encryption: End-to-end encryption for sensitive user data
- Access Control: Role-based permissions and content moderation

### 🎨 UI/UX Architecture

- Responsive Design: Mobile-first approach with adaptive layouts
- Theme System: Dark/Light mode with system preference detection
- Bengali Typography: Optimized font stack for Bengali script rendering
- Component Library: ShadCN/UI based design system with accessibility compliance

## 🛠️ Technology Stack

### Frontend Framework

- Next.js 15.2.4: App Router with Server Components and API Routes
- React 19: Latest React with concurrent features and hooks
- TypeScript 5: Strict type checking with advanced language features

### Styling & UI

- Tailwind CSS 4.1.9: Utility-first CSS framework with custom design system
- Radix UI: Unstyled, accessible UI primitives
- ShadCN/UI: High-quality React components built on Radix UI
- Framer Motion: Declarative animations and transitions

### State Management & Data

- React Context API: Client-side state management with custom hooks
- React Hook Form: Performant forms with validation
- Zod: TypeScript-first schema validation
- SWR: React hooks for data fetching with caching

### External Integrations

- Clerk: Authentication and user management
- ElevenLabs API: Text-to-speech synthesis
- IPFS: Decentralized file storage
- Blockchain: Smart contract integration for content ownership

### Development Tools

- ESLint: Code linting with Next.js configuration
- PostCSS: CSS processing with Tailwind integration
- pnpm: Fast, disk-efficient package manager

## 📁 Project Structure

This is a monorepo containing the main project overview. The actual implementations are split into separate repositories:

### Frontend Repository

- **Repository**: [https://github.com/hasanshahriar32/konthokosh-frontend](https://github.com/hasanshahriar32/konthokosh-frontend)
- **Description**: Next.js-based frontend application with modern UI/UX
- **Tech Stack**: Next.js, React, TypeScript, Tailwind CSS, ShadCN/UI

### Backend Repository

- **Repository**: [https://github.com/hasanshahriar32/konthokosh-backend](https://github.com/hasanshahriar32/konthokosh-backend)
- **Description**: Backend API server handling business logic, database operations, and integrations
- **Note**: Repository may be private or not yet public

## 🚀 Getting Started

### Prerequisites

- Node.js 18.0 or higher
- pnpm package manager
- Git

### Installation

1. Clone the frontend repository:

   ```bash
   git clone https://github.com/hasanshahriar32/konthokosh-frontend.git
   cd konthokosh-frontend
   ```

2. Install dependencies:

   ```bash
   pnpm install
   ```

3. Configure environment:

   ```bash
   cp .env.example .env.local
   # Edit .env.local with your API keys
   ```

4. Start development server:

   ```bash
   pnpm dev
   ```

5. Build for production:
   ```bash
   pnpm build
   pnpm start
   ```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

_Kontho Kosh - Revolutionizing Bengali literature through technology, making creative expression secure, accessible, and innovative._
