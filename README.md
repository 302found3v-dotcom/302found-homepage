# 302Found Homepage

Homepage oficial del proyecto 302Found desarrollada con Astro.

## 🌳 Ramas de Desarrollo

- **`main`**: Rama principal de producción
- **`deni-dev`**: Rama de desarrollo activa - ¡Nuevos features y mejoras aquí! 🚀

> **Nota para desarrolladores**: Para contribuir al proyecto, crea tu rama desde `deni-dev` y haz merge requests hacia la misma rama de desarrollo.

## 🔄 Flujo de Trabajo con Git

1. **Clona el repositorio:**
   ```bash
   git clone git@github.com:302foundevx/302found-homepage.git
   ```

2. **Cambia a la rama de desarrollo:**
   ```bash
   git checkout deni-dev
   ```

3. **Crea tu rama de feature:**
   ```bash
   git checkout -b feature/tu-nueva-funcionalidad
   ```

4. **Haz tus cambios y commitea:**
   ```bash
   git add .
   git commit -m "feat: descripción de tu cambio"
   ```

5. **Push y crea un Pull Request hacia `deni-dev`**

## 📦 Instalación

```sh
pnpm create astro@latest -- --template minimal
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
