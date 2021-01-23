# node-template

> Starter template for Node projects with Express, ESLint, Prettier, Husky and Nodemon

## Features

- ES6 _without_ Babel
- Linting using ESLint with Airbnb Javascript style guide and Prettier
- ESLint security plugin
- Pre-commit hooks using Lint-Staged with Husky
- Live reloading using Nodemon
- .gitignore for Node
- Express installed

## How to remove Express

If you want to develope a Node app without express:

1. Uninstall Express

```
yarn remove express
```

2. Rename `server` to `src` (or whatever you want)
3. In `package.json` replace `server` with the new name of directory

## Installing

```
yarn --dev
```

## Running

```
yarn start
```
