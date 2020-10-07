# eslint-plugin-modules-newline-fixed

Forked from [eslint-plugin-modules-newline](https://github.com/gmsorrow/eslint-plugin-modules-newline):

Eslint plugin to enforce placing import and export variables on separate lines


## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```
or 
```
$ yarn add eslint --dev
```

Next, install `eslint-plugin-modules-newline-fixed`:

```
$ npm install eslint-plugin-modules-newline-fixed --save-dev
```
or
```
$ yarn add eslint-plugin-modules-newline-fixed --dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-modules-newline-fixed` globally.

## Usage

Add `eslint-plugin-modules-newline-fixed` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "modules-newline-fixed"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "modules-newline/import-declaration-newline-fixed": "warn",
        "modules-newline/export-declaration-newline-fixed": "warn"
    }
}
```

## Supported Rules

* Enforce placing import variables on separate lines (import-declaration-newline)
* Enforce placing export variables on separate lines (export-declaration-newline)

## For maintainers
AST explorer - https://astexplorer.net/#/gist/b6093767261d6a5bce76043dcea24bec/5fe761308f41936beaa30cbe7aef3a6f0283e11d




