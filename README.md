# Resilient PHP Application Template

Note: still a work in progress, use at your own risk.

## Introduction

This template repository is intended for use as a starting point for any PHP application which needs to quickly:

1. Deploy to production and distribution channels
2. Read, write, and document its source code
3. Enforce code style standards
4. Onboard new developers
5. Be compatible with both Windows and Linux-based operating systems.

You may fork this project and apply framework-specific features. I plan on doing so for WordPress and Laravel.

I will move the VSCode directory's contents to a `/bin/vscode/*.sh` file you can execute to create those files if, like me, you wish to use them. Providing them like this makes those files optional. If you have a cleaner alternative please open an issue on the project's Github repository.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Documentation](#documentation)
4. [Contributing](#contributing)
## Features

This package uses:

1. Backwards compatibility (babel, autoprefixer)
2. Linting (eslint, prettier)
3. Minification
4. Obfuscation
5. Git hook-initialized linting

Still needing implementation:
5. Image compression

Global requirements:
1. ESLint `$ npm i -g eslint`
1. Prettier `$ npm i -g prettier`

https://glebbahmutov.com/blog/configure-prettier-in-vscode/

## Installation

1. `$ npm start` - Installs JS and build dependencies from NPM and initialize certain aspects of the repository; should only be run after downloading the repository for the first time.
2. `$ composer install` - Installs PHP dependencies.

## Documentation:
* PHPDoc Reference - <https://docs.phpdoc.org/3.0/guide/references/phpdoc/index.html>
* PHP Framework Interop Group - <https://www.php-fig.org/>
* Sass Lint Reference - <https://github.com/sasstools/sass-lint> (abandoned but stable)
* NPM package schema - <https://docs.npmjs.com/cli/v7/configuring-npm/package-json>
* Composer package schema - <https://getcomposer.org/doc/04-schema.md>
* The Software Package Data Exchange:reg: - <https://spdx.dev/>

## Contributing

I welcome questions and discussion and have opened up Github's features to create a space for this: https://github.com/zachwatkins/resilient-php/discussions. If you find an issue, please report it here: https://github.com/zachwatkins/resilient-php/issues. Regarding requests for supporting any particular JavaScript or PHP framework, I will accept issues or pull requests if the change is small and prevents the framework from using this template project when you implement the third party framework in its default configuration. Please see the [contribution guidelines](./CONTRIBUTING.md) for details.

[Back to top](#introduction)

---
*Free open source software under the MIT License.*  
*Copyright Zachary Kendall Watkins 2021*
