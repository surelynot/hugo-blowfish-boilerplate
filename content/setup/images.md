---
title: 'Image use'
description: 'How to use images on the site.'
series: ["setup-steps"]
series_order: "1"
---

The post can include images in three ways, via single image, gallery or carousel. Save images in sub-folders to more easily call them.

Using [Figure](https://blowfish.page/docs/shortcodes/#figure) to add single images (which are optimised automatically). The below path is the same location as this file.

```
![Alt text](image.jpg "Image caption")
```

Use [Carousel](https://blowfish.page/docs/shortcodes/#carousel) to include **all** images in a folder (in the same folder as this file) named `carousel`

```
{{</* carousel images="carousel/*"}}
```

Use [Gallery](https://blowfish.page/docs/shortcodes/#gallery) to include images in a folder (in the same folder as this file) named `gallery`. These need to be named individually.

```
{{<gallery */>}}
  <img src="gallery/01.jpg" class="grid-w33" />
  <img src="gallery/02.jpg" class="grid-w33" />
{{</* /gallery */>}}
```
