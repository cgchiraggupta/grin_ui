# Grin UI

A modern web application built with Next.js, TypeScript, and Tailwind CSS, featuring a beautiful and responsive user interface.

## 🚀 Tech Stack

- **Framework**: Next.js 15.2.0
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Package Manager**: Bun
- **Linting**: Biome
- **Deployment**: Netlify

## 📦 Dependencies

### Core Dependencies
- React 18.3.1
- Next.js 15.2.0
- TypeScript
- Tailwind CSS
- shadcn/ui components

### Development Dependencies
- Biome for linting and formatting
- ESLint
- PostCSS
- TypeScript types

## 🛠️ Getting Started

### Prerequisites
- Node.js (latest LTS version recommended)
- Bun package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/cgchiraggupta/grin_ui.git
cd grin_ui
```

2. Install dependencies:
```bash
bun install
```

3. Start the development server:
```bash
bun run dev
```

The application will be available at `http://localhost:3000`.

## 📝 Available Scripts

- `bun run dev`: Start the development server with Turbopack
- `bun run build`: Build the application for production
- `bun run start`: Start the production server
- `bun run lint`: Run linting and type checking
- `bun run format`: Format the codebase

## 🏗️ Project Structure

```
grin_ui/
├── src/
│   ├── app/
│   │   ├── page.tsx
│   │   ├── ClientBody.tsx
│   │   ├── globals.css
│   │   └── layout.tsx
│   └── lib/
├── public/
├── components.json
├── tailwind.config.ts
├── tsconfig.json
└── package.json
```

## 🎨 Styling

The project uses Tailwind CSS for styling with a custom configuration. The styling is organized in:
- `src/app/globals.css`: Global styles and Tailwind directives
- `tailwind.config.ts`: Tailwind configuration with custom theme settings

## 🔍 Code Quality

- TypeScript for type safety
- Biome for linting and formatting
- ESLint for additional code quality checks
- Prettier for code formatting

## 🚀 Deployment

The project is configured for deployment on Netlify with the following settings:
- Build command: `next build`
- Publish directory: `.next`

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
