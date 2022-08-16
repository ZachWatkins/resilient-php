# Developing on Windows

I developed this repository on Windows and I hope this file includes everything needed to get started off right.

## Git

Run this to set up Git for an optimal experience.

```shell
git config --global core.autocrlf false
git config --global core.eol lf
git config --global init.defaultBranch main
```

I originally used custom Git hooks to perform linting before comitting changes to my repository. Now I use the Husky module.

### Github Pages

This repository uses a Github Pages NPM module 
