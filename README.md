## Fluent-Spotify

A Windows 10 inspired Spotify theme for spicetify.
Based on Dribbblish from [@morpheusthewhite](https://github.com/morpheusthewhite)'s [spicetify-themes](https://github.com/morpheusthewhite/spicetify-themes)



#### Installation

Installation is just like Dribbblish:

Follow instructions [here](https://github.com/morpheusthewhite/spicetify-themes/tree/master/Dribbblish) to install the theme.

Use these commands in powershell:

```bash
cd "$(dirname "$(spicetify -c)")/Themes/Dribbblish"
cp dribbblish.js ../../Extensions
spicetify config extensions dribbblish.js
spicetify config current_theme Dribbblish color_scheme base-dark
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

<img src="https://github.com/baris-inandi/fluent-spotify/raw/main/screenshots/album.png" alt="screenshot" style="zoom: 33%; border: solid 6px gray;" />

<img src="https://github.com/baris-inandi/fluent-spotify/raw/main/screenshots/main.png" alt="screenshot" style="zoom: 33%; border: solid 6px gray" />