# UX Toolkit Acme

This repository demonstrates how you can create your own UX Toolkit registry, 
and make it available for Symfony apps.

## Create your theme

A theme is based on a `manifest.json`, components, examples, and must be located at `themes/<theme>`.

### Manifest file

The `manifest.json` file contains precious metadata about the theme, like its name, authors, and homepage:

```json
{
    "name": "My theme",
    "licenses": ["MIT"],
    "homepage": "https://github.com/MySelf/MyUxToolkitThemes",
    "authors": ["Me"]
}
```

### Components 

Components are located under `themes/<theme>/components` folder.

### Examples 

Components are located under `themes/<theme>/examples` folder.

## Lint and debug

```shell
php bin/ux-toolkit-theme-lint my-theme
php bin/ux-toolkit-theme-debug my-theme
```
