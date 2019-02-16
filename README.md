# AposThemeNaturalDocs
Apos' Dark theme for Natural Docs.

## Installation Guide

1. Copy the `AposAPITheme` folder to your project's NaturalDocs config folder. This is the same folder that contains your `Project.txt` file.
2. Edit `Project.txt` and add this line under your title and subtitle: `Style: AposAPITheme`.
3. ????
4. PROFIT!!!

## Examples

* https://apostolique.github.io/Apos.Gui/
* https://apostolique.github.io/Apos.Input/

## Fancy Upgrade

To add a link to your repository on the documentation's front page. First generate the documentation, then manually add this line to `other/home.html`. Place is below the `HSubtitle` div. Make sure to use your own links.

```
<div class="HRepo"><a target="_blank" href="https://github.com/Apostolique/Apos.Gui">https://github.com/Apostolique/Apos.Gui</a></div>
```

To add a link to your repository in the top left, manually add this line to `index.html`. Place it between the `HSubtitle` div and the `<input/>` tag. Make sure to use your own links.

```
<div id="HRepo"><a target="_blank" href="https://github.com/Apostolique/Apos.Gui">https://github.com/Apostolique/Apos.Gui</a></div>
```
