# eslint-plugin-modules-newline-fixed

Forked from [eslint-plugin-modules-newline](https://github.com/gmsorrow/eslint-plugin-modules-newline)

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
        "modules-newline-fixed/import-declaration-newline": "warn",
        "modules-newline-fixed/export-declaration-newline": "warn"
    }
}
```

## Supported Rules

* Enforce placing import variables on separate lines (import-declaration-newline)
* Enforce placing export variables on separate lines (export-declaration-newline)
