# shopping-list

### Some features that the app has:

* Creating a new shopping list with a name and description
* Adding items to the shopping list, specifying the item's quantity, unit of measure, and price
* Editing and deleting shopping list items
* Marking items as purchased or not purchased
* Sharing shopping lists with other users, allowing them to edit and add items to the list
* Purchase history view for each listing, showing the date items were purchased and the total purchase amount
* Automatic calculation of total shopping list value based on item prices and quantities
* Search for items in a public database to automatically add items to the shopping list
* Integration with online payment services to allow users to pay for their purchases directly within the app

### When developing this application, I try to practice several advanced Vue 3, TypeScript and OOP concepts, such as:

* Use of reactive, computed and assisted components
* Using mixins and inheritance to share functionality between components
* Creating classes and interfaces to represent domain entities such as shopping lists, items, and users
* Implementing design patterns such as Factory, Adapter, and Facade
* Use of asynchronous resources, such as HTTP requests and integration with online payment services
* Implementation of automated tests to ensure application quality and robustness

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin) to make the TypeScript language service aware of `.vue` types.

If the standalone TypeScript plugin doesn't feel fast enough to you, Volar has also implemented a [Take Over Mode](https://github.com/johnsoncodehk/volar/discussions/471#discussioncomment-1361669) that is more performant. You can enable it by the following steps:

1. Disable the built-in TypeScript Extension
    1) Run `Extensions: Show Built-in Extensions` from VSCode's command palette
    2) Find `TypeScript and JavaScript Language Features`, right click and select `Disable (Workspace)`
2. Reload the VSCode window by running `Developer: Reload Window` from the command palette.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Playwright](https://playwright.dev)

```sh
# Install browsers for the first run
npx playwright install

# When testing on CI, must build the project first
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chromium
npm run test:e2e -- --project=chromium
# Runs the tests of a specific file
npm run test:e2e -- tests/example.spec.ts
# Runs the tests in debug mode
npm run test:e2e -- --debug
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
