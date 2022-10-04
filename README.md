# Clock - SASS project

This is a project of the [Understanding NPM - Node.js Package Manager](https://www.udemy.com/course/understanding-npm/) course. Some NPM packages were installed to master common commands in the Node Package Manager.

## About The Project

![Clock screenshot](./screenshot.jpg)

The project aims to:
- initialize a project using NPM by wrting `npm init -y`
- install, uninstall and update project dependencies. E.g.: `npm install <package>` 
- understand what is the [difference between dependencies and development dependencies](https://medium.com/@dylanavery720/npmmmm-1-dev-dependencies-dependencies-8931c2583b0c)
- explain what is [Semantic Versioning](https://semver.org/) and what different kinds of packages versions mean
- explain [difference between Browser Application and Server Package](https://nodejs.dev/en/learn/differences-between-nodejs-and-the-browser/)
- understand purpose of the ["package-lock"](https://docs.npmjs.com/cli/v8/configuring-npm/package-lock-json) file which is to keep track of the exact version of every package that is installed so that a project is 100% reproducible in the same way even if packages are updated by their maintainers.
- configure NPM scripts and execute them. E.g.: built-in scripts: `npm test`, `npm start` or custom scripts: `npm run <script>`
- combine NPM scripts into the one script. The [npm-run-all](https://www.npmjs.com/package/npm-run-all) was installed to run multiple npm-scripts in parallel or sequential
- explain what is [executable script](https://docs.npmjs.com/cli/v8/configuring-npm/package-json#bin). [Shebang](https://alexewerlof.medium.com/node-shebang-e1d4b02f731d) (#!) is the first line of the file which tells the OS which interpreter to use.

Live site: [https://alffonti.github.io/clock/index.html)

## Built with

- [NPM](https://www.npmjs.com/)
- [Moment](https://momentjs.com/)
- [Semver](https://www.npmjs.com/package/semver)
- [Colors](https://www.npmjs.com/package/colors)

## Acknowledgments

- [Bogdan Stashchuk](https://stashchuk.com/)

## Further reading

- [Difference between dependencies, devDependencies and peerDependencies](https://www.geeksforgeeks.org/difference-between-dependencies-devdependencies-and-peerdependencies/)
- [The difference between dependencies and devDependencies in a JavaScript project](https://dev.to/clairecodes/the-difference-between-dependencies-and-devdependencies-in-a-javascript-project-22f2)
-[A guide to creating a NodeJS command-line package](https://medium.com/netscape/a-guide-to-create-a-nodejs-command-line-package-c2166ad0452e)
