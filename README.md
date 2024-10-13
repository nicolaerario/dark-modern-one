# Dark Modern One - VSCode Theme

This theme is inspired by the default `VSCode Dark Modern` theme, but with a twist.  
It leverages the default token colors for a familiar coding experience, while incorporating elements of the popular `One Dark Pro` theme for a more visually appealing editor.  
The color palette has been carefully adjusted to provide better contrast and a more cohesive overall look.

## Add Italics

To enable italic text for specific syntax elements (e.g., comments, variables), add the following snippet to your settings.json file:

```json
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "constant.language",
          "entity.other.attribute-name",
          "keyword.control",
          "keyword.operator.expression",
          "keyword.operator.new",
          "storage",
          "variable.language",
          "variable.parameter"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "scope": "storage.type.function.arrow",
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  }
```

### Suggested fonts

[IBM Plex Mono](https://github.com/IBM/plex)  
[JetBrains Mono](https://github.com/JetBrains/JetBrainsMono)  
[MonaSpace Neon](https://github.com/githubnext/monaspace)

### Credits

[VSCode team](https://github.com/microsoft/vscode)  
[binaryify](https://github.com/Binaryify/OneDark-Pro)
