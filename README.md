# React + TypeScript + Vite + Tailwind CSS + shadcn/ui Boilerplate

A modern, opinionated boilerplate for building React applications with TypeScript, Vite, Tailwind CSS, and shadcn/ui. This setup includes pre-configured tools and utilities to help you get started quickly.

---

## Features

- ⚡ **Vite**: Fast development and build tooling.
- 🛠️ **TypeScript**: Type-safe JavaScript for better developer experience.
- 🎨 **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- ✨ **shadcn/ui**: Beautiful, accessible, and customizable UI components.
- 📁 **Import Aliases**: Clean imports with `@/` and `@components/` aliases.
- 🧰 **Utility Functions**: Includes `cn` utility for merging Tailwind CSS classes.

---

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm (or yarn/pnpm)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/codingdestro/boiler-react.git
   cd boiler-react```

2. Install dependencies
    ```bash
    pnpm install 

    pnpm run dev 
    ```
    


### Project Structure
 my-app/
├── public/              # Static assets
├── src/
│   ├── assets/          # Assets
│   ├── components/      # Reusable components
│   ├── lib/             # Utilities and helpers
│   ├── App.tsx          # Main application component
│   ├── main.tsx         # Entry point
│   ├── index.css        # Global styles
│   ├── vite-env.d.ts    # Vite env types
├── components.json      # Components configuration
├── eslint.config.js     # ESLint configuration
├── .gitignore           # Git ignore file
├── index.html           # HTML template
├── package.json         # Project dependencies
├── tailwind.config.js   # Tailwind CSS configuration
├── postcss.config.mjs   # PostCSS configuration
├── tsconfig.json        # TypeScript configuration
├── vite.config.ts       # Vite configuration
