<p align="center">
  <img alt="Tauvitify - Opinionated Vuetify Admin Starter Template" src="public/favicon.svg" width=200px/>
</p>
<h1 align="center">Tauvitify</h1>

<p align="center">
  <a href="https://github.com/vuejs/vue">
    <img src="https://img.shields.io/badge/vue-3-brightgreen.svg" alt="vue">
  </a>
  <a href="https://github.com/vuetifyjs/vuetify">
    <img src="https://img.shields.io/badge/vuetify-3-blue.svg" alt="vuetify">
  </a>
  <a href="https://github.com/kingyue737/vitify-admin/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="license">
  </a>
</p>

<p align='center'>
<b>Tauri</b> + <b>Vue</b> + <b>Vuetify</b>, Starter Template<br><br>
</p>

## Features
- [Tauri](https://tauri.app/), Build an optimized, secure, and frontend-independent application for multi-platform deployment.
- [Vite](https://github.com/vitejs/vite), [pnpm](https://pnpm.io/), [ESBuild](https://github.com/evanw/esbuild) - born with fastness

- [File based routing](./src/pages)

- [Layout system](./src/layouts)

- [State Management via Pinia](https://pinia.vuejs.org/)

- [APIs auto importing](https://github.com/antfu/unplugin-auto-import) - use Composition API and others directly

- Unit/Component Testing with [Vitest](https://github.com/vitest-dev/vitest) + [Testing Library](https://github.com/testing-library/vue-testing-library), E2E Testing with [Playwright](https://playwright.dev/) on [GitHub Actions](https://github.com/features/actions)

<br>

### Starter Template

- 🪟 Default layout with drawer, header and footer

- 🧭 Auto generated navigation drawer and breadcrumbs based on routes

- 🔔 Notification store

- 📉 Data visualization with [vue-echarts](https://github.com/ecomfe/vue-echarts)

- 🎨 Theme color customization and dark mode

- 📱 Responsive layout


## Usage

### Development

Start a standalone [Vue devtools](https://github.com/vuejs/devtools) and launch Vite dev server

```bash
pnpm tauri dev
```

### Build

To build the App, run

```bash
pnpm tauri build
```

And you will see the generated executable and `setup.exe` in `release` folder.

## License
This project is licensed under the [MIT License](LICENSE).

### Acknowledgements
This project is a fork of [vitify-next](https://github.com/kingyue737/vitify-next) created by [kingyue737](https://github.com/kingyue737). Thank you to the original author for their work.
