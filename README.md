# unplugin-subset-fonts

[![NPM version](https://img.shields.io/npm/v/unplugin-subset-fonts)](https://www.npmjs.com/package/unplugin-subset-fonts)

## Install

```bash
npm i -D unplugin-subset-fonts
```

<details>
<summary>Vite</summary><br>

```ts
// vite.config.ts
import SubsetFonts from 'unplugin-subset-fonts/vite'

export default defineConfig({
  plugins: [
    SubsetFonts({ /* options */ }),
  ],
})
```

<br></details>

<details>
<summary>Rollup</summary><br>

```ts
// rollup.config.js
import SubsetFonts from 'unplugin-subset-fonts/rollup'

export default {
  plugins: [
    SubsetFonts({ /* options */ }),
  ],
}
```

<br></details>


<details>
<summary>Webpack</summary><br>

```ts
// webpack.config.js
module.exports = {
  /* ... */
  plugins: [
    require('unplugin-subset-fonts/webpack')({ /* options */ })
  ]
}
```

<br></details>

<details>
<summary>Nuxt</summary><br>

Nuxt 2 and [Nuxt Bridge](https://github.com/nuxt/bridge)

```js
// nuxt.config.js
export default {
  buildModules: [
    ['unplugin-subset-fonts/nuxt', { /* options */ }],
  ],
}
```

Nuxt 3

```js
// nuxt.config.js
export default defineNuxtConfig({
  modules: [
    ['unplugin-subset-fonts/nuxt', { /* options */ }]
  ],
})
```

<br></details>

<details>
<summary>Vue CLI</summary><br>

```ts
// vue.config.js
module.exports = {
  configureWebpack: {
    plugins: [
      require('unplugin-subset-fonts/webpack')({ /* options */ }),
    ],
  },
}
```

<br></details>

<details>
<summary>esbuild</summary><br>

```ts
// esbuild.config.js
import { build } from 'esbuild'
import SubsetFonts from 'unplugin-subset-fonts/esbuild'

build({
  plugins: [SubsetFonts()],
})
```

<br></details>