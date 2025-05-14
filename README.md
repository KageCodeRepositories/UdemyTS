# TypeScript for Beginners

## Install Software

Here you can find all the important information that will be covered in the following.
NodeJs: https://nodejs.org/en
VSCode Typescript guide: https://code.visualstudio.com/docs/typescript/typescript-compiling

Github Repository: https://github.com/franneck94/UdemyTS
Useful Shortcuts in VSCode: https://github.com/franneck94/VSCodeGuide/blob/master/usefulShortcuts.md

- npm
- npm install -g typescript
- npm install -g lite-server
- npm install -g ts-node

## Video Setup

- script.ts
- package.json
- tsconfig.json

```bash
npm init
npm install
tsc -init
```
```bash
{
    // Editor settings
    "editor.tabSize": 4,
    "editor.rulers": [80, 120],
    "editor.renderWhitespace": "trailing",
    "editor.suggestSelection": "first",
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "terminal.integrated.defaultProfile.windows": "Command Prompt",
    // Debug
    "debug.onTaskErrors": "debugAnyway",
    "debug.javascript.suggestPrettyPrinting": false,
    // Explorer settings
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "explorer.copyRelativePathSeparator": "/",
    // Files settings
    "files.autoSave": "onFocusChange",
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.trimTrailingWhitespace": true,
    // Workbench settings
    "workbench.startupEditor": "newUntitledFile",
    "workbench.editor.untitled.hint": "hidden",
    // Git settings
    "git.enableSmartCommit": true,
    "git.autofetch": true,
    "git.confirmSync": false,
    // Typescript/Javascript settings
    "typescript.updateImportsOnFileMove.enabled": "always",
    "typescript.suggest.completeJSDocs": true,
    "importSorter.importStringConfiguration.maximumNumberOfImportExpressionsPerLine.count": 80,
    "importSorter.importStringConfiguration.maximumNumberOfImportExpressionsPerLine.type": "newLineEachExpressionAfterCountLimitExceptIfOnlyOne",
    "importSorter.importStringConfiguration.tabType": "tab",
    "importSorter.importStringConfiguration.trailingComma": "multiLine",
    "importSorter.generalConfiguration.sortOnBeforeSave": true,
    // Prettier
    "prettier.tabWidth": 4,
    "prettier.singleQuote": true,
    "prettier.jsxSingleQuote": true,
    "prettier.trailingComma": "all",
    "prettier.useEditorConfig": true,
    "prettier.bracketSpacing": false,
    // Different languages
    "[yaml]": {
        "editor.formatOnSave": false,
        "editor.defaultFormatter": "redhat.vscode-yaml"
    },
    "[json]": {
        "editor.formatOnSave": false
    },
    "[jsonc]": {
        "editor.formatOnSave": false
    },
    "[markdown]": {
        "files.trimTrailingWhitespace": false,
        "editor.formatOnSave": false,
        "editor.defaultFormatter": "yzhang.markdown-all-in-one",
        "editor.wordWrap": "wordWrapColumn",
        "editor.wordWrapColumn": 80
    }
}
```
