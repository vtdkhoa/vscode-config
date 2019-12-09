```json
{
  "workbench.colorTheme": "CodeSandbox",
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  // jshint configuration
  "jshint.options": {
    "esversion": 9,
  },
  // eslint configuration
  "eslint.options": {
    "env":{
      "es6": true
    },
    "parserOptions": {
      "ecmaVersion": 9 // or 6,7,8,9,10
    }
  },
  "workbench.iconTheme": "material-icon-theme",
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.detectIndentation": false,
  "winopacity.opacity": 255,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "explorer.confirmDragAndDrop": false,
  // Better Comments configuration
  "better-comments.tags": [
    { // warning
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // make a question
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // results, solutions, best practices
      "tag": "=>",
      "color": "#00FF00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // add a comment
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "backgroundColor": "transparent"
    },
    { // explain methods
      "tag": "todo",
      "color": "#FF8C00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // note something
      "tag": "note",
      "color": "#FF69B4",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // add many comments
      "tag": "*",
      "color": "#808080",
      "strikethrough": false,
      "backgroundColor": "transparent"
    }
  ],
  // Fira Code
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  // Live Sass
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    }
  ],
  "liveServer.settings.donotVerifyTags": true,
  // Window colors
  "workbench.colorCustomizations": {
    "activityBar.background": "#f43d55",
    "activityBar.foreground":"#F6FCF5",
    "activityBar.inactiveForeground": "#F6FCF5",
    "titleBar.activeBackground": "#df244e",
    "titleBar.activeForeground": "#F6FCF5",
    "statusBar.background": "#df244e",
    "statusBar.foreground": "#F6FCF5",
    "tab.activeBorder": "#f43d55"
  }
}
```
