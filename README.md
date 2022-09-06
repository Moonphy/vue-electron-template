# Vue-Electron

[![Build Status](https://travis-ci.org/mubaidr/vue-electron-template.svg?branch=master)](https://travis-ci.org/mubaidr/vue-electron-template)
[![Build status](https://ci.appveyor.com/api/projects/status/cjua6pdhjp9rqa1o?svg=true)](https://ci.appveyor.com/project/mubaidr/vue-electron-template)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)

Template for building desktop applications using [Electronjs](https://electronjs.org) and [Vue.js](https://vuejs.org)

## Overview

This template takes advantage of `webpack-5` with `vue-loader`, `electron-builder`, and some of the most used plugins like `vue-router`, `vuex` and so much more to provide an easy to use development (with vscode debugging) enviroment with hot module replacement.

### Getting Started

Clone this repository, install dependencies and run using either `dev`, `debug` or `build` command.

```bash
# Clone this repository
git clone https://github.com/mubaidr/vue-electron

# change directory to cloned path
cd vue-electron

# Install dependencies
npm install

# Run in `debug` mode, to debug app using VSCODE
npm run debug

# Run in `dev` mode
npm run dev

# Build installer for this app
npm run build
```

### Project structure

`src/main` contains electron main script.

`src/renderer` contains vue-js application.

`src/utilities/workerSample.ts` a sample worker script.

#### Credits

All credits to authors of packages and tools used in the project.

\* This template is inspired by [electron-vue](https://github.com/SimulatedGREG/electron-vue)

