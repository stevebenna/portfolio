# Portfolio

A modern portfolio website built with Astro, showcasing projects and professional work.

## 🚀 Project Structure

```text
/
├── public/
├── src/
│   ├── assets/
│   │   └── styles.css
│   ├── components/
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── ProjectCard.astro
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── tsconfig.json
└── package.json
```

## 📦 Components

- **Header.astro** - Navigation header for site navigation and branding
- **Footer.astro** - Footer section with links and information
- **ProjectCard.astro** - Reusable component for displaying individual projects
- **Welcome.astro** - Hero/welcome section for the landing page
- **Layout.astro** - Base layout wrapper for all pages

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
