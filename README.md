# Empty Themes for Visual Studio Code

This theme does not include color settings such as `tokenColors`.  
Use this when you want to manage colors in `settings.json`.

```json
{
    "editor.tokenColorCustomizations": {
        "textMateRules": [
          {
            "scope": [
              "comment"
            ],
            "settings": {
              "foreground": "#D0D0D0"
            }
          },
          {
            "scope": [
              "invalid.illegal"
            ],
            "settings": {
              "foreground": "#FF7060"
            }
          },
          {
            "scope": [
              "invalid.deprecated"
            ],
            "settings": {
              "foreground": "#FFA090"
            }
          }
       ]
    }
}
```
