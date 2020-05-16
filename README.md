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
num_array = list()
num = raw_input("Enter how many elements you want:")
print 'Enter numbers in array: '
for i in range(int(num)):
    n = raw_input("num :")
    num_array.append(int(n))
print 'ARRAY: ',num_array

# second ver
arr = list(map(int, input().split()))

# third ver
n = int(input)
arr = [ int(input()) for i in range(n)]