# Angular 2 - Electron seed
A biolerplate for building cross platform desktop apps with [Electron](http://electron.atom.io/) and [Angular 2](https://angular.io/).

This project is based on electron-forge

## What you get
* Electron
* Angular
* Mocha, Ava & Chai for testing
* Application packaging via [electron-packager](https://github.com/electron-userland/electron-packager)

## Getting started
Use the seed via git:
```sh
git clone https://github.com/RCTechnologies/Seed.git my-project
```
After this change into `my-project` and run
```sh
npm install
```

## Available tools
### Build
Run `npm run Package:platform` to package the project. The build artifacts will be stored in the out directory. Use the `:platform` flag to package for either Linux, Windows(Win32), Mac(Darwin).

### Running the app
To run the app, run `npm start`

### Running unit tests
Run `npm test` to execute the unit tests via [AVA].

### CI
Travis.yml is included with example settings that enables CI with [Travis](https://travis-ci.org/).

### TODO
Live Reload
e2e
Test Runner
