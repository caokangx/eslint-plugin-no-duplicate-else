# eslint-plugin-no-duplicate-else

this plugin provides a new rules which enforce no duplicate else

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-no-duplicate-else`:

```
$ npm install eslint-plugin-no-duplicate-else --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-no-duplicate-else` globally.

## Usage

Add `no-duplicate-else` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "no-duplicate-else"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "no-duplicate-else/rule-name": 2
    }
}
```

## Supported Rules

[no-dupe-else-if](./docs/rules/no-dupe-else-if.md)




