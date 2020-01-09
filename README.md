# ESLint (and Prettier) config

[![npm version](https://badge.fury.io/js/eslint-config-leozera.svg)](https://badge.fury.io/js/eslint-config-leozera) ![NPM downloads](https://img.shields.io/npm/dm/eslint-config-leozera) [![GitHub issues](https://img.shields.io/github/issues/leonardofaria/eslint-config-leozera)](https://github.com/leonardofaria/eslint-config-leozera/issues) ![Code Style Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg) [![MIT License](https://img.shields.io/badge/license-MIT-red.svg?style=flat)](https://github.com/leonardofaria/leozera-ui/blob/master/LICENSE) [![Twitter Follow](https://img.shields.io/twitter/follow/leozera?label=Follow%20on%20Twitter)](https://twitter.com/leozera/)

These are settings for ESLint and Prettier used by me and Thinkific.

## What it does

This setup lints your JavaScript code based on practices. Check the [.eslintrc.js](https://github.com/leonardofaria/eslint-config-leozera/blob/master/.eslintrc.js) file to see what is included. Feel free to override the rules that make sense for you.

## Installing

1. In your project folder, run:

```
npm i -D eslint-config-leozera # or yarn install --dev eslint-config-leozera
npx install-peerdeps --dev eslint-config-leozera
```

2. You will see several dependencies were installed. Now, create (or update) a `.eslintrc` file with the following content:

```js
{
  'extends': [
    'leozera'
  ]
}
```

3. Copy the [.prettierrc](https://github.com/leonardofaria/eslint-config-leozera/blob/master/.prettierrc) file from this repository into your project folder

---

This repository is inspired by [eslint-config-wesbos](https://github.com/wesbos/eslint-config-wesbos).
