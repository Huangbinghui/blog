# blog

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Create

```sh
npm init vue@latest
# or
pnpm create vue@latest 
```

## Project Setup

```sh
pnpm install
```

### Compile and Hot-Reload for Development

```sh
pnpm run dev
```

### Compile and Minify for Production

```sh
pnpm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
pnpm run lint
```

### Format with [prettier](https://prettier.io/)

```sh
pnpm run format
```

## Install [tailwindcss](https://www.tailwindcss.cn/)

```sh
pnpm install -D tailwindcss@latest postcss@latest autoprefixer@latest
```

### create [tailwind.config.js](./tailwind.config.js)

```sh
npx tailwindcss init
```
### 在入口中引入tailwind

```js
import "tailwindcss/tailwind.css"
```

### 配置tailwind.config.js文件

```js
content: ['./index.html', './src/**/*.{vue,js,ts,jsx,tsx}'],
```

### 配置vite.config选项

```js
css: {
    postcss: {
      plugins: [require("tailwindcss"), require("autoprefixer")]
    }
  },
```

### 配置vscode

```js
"editor.quickSuggestions": {
    "strings": true
  }
```

