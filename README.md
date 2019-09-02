#NPM Shadow Wizard Package


Just get your shadows and paddings right without messing it up.

#Installation
Just type in the following in your command-line : `npm -i shadowizard --save`

#Usage

```

import { shadowizard } from 'shadowizard';

shadowizard({
    shadow_type: 'soft',
    padding: false
});

```


## Options

Shadowizard has two modes:
+ *shadow_type* = _hard | soft_ (soft is default)
+ *padding* = _boolean_ (Default is false)