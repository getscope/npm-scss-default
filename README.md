# SCSS Default

NPM Repository for installing reset styles.

## Installation

You can install the package:

```bash 
npm install --save https://github.com/getscope/npm-scss-default
```

or include the dependency in the `package.json` file:

```json
{
    "dependencies": {
        "@getscope/npm-scss-default": "github:getscope/npm-scss-default"
    }
}
```

and run the following command in the CLI:

```bash 
npm update
```

## Examples of use

### SCSS

```scss 
@import "node_modules/@getscope/npm-scss-default/src/scss/components/_base.scss";

@import "node_modules/@getscope/npm-scss-default/src/scss/components/_form.scss";

@import "node_modules/@getscope/npm-scss-default/src/scss/_all.scss";
```

## Development dependencies

```json 
{
    "devDependencies": {
        "resolve-url-loader": "^3.1.0",
        "sass": "^1.26.10",
        "sass-loader": "^8.0.0"
    }
}
```

## Licenses

* The software is licensed under the [MIT license](https://github.com/getscope/npm-scss-default/blob/main/LICENSE).
