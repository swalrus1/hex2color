# hex2color

The name is pretty self-explanatory. Use HEX color values in LÖVE.

## How to

```lua
Color = require "hex2color"

pink = Color("#ea306d")
```

#### Color(hex, opacity)

returns a table representing the color

+ hex - the color value starting with `#`
+ opacity - opacity value [0, 1]
