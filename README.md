# 🎨 Obsidian Vanilla Theme Palettes

A simple theme color palette switcher for Obsidian for theme hoppers.
It includes many popular themes without changing the vanilla interface.

The [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin is required in order to switch themes.

![Theme illustration](./vanilla%20theme%20palettes.png)

Featured themes:

- Atom One Dark
- Catppuccin
- Dracula
- Gruvbox
- Horizon
- Kanagawa
- Nord
- Rose Pine
- Tokyo Night

## Project Overview

```
├── src       # SCSS source folder
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
npm install -g sass
sass src:. --no-source-map --watch
```
