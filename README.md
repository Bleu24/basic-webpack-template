# 🚀 Basic Webpack Template

A modern, minimal Webpack boilerplate for quickly building JavaScript web apps with a fast development workflow and production-ready builds.

---

## ✨ Overview

This template provides a clean starting point for frontend projects using **Webpack** to bundle and optimize assets.

It is designed for:

- Fast local development
- Easy project structure
- Optimized production output

All source code lives in the `src/` directory, and production files are generated in `dist/`.

---

## 📁 Project Structure

```text
.
├─ src/            # Application source code (edit here)
├─ dist/           # Production build output (generated)
├─ package.json    # Scripts and dependencies
└─ webpack.config.js (or config files) # Webpack setup
```

---

## 🛠️ Features

- **Single Source Directory**: Build inside `src/`
- **Webpack Dev Server**: Fast in-memory development
- **Hot Module Replacement (HMR)**: Update modules instantly without full reload
- **Live Reload**: Automatic page refresh when needed
- **Production Build**: Minified, optimized output in `dist/`

---

## ✅ Prerequisites

Before getting started, make sure you have:

- [Node.js](https://nodejs.org/) (recommended LTS)
- npm (comes with Node.js)

Check versions:

```bash
node -v
npm -v
```

---

## 💻 Getting Started

### 1) Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

### 2) Install dependencies

```bash
npm install
```

---

## 🏃 Available Scripts

### `npm run dev`

Starts the development server.

```bash
npm run dev
```

What this does:

- Reads your project from `src/`
- Bundles files in memory (no disk writes for faster rebuilds)
- Enables HMR / live reload
- Serves your app locally (usually `http://localhost:8080` unless configured otherwise)

Use this while actively developing.

---

### `npm run build`

Creates an optimized production build.

```bash
npm run build
```

What this does:

- Bundles all required assets from `src/`
- Applies production optimizations (e.g., minification, tree-shaking)
- Writes final deployable files to `dist/`

Use this before deploying.

---

## 🚢 Deployment

Deploy the contents of the `dist/` folder to your static hosting/server.

Typical flow:

```bash
npm run build
# upload dist/ to your hosting provider
```

---

## 🧩 How to Use This Template

1. Put your app code in `src/`
2. Run `npm run dev` during development
3. Run `npm run build` for production
4. Deploy `dist/`

---

## 📝 Customization Tips

- Add loaders/plugins for CSS preprocessors, TypeScript, images, etc.
- Split config into `webpack.dev.js` and `webpack.prod.js` for larger projects
- Add linting/formatting tools (ESLint + Prettier)

---

## 🤝 Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request with improvements.

---

## 📄 License

Specify your license here (e.g., MIT).
