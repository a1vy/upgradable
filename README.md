# Upgradable

[![NPM](https://nodei.co/npm/upgradable.png)](https://nodei.co/npm/upgradable/)

Prompt your users to upgrade your node CLI tool if there's a new version available
> Prompts at end of interaction when user sends interrupt signal (ctrl+c)

Use
```js
const upgradable = require('upgradable');
const { name, version } = require('./package.json');

upgradable({name, version});
```

Shorthand
```js
require('upgradable')(require('./package.json'));
```


<img width="590" alt="image" src="https://user-images.githubusercontent.com/516342/36251069-8125d026-1248-11e8-86c7-8b4307a5774c.png">