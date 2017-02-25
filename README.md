# Angular 2 - Electron seed [![Build Status](https://travis-ci.org/RCTechnologies/Seed.svg?branch=master)](https://travis-ci.org/RCTechnologies/Seed)
A biolerplate for building cross platform desktop apps with [Electron](http://electron.atom.io/), [Angular 2](https://angular.io/) and [Travis CI](https://travis-ci.org/)

This project is build from electron-forge angular 2 template

## What you get
* Electron
* Angular
* Mocha, Ava & Chai for testing
* Application packaging via [electron-packager](https://github.com/electron-userland/electron-packager)
* Travis CI 

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
Run `npm run Package:platform` to package the project. 
The build artifacts will be stored in the out directory. Use the `:platform` flag to package for either Linux, Windows(Win32), Mac(Darwin).

### Running the app
To run the app, run `npm start`

### Running unit tests
Run `npm test` to execute the unit tests via [AVA].

### Running Test Runner 
Run `npm run watch` to run test on save.

### CI
Travis.yml file is included with example settings that enables CI with [Travis](https://travis-ci.org/).
Example CI is following a 'Branchy' approach(http://www.josra.org/blog/An-automated-git-branching-strategy.html).
Pushing a branch mathching the pattern /^ready\/.*$/ (ready/*) will trigger [Travis] to build/test and  if successful merge the feature branch with master and delete the feature branch.

### TODO
Live Reload
E2E
