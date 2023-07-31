---
title: 'Fonts setup'
description: 'Add custom fonts.'
series: ["setup-steps"]
series_order: "2"
---
Fonts can be added, [see here](https://blowfish.page/docs/advanced-customisation/#using-additional-fonts)

Now, the font can just import it in your `custom.css` and replaced wherever you see fit. The example below shows what replacing the font for the entire html would look like.
```
@font-face {
    font-family: font;
    src: url('/fonts/font.ttf');
}

html {
    font-family: font;
}
```

Changing the font size of your website is one example of overriding the default stylesheet, which uses scaled font sizes throughout the theme which are derived from the base HTML font size. By default, the size is 12pt, but it can be changed to whatever value you prefer.

Create a `custom.css` file using the instructions above and add the following CSS declaration:

```
/* Increase the default font size */
html {
  font-size: 13pt;
}
```