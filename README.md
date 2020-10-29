# nuxt-blurhash

[![npm version][npm-version-src]][npm-version-href]

>

[📖 **Release Notes**](./CHANGELOG.md)

this project based on [https://github.com/damienroche/vue-blurhash](https://github.com/damienroche/vue-blurhash)

## Setup

1. Add `nuxt-blurhash` dependency to your project

```bash
yarn add nuxt-blurhash # or npm install nuxt-blurhash
```

2. Add `nuxt-blurhash` to the `modules` section of `nuxt.config.js`

```js
{
  modules: [
    // Simple usage
    'nuxt-blurhash'
  ]
}
```

## Simple usage

<p align="center">
  <img src="./Screenshot_2020-10-29%20test-blur(1).png">
</p>


```vue
<template>
  <nuxt-blur-image
    width="400"
    height="300"
    src="https://images.unsplash.com/photo-1417325384643-aac51acc9e5d?q=75&fm=jpg&w=1080&fit=max"
    hash="LFC$yHwc8^$yIAS$%M%00KxukYIp"
    alt="A man drinking a coffee."
  />
</template>
```

<p align="center">
  <img src="./Screenshot_2020-10-29 test-blur.png">
</p>
## Use Canvas only

```vue
<template>
  <nuxt-blurhash
    :hash="'LdHfL}oJR$WBKnfi%3ofT0kCM{ay'"
    :width="'340'"
    :height="'320'"
    :punch="punch"
  />
</template>
```



