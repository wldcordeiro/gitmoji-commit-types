# gitmoji-commit-types

[![npm](https://img.shields.io/npm/v/gitmoji-commit-types.svg?maxAge=2592000)](https://www.npmjs.com/package/conventional-commit-types)

List of [Gitmoji](https://gitmoji.carloscuesta.me/) commit types.

## Spec

Exports an object with a `types` key whose value is an object whose keys are type emojis and whose values are objects with key-value pairs such as `description` as string, optional `title` as string, etc. See [index.json](index.json). Any alternatives should follow the same spec.

## Etc.

Used by [wldcordeiro/cz-gitmoji-changelog](https://github.com/wldcordeiro/cz-gitmoji-changelog) for [commitizen/cz-cli](https://github.com/commitizen/cz-cli).

Can be used with [kentcdodds/validate-commit-msg](https://github.com/kentcdodds/validate-commit-msg#types).

Commit types originally from:
* [Gitmoji](https://gitmoji.carloscuesta.me/)
* [Angular Git Commit Message Conventions](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#type)
* [commitizen/cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog)
