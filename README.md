# dome-color-filter
A drop-in color simulator to aid in developing for Color Vision Deficient Gamers

Import this into your DOME game by doing:

```wren
  ...
  // After all draw code

  var palette = 0 // This can be from 0..8
  import "./filter" for ColorBlindFilter
  ColorBlindFilter.apply(palette)

```

You won't want to ship this during production, as it is very slow, but it is sufficient for development purposes.

Get [more information](http://gameaccessibilityguidelines.com/ensure-no-essential-information-is-conveyed-by-a-colour-alone/) on guidelines for CVD gamers.

