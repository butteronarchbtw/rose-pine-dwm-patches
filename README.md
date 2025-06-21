# rose pine dwm patches

this provides some basic patches for applying [Rose Pine](https://rosepinetheme.com/) to dwm

the folders are named after the respective accent color (which can be found on the [Rose Pine website](https://rosepinetheme.com/palette/ingredients/))

## applying a patch

just as you would with all other dwm patches too, e.g.

```
$ cd <folder-where-dwm-source-is-located>
$ patch < <folder-where-patch-is-located>/iris/iris.patch
```

you might need to apply patches manually if conflicts occur (this can happen with any other dwm patch too)

## future work

- add dawn & moon palettes

## Contributing

This theme is built using [bloom](https://github.com/rose-pine/rose-pine-bloom):

```sh
# Install bloom
curl -sf http://goblin.run/github.com/rose-pine/rose-pine-bloom@v2 | sh

# Build themes
rose-pine-bloom template.patch
```
