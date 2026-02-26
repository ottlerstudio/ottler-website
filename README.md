# Ottler Studio Sites

A collection of privacy policy pages and related content for Ottler Studio products.

## 🚀 Project Structure

```text
/
├── public/
│   ├── favicon.ico
│   └── favicon.svg
├── content/
│   ├── privacy-policy-always-on.md
│   └── privacy-policy-flashlight.md
├── src/
│   ├── assets/
│   │   ├── astro.svg
│   │   └── background.svg
│   ├── components/
│   │   ├── Home.astro
│   │   └── Welcome.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── always-on.astro
│       ├── blog.astro
│       ├── index.astro
│       └── privacy-policy/
│           ├── always-on.astro
│           └── flashlight.astro
│   └── styles/
│       └── main.css
```

## 📄 Pages

- **Home Page**: `src/pages/index.astro`
- **Always-On Product Page**: `src/pages/always-on.astro`
- **Flashlight Privacy Policy**: `src/pages/privacy-policy/flashlight.astro`
- **Always-On Privacy Policy**: `src/pages/privacy-policy/always-on.astro`
- **Blog**: `src/pages/blog.astro`

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

## 📝 Content Management

Privacy policy content is managed in the `content/` directory:
- `content/privacy-policy-always-on.md`
- `content/privacy-policy-flashlight.md`

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
