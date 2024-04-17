# vs-code-settings

```
{
  "editor.suggestSelection": "recentlyUsedByPrefix",
  "editor.tabCompletion": "on",
  "editor.snippetSuggestions": "inline",
  // "editor.fontFamily": "Fira Code, Dank Mono, JetBrains Mono, Operator Mono Lig",
  // "editor.fontLigatures": true,
  // # Cascadia Settings
  "editor.fontFamily": "Cascadia Code PL",
  "editor.fontLigatures": "'calt', 'ss01'",
  "editor.fontSize": 14,
  "editor.guides.indentation": true,
  // * terminal font
  "terminal.integrated.fontFamily": "Cascadia Code",
  "terminal.integrated.fontSize": 14,
  // * debug console font
  "debug.console.fontSize": 14,
  "debug.console.fontFamily": "Cascadia Code PL",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "javascript.autoClosingTags": true, // Disable JSX tag closing
  "emmet.triggerExpansionOnTab": true,
  "explorer.confirmDragAndDrop": false,
  "javascript.format.enable": true,
  // "eslint.enable": true,
  // "[css]": {
  // 	"editor.defaultFormatter": "vscode.css-language-features"
  // },
  // ## limit tabs
  "workbench.editor.limit.enabled": true,
  "workbench.editor.limit.value": 30,
  "workbench.tips.enabled": false,
  "workbench.iconTheme": "material-icon-theme",
  "workbench.tree.indent": 14,
  "explorer.confirmDelete": false,
  "git.enableSmartCommit": false,
  "files.associations": {
    "*.jsx": "javascriptreact",
    "*.js": "javascript",
    "*.tsx": "typescriptreact",
    "*.ascx": "html"
  },
  "projectManager.hg.ignoredFolders": [
    "node_modules",
    "out",
    "typings",
    "test",
    ".haxelib"
  ],
  "terminal.integrated.cursorStyle": "block",
  "diffEditor.renderSideBySide": true,
  "extensions.ignoreRecommendations": false,
  "explorer.compactFolders": false,
  "explorer.sortOrder": "foldersNestsFiles",
  "workbench.sideBar.location": "left",
  "projectManager.git.baseFolders": ["~/codebase"],
  "colorize.languages": ["javascriptreact", "javascript", "css", "scss"],
  "editor.linkedEditing": true,
  "redhat.telemetry.enabled": false,
  "security.workspace.trust.untrustedFiles": "open",
  "yaml.schemas": {
    "file:///Users/patrickbradshaw/.vscode/extensions/atlassian.atlascode-2.10.7/resources/schemas/pipelines-schema.json": "bitbucket-pipelines.yml"
  },
  // # Peacock
  "peacock.affectActivityBar": false,
  // # Better comments
  "better-comments.tags": [
    {
      "tag": "!",
      "backgroundColor": "red",
      "strikethrough": false,
      "color": "white"
    },
    {
      "tag": ":!",
      "backgroundColor": "transparent",
      "color": "#c62828"
    },
    {
      "tag": "^",
      "backgroundColor": "#ffee58",
      "color": "black"
    },
    {
      "tag": ":^",
      "color": "#ffee58",
      "backgroundColor": "transparent"
    },
    {
      "tag": ":$",
      "backgroundColor": "transparent",
      "color": "#00c853"
    },
    {
      "tag": "$",
      "backgroundColor": "#00c853",
      "color": "black"
    },
    {
      "tag": ":?",
      "color": "#2962ff",
      "backgroundColor": "transparent"
    },
    {
      "tag": "?",
      "backgroundColor": "#2962ff",
      "color": "white"
    },
    {
      "tag": "#",
      "backgroundColor": "#546e7a",
      "color": "#fff"
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "backgroundColor": "transparent"
    },
    {
      "tag": "todo",
      "backgroundColor": "#FF8C00",
      "strikethrough": false,
      "color": "#000"
    },
    {
      "tag": "*",
      "backgroundColor": "#00796b",
      "strikethrough": false,
      "color": "white"
    }
  ],
  "todo-tree.general.tags": [
    "BUG",
    "HACK",
    "FIXME",
    "TODO",
    "XXX",
    "[ ]",
    "[x]",
    "vipernest [ ]"
  ],
  "workbench.colorTheme": "Night Owl",
  "editor.cursorBlinking": "phase",
  "terminal.integrated.cursorBlinking": true,
  "js/ts.implicitProjectConfig.checkJs": true,
  "codestats.apikey": "SFMyNTY.Y0dGMGNtbGphMkk0TkE9PSMjTVRnMk1qZz0.cAD8aMD23mJyK8st4X3dyB5lbkavV8uCOO44mgEzJA0",
  // "workbench.editor.tabSizing": "fit",
  // --------------------------------------
  // PRETTIER ----------------------------------
  // "prettier.singleQuote": true,
  // "prettier.jsxSingleQuote": true,
  // "prettier.trailingComma": "none",
  // "prettier.arrowParens": "avoid",
  // "prettier.proseWrap": "preserve",
  // "prettier.quoteProps": "as-needed",
  // "prettier.bracketSameLine": false,
  // "prettier.bracketSpacing": true,
  // "prettier.tabWidth": 4,
  // Markdown
  "[markdown]": {
    "editor.quickSuggestions": {
      "comments": "on",
      "strings": "on",
      "other": "on"
    }
  },
//   "editor.tabSize": 3,
  // // JSON
  // "[json]": {
  //   "editor.defaultFormatter": "esbenp.prettier-vscode"
  // },
  // // JavaScript
  // "[javascript]": {
  //   "editor.defaultFormatter": "esbenp.prettier-vscode"
  // },
  // // JavaScript + React
  // "[javascriptreact]": {
  //   "editor.defaultFormatter": "esbenp.prettier-vscode"
  // },
  // // TypeScript
  // // "[typescript]": {
  // //   "editor.defaultFormatter": "esbenp.prettier-vscode"
  // // },
  // // TypeScript + React
  // // "[typescriptreact]": {
  // //   "editor.defaultFormatter": "esbenp.prettier-vscode"
  // // },
  // // JSON with Comments
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  // // HTML
  // "[html]": {
  //   "editor.defaultFormatter": "esbenp.prettier-vscode"
  // },
  // ----------------------------------
  // ESLINT
  // "eslint.validate": [
  // 	"javascript",
  // 	"javascriptreact",
  // 	// "typescript",
  // 	// "typescriptreact",
  // 	"html"
  // ],
  // --------------------------------------
  // LANGUAGES SPECIFIC
  "javascript.updateImportsOnFileMove.enabled": "always",
  "security.workspace.trust.banner": "never",
  "emmet.includeLanguages": {
    // "typescript": "typescriptreact",
    "javascript": "javascriptreact",
    "razor": "html"
  },
  // MISCELLANEOUS
  "git.autofetch": true,
  "editor.inlineSuggest.enabled": true,
  "github.copilot.enable": {
    "*": true
  },
  // NATIVE BRACKET PAIR COLOR SETTINGS
  "editor.bracketPairColorization.enabled": true,
  "workbench.colorCustomizations": {
    "[Night Owl]": {
      "activityBar.background": "#000C1D",
      "activityBar.border": "#102a44",
      "sideBar.background": "#001122",
      "sideBar.border": "#102a44",
      "sideBar.foreground": "#8BADC1",
      "editorGroup.border": "#102a44",
      "terminal.ansiBlue": "#0034a4",
      // "terminal.ansiBrightBlack": "#ff0000"
      "terminal.ansiBlack": "#000000"
    }
  },
  "terminal.integrated.persistentSessionScrollback": 100000,
  "terminal.integrated.scrollback": 100000,
  "workbench.editorAssociations": {
    "*.png": "imagePreview.previewEditor"
  },
  //   "[shellscript]": {
  //     "editor.defaultFormatter": "foxundermoon.shell-format"
  //   },
  "terminal.integrated.shellIntegration.history": 200,
  // "[toml]": {
  //   "editor.defaultFormatter": "tamasfe.even-better-toml"
  // },
  // "typescript.validate.enable": false,
  "javascript.validate.enable": false,
  // "editor.defaultFormatter": "rvest.vs-code-prettier-eslint",
  // "editor.defaultFormatter": "esbenp.prettier-vscode",

  // "[html]": {
  // 	"editor.defaultFormatter": "vscode.html-language-features"
  // },
  "editor.formatOnPaste": false, // required
  "editor.formatOnType": false,
  "workbench.editor.decorations.colors": false,
  "explorer.decorations.colors": false, // required,
  // "terminal.external.osxExec": "iTerm.app",
  "workbench.editor.enablePreview": true,
  // "[json]": {
  // 	"editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  // },
  // "[javascript]": {
  // 	"editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  // },
  // "[vue]": {
  // 	"editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  // },
  "editor.accessibilitySupport": "off",
  "workbench.startupEditor": "none",
  "editor.wordWrapColumn": 200,
  "liveServer.settings.donotShowInfoMsg": true,
  // "[less]": {
  // 	"editor.defaultFormatter": "vscode.css-language-features"
  // },
  "git.openRepositoryInParentFolders": "never",
  "breadcrumbs.enabled": false,
  "github.copilot.advanced": {},
  "editor.minimap.enabled": false,
  "gitlens.rebaseEditor.ordering": "asc",
  "[javascript]": {
    "editor.defaultFormatter": "rvest.vs-code-prettier-eslint"
  }
}
// #011627 Background
// #d6deeb Foreground
// #01111d Current Line
// #1d3b53 Selection
// #80a4c2 Cursor
// #4b6479 Line Number
// #c5e4fd Current Line Numberz
// #7fdbca Tags/Keywords
// #637777 Comment
// #ef5350 Red
// #22da6e Green
// #addb67 Yellow
// #82aaff Blue
// #f78c6c Orange
// #c792ea Magenta
// #21c7a8 Cyan
// #ffffff White
// #575656 Bright Black
```
