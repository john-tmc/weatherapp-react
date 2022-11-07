# Weather App - React

* **[React](https://facebook.github.io/react/)** (18.x)
* **[Webpack](https://webpack.js.org/)** (5.x)
* **[Typescript](https://www.typescriptlang.org/)** (4.x)
* **[Hot Module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)** + [Fast Refresh](https://github.com/pmmmwh/react-refresh-webpack-plugin)
* Image support ([Image Webpack Loader](https://github.com/tcoopman/image-webpack-loader))
* [LESS](https://lesscss.org/) support
* Production build script
* Code linting ([ESLint](https://github.com/eslint/eslint)) and formatting ([Prettier](https://github.com/prettier/prettier))
* Test frameworks ([Jest](https://facebook.github.io/jest/) + [React Testing Library](https://testing-library.com/docs/react-testing-library/intro))

## Requirements
1. [Requirement Notes](.reqs/Instructions.pdf)
2. [Requirement Mockup](.reqs/Mockup.png)
<details>
<summary><font size=4>Mockup Preview</font></summary>

![Agency Analytics](.reqs/Mockup.png?raw=true "Reference Image")

</details>

<summary><font size=4>Result Preview</font></summary>

![Agency Analytics](.reqs/Result.png?raw=true "Result Image")

</details>

## Installation
1. Clone/download repo
2. `npm install` (or `npm install` for npm)

## Usage
**Development**
`npm run start-dev`

* Build app continuously (HMR enabled)
* App served @ `http://localhost:8080`


**Production**
`npm run build`
* Build app once (HMR disabled) to `/dist/`
---

**All commands**

Command | Description
--- | ---
`npm run start-dev` | Build app continuously (HMR enabled) and serve @ `http://localhost:8080`
`npm run build` | Build app to `/dist/`
`npm run test` | Run tests
`npm run lint` | Run linter
`npm run lint --fix` | Run linter and fix issues
`npm run start` | (alias of `npm run start-dev`)
