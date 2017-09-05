
In this docker image, chrome will run as root, so use '--no-sandbox' option while starting puppeteer.

```js
const puppeteer = require('puppeteer');

puppeteer.launch({ args: ['--no-sandbox'] });
```