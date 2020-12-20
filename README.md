# Babel Plugin Goober CSS Prop

Most of the code here is from [`babel-plugin-css-prop`](https://github.com/satya164/babel-plugin-css-prop) which has been customised for [`goober`](https://github.com/cristianbote/goober)

![npm (scoped)](https://img.shields.io/npm/v/@agney/babel-plugin-goober-css-prop?style=flat-square)
[![Twitter Follow](https://img.shields.io/twitter/follow/agneymenon?style=flat-square&color=informational)](https://twitter.com/agneymenon)

```bash
# Installation
npm install --save-dev @agney/babel-plugin-goober-css-prop
```

## Usage

In `.babelrc` (or any babel configuration type):

```json
{
  "plugins": [
    "babel-plugin-transform-goober",
    "@agney/babel-plugin-goober-css-prop"
  ]
}
```


This has been tested only for a specific use case for usage with [`twin.macro`](https://github.com/ben-rogerson/twin.macro). Any contributions welcome.