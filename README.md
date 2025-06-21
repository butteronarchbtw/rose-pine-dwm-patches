# rose pine dwm patches

this provides some basic patches for applying [Rose Pine](https://rosepinetheme.com/) to dwm

the folders are named after the respective accent color (which can be found on the [Rose Pine website](https://rosepinetheme.com/palette/ingredients/))

## applying a patch

just as you would with all other dwm patches too, e.g.

```sh
patch < <folder-where-patch-is-located>/rose-pine/rose-pine-iris.patch
```

you might need to apply patches manually if conflicts occur (this can happen with any other dwm patch too)

## Contributing

This theme is built using [bloom](https://github.com/rose-pine/rose-pine-bloom):

```sh
# Install bloom
curl -sf http://goblin.run/github.com/rose-pine/rose-pine-bloom@v2 | sh

# Build themes
rose-pine-bloom template.patch
```
