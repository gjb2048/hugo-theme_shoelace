# Shoelace

Personal blog theme powered by [Hugo](https://gohugo.io).
Based upon [Minimal](https://themes.gohugo.io/themes/minimal/).

## Installation

You can install the theme either as a clone or submodule.

I recommend the latter. From the root of your Hugo site, type the following:

```
$ git submodule add https://github.com/gjb2048/hugo-theme_shoelace.git themes/shoelace
$ git submodule init
$ git submodule update
```

Now you can get updates to Shoelace in the future by updating the submodule:

```
$ git submodule update --remote themes/shoelace
```

## Configuration

After installation, take a look at the `exampleSite` folder inside `themes/shoelace`.

To get started, copy the `config.toml` file inside `exampleSite` to the root of your Hugo site:

```
$ cp themes/shoelace/exampleSite/config.toml .
```

Now edit this file and add your own information. Note that some fields can be omitted.

I recommend you use the theme's archetypes so now delete your site's `archetypes/default.md`.

## Run demo

hugo server --themesDir=../.. -disableFastRender


## Features

You can tweak the look of the theme to suit your needs in a number of ways:

- The accent colour can be changed by using the `accent` field in `config.toml`.

- You can also change the background colour by using `backgroundColor`.

- Add colored 5px borders at the top and bottom of pages by setting `showBorder` to `true`.

For best results, I recommend you use a dark accent colour with a light background, for example:

```toml
[params]
    accent = "red"
    showBorder = true
    backgroundColor = "white"
```

### Fonts

The theme uses local fonts. To change the font:

```toml
[params]
    font = "Open Sans" # Should match the name in the assets/scss/_fonts
```

## Refs

1. [How to cache-bust and concatenate JS and SASS files with Hugo in 2018](https://blog.fullstackdigital.com/how-to-cache-bust-and-concatenate-js-and-sass-files-with-hugo-in-2018-9266fd3c411e)
1. [How to use Hugo template variables in SCSS files (in 2018)](https://blog.fullstackdigital.com/how-to-use-hugo-template-variables-in-scss-files-in-2018-b8a834accce)
