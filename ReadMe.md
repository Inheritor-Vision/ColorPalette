# Color Palette Generator from Image

Require Jimp lib (from npm) & NodeJS. To be rewriten in either Rust or Python. Based on Adobe-Color-CC.

Output is the Color Palette respresented as an array of hexcode jsonified.

Usage:
```
node colorPalette IMAGE MODE COUNT

```

Result example:
```
["#9fb3bf","#5f6b73","#bfa07a","#f2f2f2","#262626"]
```

with:

- Image: Path to image
- MODE: Either `bright`, `dark`, `muted`, `deep` (I like this one for color scheme), `colorful` or `blank`. Other options ignored in favor of `colorful`.
- COUNT: Size of the color palette.

