# alfaarhitektid

Vite + React + TypeScript + Tailwind CSS + shadcn/ui.

## Local development

Requirements: Node.js 20+ and npm.

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
```

Preview the production build with `npm run preview`.

## GitHub Pages

This repository includes a workflow (`.github/workflows/deploy.yml`) that builds on push to `main` and deploys the `dist` output to GitHub Pages.

In the repository settings, enable **Pages** with the **GitHub Actions** source. For a custom domain, add your domain under Pages and keep `public/CNAME` in sync with the hostname you configure.

## Stack

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
