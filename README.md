# 🌌 Space Maze

A 3D space exploration game where you navigate through a cosmic maze. Built with **Astro**, **Three.js**, and **TypeScript**.

## 🚀 Live Demo

This project is deployed at [space-maze.coreyburns.ca](https://space-maze.coreyburns.ca).

## ✨ Features

- **3D Graphics**: Immersive space environments rendered with Three.js.
- **Procedural Elements**: Explore cosmic vistas with real-time rendering.
- **Fast Performance**: Optimized for speed and static delivery via Astro.
- **Responsive Layout**: Designed for seamless exploration across different screen sizes.

## 🛠️ Tech Stack

- [Astro](https://astro.build/) - Modern web framework for content-driven websites.
- [Three.js](https://threejs.org/) - Comprehensive 3D engine for the web.
- [TypeScript](https://www.typescriptlang.org/) - Typed JavaScript for robust development.
- [Cloudflare Pages](https://pages.cloudflare.com/) - Lightning-fast hosting and deployment.

## 🛠️ Development

### Prerequisites

- [Bun](https://bun.sh/) (v1.3+)
- Node.js (v18+)

### Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   bun install
   ```
3. Start the development server:
   ```bash
   bun run dev
   ```

### 🚀 Deployment

Build locally with:

```bash
bun run build
```

Deploy to Cloudflare Pages with:

```bash
bun run deploy
```

If you need to target the production branch explicitly:

```bash
bun run deploy:production
```

## 📜 Wrangler Configuration

Wrangler is configured for Cloudflare Pages. This repository is a Cloudflare Pages project, not a Workers project.
