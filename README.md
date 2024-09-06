# Astro Starter Kit

## ¿What changes from the minimal official Astro template?

- Add [@barcia/corecss](https://github.com/barcia/corecss)
- Contigure alias to import from `/src/` with `@/`
- Create a basic layout
- Create a basic collection (blog)
  - Create the list page
  - Create the post page
- Create some basic common components (Head, Navbar, Footer, FormattedDate, etc.)
- Create an Icon component to easily import inline SVG icons
- Add 404 page
- Add task `dev:host`
- Add some utility functions

```sh
npm create astro@latest ./ -- --template barcia/astro
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                                       |
| :------------------------ | :----------------------------------------------------------- |
| `npm install`             | Installs dependencies                                        |
| `npm run dev`             | Starts local dev server at `localhost:4321`                  |
| `npm run dev:host`        | Starts local dev server at `localhost:4321` with host in LAN |
| `npm run build`           | Build your production site to `./dist/`                      |
| `npm run preview`         | Preview your build locally, before deploying                 |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check`             |
| `npm run astro -- --help` | Get help using the Astro CLI                                 |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
