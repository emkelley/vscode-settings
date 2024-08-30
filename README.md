# VS Code Settings

# Font

* [Geist Mono](https://vercel.com/font)

## Themes/Color

* [Midnight Synth](https://marketplace.visualstudio.com/items?itemName=ekelley.midnight-synth)
    * My own theme I've been using since 2021.
* [Bearded Icons](https://marketplace.visualstudio.com/items?itemName=BeardedBear.beardedicons)
    * The icons with a long beard.

## Extensions

* Theme / Editor Experience
  * [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
    * See all of your TODO comments in one place.
  * [Better Coomments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
    * More human-friendly comments with automatic coloring based on type of comment.
  * [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
    * In-line color highlighting preview for hex, hls, etc.
  * [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    * Integrates ESLint JavaScript into VS Code.
  * [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * Automatically format javascript, JSON, CSS, Sass
  * [PostCSS Language Support](https://marketplace.visualstudio.com/items?itemName=csstools.postcss)
    * Does what it says on the tin.
  * [Pretty TypeScript Errors](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors)
    * Makes TS errors more human readable.
* Useful Tools
  * [Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
    * Automating the process of writing meaningful log messages..
  * [Rainbow CSV](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv)
    * Highlight CSV and TSV files, Run SQL-like queries.
  * [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
    * Display inline in the editor the size of the imported package.
  * [Postman](https://marketplace.visualstudio.com/items?itemName=Postman.postman-for-vscode)
    * Make HTTP requests from inside VS Code using your Postman account.
  * [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)
    * GitHub Copilot is an AI pair programmer tool that helps you write code faster and smarter.
* Languages and Libraries
  * [Vue - Official (formerly Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
    * Language Support for Vue.
  * [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)
    * Snippets that will supercharge your Vue workflow.
  * [ESO Snippets](https://marketplace.visualstudio.com/items?itemName=Origami.vsc-eso)
    * Lua snippets for Elder Scrolls Online Addon development.
  * [godot-tools](https://marketplace.visualstudio.com/items?itemName=geequlim.godot-tools)
    * Game development tools for working with Godot Engine in VSCode.
* Fun
  * [Power Mode](https://marketplace.visualstudio.com/items?itemName=Origami.vsc-eso)
    *  VSCODE POWER MODE!!! (now with atom-like explosions and an improved combo meter!)

# Settings.json

```json
{
  "editor.bracketPairColorization.enabled": true,
  "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
  "css.lint.unknownAtRules": "ignore",
  "editor.accessibilitySupport": "off",
  "editor.cursorBlinking": "expand",
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.fontFamily": "Geist Mono",
  "editor.fontLigatures": true,
  "editor.fontSize": 16,
  "editor.fontWeight": "400",
  "editor.formatOnSave": true,
  "editor.glyphMargin": true,
  "editor.inlineSuggest.enabled": true,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 1.3,
  "editor.linkedEditing": true,
  "editor.minimap.maxColumn": 150,
  "editor.minimap.renderCharacters": false,
  "editor.renderWhitespace": "all",
  "editor.rulers": [],
  "editor.semanticHighlighting.enabled": false,
  "editor.snippetSuggestions": "top",
  "editor.suggest.preview": true,
  "editor.suggestSelection": "first",
  "editor.tabSize": 2,
  "editor.unicodeHighlight.allowedLocales": {
    "es": true
  },
  "editor.wordWrap": "bounded",
  "editor.wordWrapColumn": 250,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "plaintext": "jade",
    "razor": "html",
    "vue-html": "html"
  },
  "emmet.triggerExpansionOnTab": true,
  "eslint.run": "onType",
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "files.trimFinalNewlines": true,
  "files.trimTrailingWhitespace": true,
  "git.autofetch": false,
  "git.confirmEmptyCommits": false,
  "git.confirmForcePush": false,
  "git.enabled": false,
  "github.copilot.enable": {
    "*": true,
    "markdown": true,
    "plaintext": true,
    "yaml": false
  },
  "html.format.wrapLineLength": 0,
  "javascript.format.semicolons": "remove",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "less.lint.unknownAtRules": "ignore",
  "scss.lint.unknownAtRules": "ignore",
  "security.workspace.trust.untrustedFiles": "open",
  "tailwindCSS.emmetCompletions": true,
  "tailwindCSS.includeLanguages": {
    "vue": "html",
    "javascript": "javascript",
    "css": "css"
  },
  "editor.quickSuggestions": {
    "strings": true
  },
  "terminal.external.windowsExec": "C:\\Users\\Eric\\AppData\\Local\\Microsoft\\WindowsApps\\wt.exe",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.defaultLocation": "editor",
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.env.windows": {},
  "terminal.integrated.fontFamily": "FiraCode Nerd Font",
  "terminal.integrated.fontSize": 15,
  "terminal.integrated.gpuAcceleration": "on",
  "terminal.integrated.macOptionIsMeta": true,
  "terminal.integrated.scrollback": 10000,
  "terminal.integrated.tabs.enabled": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "window.commandCenter": true,
  "workbench.colorCustomizations": {
    "[Midnight Synth]": {
      "editorSuggestWidget.highlightForeground": "#eeff005e",
      "editorSuggestWidget.selectedBackground": "#ff00005e"
    }
  },
  "workbench.colorTheme": "Midnight Synth",
  "workbench.editor.enablePreview": true,
  "workbench.editorAssociations": {
    "*.html": "default"
  },
  "workbench.iconTheme": "bearded-icons",
  "workbench.layoutControl.enabled": false,
  "workbench.startupEditor": "none",
  "workbench.statusBar.visible": true,
  "workbench.tree.indent": 20,
  "terminal.external.linuxExec": "/bin/zsh",
  "terminal.explorerKind": "external",
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "icon": "terminal-bash"
    },
    "zsh": {
      "path": "zsh"
    }
  },
  "workbench.editor.empty.hint": "hidden",
  "prettier.printWidth": 100,
  "vue3snippets.printWidth": 100,
  "editor.minimap.showSlider": "always",
  "editor.stickyScroll.enabled": true,
  "godotTools.editorPath.godot4": "D:\\SteamLibrary\\steamapps\\common\\Godot Engine\\godot.windows.opt.tools.64.exe",
  "godotTools.lsp.serverPort": 6005,
  "editor.minimap.enabled": false,
  "security.allowedUNCHosts": ["Obelisk"],
  "github.copilot.editor.enableAutoCompletions": true,
  "window.confirmSaveUntitledWorkspace": false,
  "Lua.workspace.library": ["E:\\development\\_ESOUI"],
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "yzhang.markdown-all-in-one"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[vue]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
}

```
