```json
{
  "workbench.iconTheme": "material-icon-theme",
	"editor.tabSize": 2,
	"editor.insertSpaces": true,
  "editor.detectIndentation": false,

  // + jshint configuration
  "jshint.options":{
    "esversion": 9
  },

  // + eslint configuration
  "eslint.options": {
    "env":{
      "es6": true
    },
    "parserOptions": {
      "ecmaVersion": 9 // or 6,7,8,9,10
    }
  },

  // + Window opacity
  "winopacity.opacity": 255,

  // + Better Comments configuration
  "better-comments.tags": [
    { // warning
      "tag": "!",
      "color": "#ff3300",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // make a question
      "tag": "?",
      "color": "#004dff",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // results, solutions, best practices
      "tag": "=>",
      "color": "#4cff00",
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
      "color": "#ffb300",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // NOTE: something important, explain something
      "tag": "note",
      "color": "#ff00cc",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    { // add many comments
      "tag": "*",
      "color": "#474747",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      // something else and other stuffs
      "tag": "+",
      "color": "#ccff00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    }
  ],

  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  // NOTE: When moving file or folder, import path is changed
  "javascript.updateImportsOnFileMove.enabled": "always",

  // + Fira Code
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,

  // + Live SCSS Compiler
  "liveSassCompile.settings.formats": [
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/css"
    }
  ],

  // + Window Customize
  "workbench.colorCustomizations": {
    "activityBar.background": "#f43d55",
    "activityBar.foreground":"#F6FCF5",
    "activityBar.inactiveForeground": "#F6FCF5",
    "titleBar.activeBackground": "#df244e",
    "titleBar.activeForeground": "#F6FCF5",
    "statusBar.background": "#df244e",
    "statusBar.foreground": "#F6FCF5",
    "tab.activeBorder": "#f43d55"
  },
  "workbench.colorTheme": "CodeSandbox"
}
```
