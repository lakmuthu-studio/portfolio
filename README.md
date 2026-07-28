# Lakmuthu Studio Website

The official website for Lakmuthu Studio, the independent software development practice of Kaveen Lakmuthu.

The site presents web, mobile, dashboard, and internal-tool development services for businesses, founders, and service providers. It includes service descriptions, starting prices, project examples, working policies, frequently asked questions, and a structured project inquiry form.

## Technology

- [Astro](https://astro.build) for static site generation
- TypeScript for client-side form behavior
- Component-based Astro templates
- Custom responsive CSS without a UI framework

## Project Structure

```text
public/
├── images/              Portfolio and demonstration images
├── favicon.ico
└── favicon.svg

src/
├── components/          Individual page sections
├── layouts/             Shared document layout and metadata
├── pages/               Site routes
└── styles/              Global design system and responsive styles
```

## Local Development

Requirements:

- Node.js 22.12 or newer
- npm

Install the dependencies:

```sh
npm install
```

Start the Astro development server in background mode:

```sh
npx astro dev --background
```

Manage the background server:

```sh
npx astro dev status
npx astro dev logs
npx astro dev stop
```

## Production Build

Create an optimized static production build:

```sh
npm run build
```

The generated site is written to `dist/`.

Preview the production build locally:

```sh
npm run preview
```

## Site Content

The primary page is assembled in `src/pages/index.astro`. Each major section is maintained as a separate component in `src/components/`.

Before deploying, replace the placeholder LinkedIn and WhatsApp URLs in `src/components/Contact.astro` with the correct business contact details.

## Copyright

Copyright © 2026 Kaveen Lakmuthu. All rights reserved.

This repository contains the source code and content for the Lakmuthu Studio website. The code, design, copy, layout, and assets are not licensed for reuse, copying, redistribution, or derivative works without written permission.
