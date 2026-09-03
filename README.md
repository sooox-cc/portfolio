# sooox portfolio

Personal portfolio and blog, built with [Astro](https://astro.build).

## Project Structure

```text
/
├── public/
├── src/
│   ├── assets/blog/       # blog images/diagrams
│   ├── components/        # Header, Footer, BlogCard, ProjectCard, Spoiler
│   ├── content/blog/      # MDX blog posts
│   ├── layouts/           # Layout, BlogPost
│   ├── pages/              # index, services, blog/
│   ├── plugins/           # remark-spoiler.mjs
│   ├── styles/global.css
│   └── content.config.ts
├── astro.config.mjs
└── package.json
```

Blog posts live as MDX files in `src/content/blog/`, defined via `src/content.config.ts`. Styling uses Tailwind CSS v4.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build production site to `./dist/`               |
| `npm run preview`         | Preview build locally, before deploying          |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Learn more

[Astro docs](https://docs.astro.build) · [Astro Discord](https://astro.build/chat)
