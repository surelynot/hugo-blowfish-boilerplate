---
title: 'Series setup'
description: 'Add series.'
series: ["setup-steps"]
series_order: "3"
---

### Taxonomy

The first step to enable series is to create the series taxonomy. Add the series to the taxonomy list in `config.toml`.

```
[taxonomies]
  tag = "tags"
  category = "categories"
  author = "authors"
  series = "series"
  setup-steps = "setup-steps"
```

### Identify content
In `Front Matter` add:
```
series: ["setup-steps"]
series_order: 3
```

### Decide open/closed display
Choose to show it closed or open in the `params.toml` using for a global setting, or in `Front Matter` with `seriesOpened` for an individual page behaviour.