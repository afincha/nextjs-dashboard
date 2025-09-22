# This is a test README

## Local Development Environment Setup

This is a Next.js dashboard application. Follow these steps to run the app locally:

### Prerequisites
- Node.js (version 18 or higher)
- npm, yarn, or pnpm package manager

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd nextjs-dashboard
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Set up environment variables**
   - Create a `.env.local` file in the root directory
   - Add necessary environment variables (database connection, authentication secrets, etc.)

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

5. **Access the application**
   - Open [http://localhost:3000](http://localhost:3000) in your browser
   - The app will automatically reload when you make changes

### Available Scripts

- `npm run dev` - Starts the development server with Turbopack
- `npm run build` - Creates an optimized production build
- `npm run start` - Starts the production server
- `npm run lint` - Runs ESLint for code quality checks

### Technology Stack

- **Framework**: Next.js with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Database**: Vercel Postgres
- **Authentication**: NextAuth.js
- **UI Components**: Heroicons, custom React components
