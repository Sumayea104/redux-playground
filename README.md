# Redux Playground

A practice project for learning modern Redux with React, TypeScript, Tailwind CSS, and shadcn/ui.

---

## 🚀 Project Setup Journey

This repository documents my Redux learning process from project initialization to UI setup.

---

# 🛠️ Technologies Used

- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- Redux Toolkit

---

# 📦 Project Initialization

## 1. Create Vite Project

```bash
npm create vite@latest
```

### Project Configuration
- Framework: React
- Variant: TypeScript

---

## 2. Install Dependencies

```bash
npm install
```

---

## 3. Run Development Server

```bash
npm run dev
```

---

# 🎨 Tailwind CSS Setup

## Install Tailwind CSS

```bash
npm install tailwindcss @tailwindcss/vite
```

---

## Configure Vite

Add Tailwind plugin inside `vite.config.ts`

```ts
import tailwindcss from "@tailwindcss/vite";

plugins: [tailwindcss()]
```

---

## Import Tailwind in CSS

Inside `src/index.css`

```css
@import "tailwindcss";
```

---

# 🧩 shadcn/ui Setup

## Install shadcn/ui

Follow official docs for existing Vite project.

---

## Configure TypeScript Paths

### tsconfig.app.json

```json
{
  "compilerOptions": {
    "baseUrl": ".",
    "paths": {
      "@/*": ["./src/*"]
    }
  }
}
```

---

## Install Node Types

```bash
npm install -D @types/node
```

---

## Update vite.config.ts

Add alias configuration.

---

## Initialize shadcn

```bash
npx shadcn@latest init
```

### Selected Preset
- Style: New York

---

# 📁 Generated Structure

```bash
src/
 ├── components/
 │    └── ui/
 │         └── button.tsx
 │
 ├── lib/
 │    └── utils.ts
```

---

# 🔥 Git & GitHub Workflow

## Initialize Git

```bash
git init
```

---

## Add Files

```bash
git add .
```

---

## Commit Changes

```bash
git commit -m "initial setup vite typescript tailwind shadcn"
```

---

## Connect GitHub Repository

```bash
git remote add origin https://github.com/Sumayea104/redux-playground.git
```

---

## Rename Branch

```bash
git branch -M main
```

---

## Push to GitHub

```bash
git push -u origin main
```

---

## If Error Occurs

### Unrelated Histories Error

```bash
git pull origin main --allow-unrelated-histories
```

Then:

```bash
git push -u origin main
```

---

# 📚 Learning Goals

- Understand Redux fundamentals
- Learn Redux Toolkit
- State management with React
- Scalable frontend architecture
- Type-safe Redux with TypeScript

---

# ✨ Status

🚧 Currently Learning & Building