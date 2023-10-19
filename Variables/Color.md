The color variable is a representation of four different numbers. Each representing a different colour channel and each having a minimum of 0 and a maximum of 1.

The four channels in question are: Red, Green, Blue, Alpha

The first three are explanatory but you may not have heard of alpha. Alpha is a certain colours transparency. If the alpha value is 1, the colour will be fully visible. If the alpha value is 0, the colour will be completely invisible.

**Colour variable examples:**
```
var red = Color(1, 0, 0, 1)

var green = Color(0, 1, 0, 1)

var purple = Color(1, 0, 1, 1)

var invisible = Color(0, 0, 0, 0)
```