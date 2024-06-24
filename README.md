# Obsidian Chameleon Theme

A simple color palette switcher for obsidian.
It aims at keeping the per-theme configuration very simple, in order to easily support multiple themes and to avoid getting lost in pointless configuration details.

## Project Overview

```
├── src       # SCSS source folder
│   ├── custom    # Obsidian theme customization
│   ├── snippets  # Style Settings extension snippets
│   └── themes    # Color Themes
```

## Themes

See the [`themes/`](./src/themes) folder for existing themes. They all follow the same pattern:

1. Implement the theme's color palette
2. Implement the generic colors required in the [`commons.scss`](./src/themes/commons.scss) file.

## Build

Build with the following command:

```bash
sass src:. --no-source-map --watch
```
