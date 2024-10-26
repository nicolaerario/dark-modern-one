# Dark Modern One - VSCode Theme

This theme is inspired by the default `VSCode Dark Modern` theme, but with a twist.  
It leverages the default token colors for a familiar coding experience, while incorporating elements of the popular `One Dark Pro` theme for a more visually appealing editor.  
The color palette has been carefully adjusted to provide better contrast and a more cohesive overall look.

## Screenshots

![alt text](./images/Screenshot_wp.png 'Welcome screen')
![alt text](./images/Screenshot_full.png 'Full example')

## Italics

Italic text is enabled by default for specific syntax elements, like:

```json
"comment",
"constant",
"attribute-name",
"keyword",
"storage", // BUT not for arrow functions =>
"variable",
```

To take full advantage of the italics, I recommend setting a font that provides for it (see [suggested fonts](#suggested-fonts)):

```json
// settings.json

"editor.fontFamily": "'IBM Plex Mono', 'JetBrains Mono', ... ",
```

If you don't like italics, you can choose the `No italics` variant of the theme.

### Suggested fonts

[IBM Plex Mono](https://github.com/IBM/plex)  
[JetBrains Mono](https://github.com/JetBrains/JetBrainsMono)  
[MonaSpace Neon](https://github.com/githubnext/monaspace)

### Credits

[VSCode team](https://github.com/microsoft/vscode)  
[binaryify](https://github.com/Binaryify/OneDark-Pro)
