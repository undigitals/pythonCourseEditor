# Python Curriculum & Live Editor

### Left Sidebar

On the left sidebar there will be sections

### Right Sidebar

On the right sidebar there will be sub-sections

## Theme Colors

## Syntax Colors

Document uses [@theme-ui/prism](https://theme-ui.com/prism) for syntax highlighting. Different presets can be used by editing the file at `src/gatsby-plugin-theme-ui/index.js`. The desired preset must be included at the top of the file and spread into the `pre` styles

```javascript
import dracula from '@theme-ui/prism/presets/dracula.json';

styles: {
  pre: {
    ...dracula,
  }
}
```

The code blocks will not change color based on the color modes. For a complete list of all available prism presets, check out the Theme UI [syntax themes](https://theme-ui.com/prism#syntax-themes).
the page.

```md
---
title: "Section Title"
description: "Section description"
---
```
