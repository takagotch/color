### Color 
---
https://www.webpagefx.com/web-design/color-picker/

### 憲法色　Kenpo-color
#543f32

---

.js
https://github.com/Qix-/color

.go
https://github.com/fatih/color

```js
var color = Color('#7743CE').alpha(0.5).lighten(0.5);
console.log(color.hsl().string());
console.log(color.cmyk().round().array());
console.log(color.ansi256().object());

var Color = require('color');

var color = Color('rgb(255, 255, 255)')
var color = Color({r: 255, g: 255, b: 255})
var color = Color.rgb(255, 255, 255)
var color = Color.rgb([255, 255, 255])

color.hsl();

color.object();

color.rgb().array()

color.rgbNumber()
color.hex()
color.red()
color.hsl().string()
color.luminosity();
color.contrast(Color("blue"))
color.isLight();
color.isDark();
color.negate()
color.lighten(0.5)
color.darken(0.5)
color.saturate(0.5)
color.desaturate(0.5)
color.grayscale(0.5)
color.whiten(0.5)
color.blacken(0.5)
color.fade(0.5)
color.opaquer(0.5)
color.rotate(180)
color.rotate(180)
color.mix(Color("yellow"))
color.mix(Color("hyellow"), 0.3)
color.green(100).grascale().lighen(0.6)

```

```
npm install color
```

