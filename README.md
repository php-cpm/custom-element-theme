# element-theme
[![Build Status](https://travis-ci.org/ElementUI/element-theme.svg?branch=master)](https://travis-ci.org/ElementUI/element-theme)
[![npm](https://img.shields.io/npm/v/element-theme.svg)](https://www.npmjs.com/package/element-theme)

> Theme generator cli tool for Element.

![](./media/element.gif)

## Installation
```shell
npm i element-theme -g

npm install
```


## CLI
```shell
# init variables file
et --init [file path]

# build theme
et

# gulp css name wrapper
gulp

# more cmds

# edited mixin file
cp -R mixins/_button.scss node_modules/element-theme-chalk/src/mixins/

# just et && gulp
npm run build
# just cp mixin file to nodeModule
npm run mixin
```


## License
MIT
