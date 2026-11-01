# Nagaraja Prabhu — Portfolio

A responsive personal portfolio built with React, Vite, Tailwind CSS, Framer Motion and Lucide icons.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

The production files are created in `dist/`.

## Deploy

### Vercel

Import this repository in Vercel. It detects Vite automatically. Use `npm run build` as the build command and `dist` as the output directory.

### GitHub Pages

The site can be deployed with any static hosting workflow after `npm run build`; publish the contents of `dist/`. For a repository path (rather than a root domain), set Vite's `base` option in `vite.config.js` to `/<repository-name>/` before building.

## CV and contact form

The uploaded CV is included at `public/Nagaraja_Prabhu_Premium_Resume_Updated.pdf`. The contact form validates its fields and opens the visitor's email app with a prefilled message to Nagaraja.
