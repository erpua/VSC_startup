# VSC_startup

// Additions

- Debugger for Chrome
- ESLint
- Highlight Matching Tag
- html tag wrapper
- HTMLHint
- Import Cost
- JavaScript (ES6) code snippets
- lit-html
- LitElement and Polymer v2/v3 Snippets
- LitElement Snippet
- Live Server
- Path Intellisense
- Prettier - Code formatter
- Template Literal Editor
- Terminal
- Trailing Spaces


// DOWNLOAD PRETTIER ADDS AND npm install --save-dev --save-exact prettier
// FOR THE PROJECT.    JSON: 

{
 "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "files.autoSave": "onWindowChange",
  "window.zoomLevel": 0,
  "emmet.triggerExpansionOnTab": true,
  "editor.renderWhitespace": "all",
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.formatOnPaste": true,
  "css.validate": false,
  "scss.validate": false,
  "editor.detectIndentation": false,
  "editor.folding": true,
  "editor.glyphMargin": false,
  "editor.smoothScrolling": true,
  "editor.minimap.enabled": false,
  "workbench.editor.tabSizing": "shrink",
  "editor.fontSize": 14,
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.wordWrap": "wordWrapColumn",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.wordWrapColumn": 80,
  "prettier.trailingComma": "all",
  "prettier.singleQuote": true,
}



// 2-nd OPTION INCLUDING PRETTIER EXTENSION AND .prettierrc file(!IN THE PROJECT !NOT GLOBALLY)

SETTINGS:
   search: Quote =>
      Editor: Auto Closing OverType: auto;
      Editor: Auto Closing Quotes: languageDefined
      JavaScript Preference: Quote Style: single;
      TypeScript Preference: Quote Style: single;
      Prettier: JSX Single Quote: checked to Use Single ...
      Prettier: Quote Props: consistent;
      Prettier: Single Quote: checked to If true ...

 EXTENSION settings:

{
  "files.autoSave": "onWindowChange",
  "window.zoomLevel": 0,
  "emmet.triggerExpansionOnTab": true,
  "editor.renderWhitespace": "all",
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.snippetSuggestions": "top",
  "editor.formatOnPaste": true,
  "css.validate": false,
  "scss.validate": false,
  "editor.detectIndentation": false,
  "editor.folding": true,
  "editor.glyphMargin": false,
  "editor.smoothScrolling": true,
  "editor.minimap.enabled": false,
  "workbench.editor.tabSizing": "shrink",
  "editor.fontSize": 14,
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.wordWrap": "wordWrapColumn",
  "editor.wordWrapColumn": 100,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "javascript.updateImportsOnFileMove.enabled": "always",
  "javascript.preferences.quoteStyle": "single",
  "typescript.preferences.quoteStyle": "single",
  "prettier.jsxSingleQuote": true,
  "prettier.quoteProps": "consistent",
  "prettier.singleQuote": true
}

/*  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  }, */


.prettierrc file settings:

{
  "printWidth": 80,
  "tabWidth": 2,
  "useTabs": false,
  "semi": true,
  "singleQuote": true,
  "trailingComma": "all",
  "bracketSpacing": true,
  "jsxBracketSameLine": false,
  "arrowParens": "avoid",
  "proseWrap": "always"
}
