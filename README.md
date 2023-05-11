# Chrome Extension Boilerplate with

![](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![](https://img.shields.io/badge/Typescript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![](https://badges.aleen42.com/src/vitejs.svg)

## Table of Contents

- [Intro](#intro)
- [Features](#features)
- [Installation](#installation)
    - [Procedures](#procedures)
- [Screenshots](#screenshots)
    - [NewTab](#newtab)
    - [Popup](#popup)
- [Sample](#sample)
- [Documents](#documents)

## Intro <a name="intro"></a>

This boilerplate is made for creating chrome extensions using React and Typescript.
> The focus was on improving the build speed and development experience with Vite.

## Features <a name="features"></a>

- [React 18](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://jestjs.io/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Vite](https://vitejs.dev/)
- [SASS](https://sass-lang.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Chrome Extension Manifest Version 3](https://developer.chrome.com/docs/extensions/mv3/intro/)
- HRR(Hot Rebuild & Refresh/Reload)

## Installation <a name="installation"></a>

### Procedures <a name="procedures"></a>

1. Clone this repository.
2. Change `name` and `description` in package.json => **Auto synchronize with manifest**
3. Run `pnpm install` (check your node version >= 16.6, recommended >= 18)
4. Run `pnpm run dev`
5. Load Extension on Chrome
    1. Open - Chrome browser
    2. Access - chrome://extensions
    3. Check - Developer mode
    4. Find - Load unpacked extension
    5. Select - `dist` folder in this project (after dev or build)
6. If you want to build in production, Just run `pnpm run build`.

## Screenshots <a name="screenshots"></a>

### New Tab <a name="newtab"></a>

<img width="971" src="https://user-images.githubusercontent.com/53500778/162631646-cd40976b-b737-43d0-8e6a-6ac090a2e2d4.png">

### Popup <a name="popup"></a>

<img width="314" alt="popup" src="https://user-images.githubusercontent.com/53500778/203561728-23517d46-12e3-4139-8a4f-e0b2f22a6ab3.png">

## Sample <a name="sample"></a>

- https://github.com/Jonghakseo/drag-gpt-extension
- https://github.com/Jonghakseo/pr-commit-noti

## Documents <a name="documents"></a>

- [Vite Plugin](https://vitejs.dev/guide/api-plugin.html)
- [ChromeExtension](https://developer.chrome.com/docs/extensions/mv3/)
- [Rollup](https://rollupjs.org/guide/en/)
- [Rollup-plugin-chrome-extension](https://www.extend-chrome.dev/rollup-plugin)

