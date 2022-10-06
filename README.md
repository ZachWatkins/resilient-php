# JavaScript Examples

## Build Tools

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

## Files Explained

1. .nvmrc - Node version compatible with this project.

https://github.com/webpack-contrib/mini-css-extract-plugin

## Using React

To use this framework with React install the following libraries:

```shell
npm i -D eslint-plugin-react
```

Modify .eslintrc.js:

```js
"extends": ["...", "plugin:react/recommended"]
```

# Links to relevant documentation:
* PHPDoc Reference - <https://docs.phpdoc.org/3.0/guide/references/phpdoc/index.html>
* Sass Lint Reference - <https://github.com/sasstools/sass-lint> (abandoned but stable)
* PHP CodeSniffer Wiki - <https://github.com/squizlabs/PHP_CodeSniffer/wiki/Usage>
* NPM package schema - <https://docs.npmjs.com/cli/v7/configuring-npm/package-json>
* Composer package schema - <https://getcomposer.org/doc/04-schema.md>
* The Software Package Data Exchange:reg: - <https://spdx.dev/>
* PHP Framework Interop Group - <https://www.php-fig.org/>

## Command Line Tasks

1. `$ npm start` - Used to install dependencies from NPM and initialize certain aspects of the repository; should only be run after downloading the repository for the first time.

## Recommendations

I recommend you provide a "SECURITY.md" file which informs users how to disclose security issues with discretion and also notes security aspects which users are responsible for implementing. You may also wish to include a "CONTRIBUTORS.md" file if you work with a team or if the public contributes to your project.
