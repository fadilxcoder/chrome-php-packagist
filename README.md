Chrome PHP Logger
=======================================

<img style="width: 50px; vertical-align:middle;" src="https://lh3.googleusercontent.com/10bKCQrDOnfMZ9JmEwDObN02eeQWZuCHwhmlAUtKKDwzA6vQxlOptoGoUroXzU9giN8q7eUKqehjTfJCM4hnoCCijg=w128-h128-e365-rj-sc0x00ffffff" /> 

Chrome Logger is a Google Chrome extension for debugging server side applications in the Chrome console.

Most languages include their own logging capabilities, but sometimes it is easier to see your logs right in the browser.

[![developer](https://img.shields.io/badge/developer-craigiam-blue.svg)](https://craig.is/) [![developer](https://img.shields.io/badge/developer-fadilxcoder-green.svg)](https://dev.to/fadilxcoder/)

- Install the [Google Chrome extension](https://chrome.google.com/webstore/detail/chrome-logger/noaneddfkdjfnfdakjjmocngnfkfehhd?hl=en)
- Click the extension <img style="width: 15px; vertical-align:middle;" src="https://lh3.googleusercontent.com/10bKCQrDOnfMZ9JmEwDObN02eeQWZuCHwhmlAUtKKDwzA6vQxlOptoGoUroXzU9giN8q7eUKqehjTfJCM4hnoCCijg=w128-h128-e365-rj-sc0x00ffffff" />  icon in the browser to **enable** it for the current tab's domain
- Usage :
```php

...

use Logger\Chrome\ChromePhp;

...

class User {

    ....
    ChromePhp::log('hello world');
    ChromePhp::log($_SERVER);
    ChromePhp::warn('something went wrong!');
    ...

}

```

[Click for more information.](https://craig.is/writing/chrome-logger)

