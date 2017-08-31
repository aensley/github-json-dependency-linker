# GitHub JSON Dependency Linker

**[![INSTALL](https://img.shields.io/badge/INSTALL-1.0.0-blue.svg?style=plastic)](https://github.com/aensley/github-json-dependency-linker/raw/master/GitHub_JSON_Dependency_Linker.user.js)**

## Description

This simple user script adds links to dependencies listed in JSON files on GitHub. It is based on [@jerone](https://github.com/jerone)'s [UserScripts](https://github.com/jerone/UserScripts/tree/master/Github_JSON_Dependencies_Linker) project.

The following JSON schemes are supported:
* [Atom](https://atom.io) - `package.json`
* [Bower](http://bower.io) - `bower.json`
* [Composer](https://getcomposer.org/) - `composer.json`
* [NPM](https://www.npmjs.com) - `package.json` & `npm-shrinkwrap.json`
* [NuGet](https://www.nuget.org) - `project.json`

In the JSON file it will search for the following dependency keys:
* `require`
* `require-dev`
* `dependencies`
* `devDependencies`
* `peerDependencies`
* `bundleDependencies`
* `bundledDependencies`
* `packageDependencies`
* `optionalDependencies`
