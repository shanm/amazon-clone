# VS Code Setup

Hey Hey! [VS Code](https://code.visualstudio.com/) is an amazing editor, we will be using it for this entire course.

Here you will find my VS Code settings, extensions, fonts, and favorite keyboad shortcuts.

All of this is meant to make us the most efficient and fast developers possible.

### Settings

- Auto format on save. Let prettier handle formatting for us.
- Cursor smooth caret animation on, A cool little effect
- Hide activity bar - ctl+shift+p - type activity
- Hide status bar - ctl_shift+p - type status
- Sometimes centered layout

### Extensions

- [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock): To change the color of our editor
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): To help find errors and fix them.
- [Javascript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets): Snippets to speed up writing code (clg for console.log is the best)
- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense): Easy way to import from ther files
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Auto format. Let the humans write code. Let the computer format.
- [Simple React Snippets](https://marketplace.visualstudio.com/items?itemName=burkeholland.simple-react-snippets): Small snippets for React (`imd` is a good one)
- [Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log): Make console. logging even faster
- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion): CSS class name completion for the HTML class attribute based on the definitions found in your workspace. 
- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
- [Yarn]
- [Deno]
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Bracket Pair Colorizer 2]
- [Composer]
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
- [Docker]
- [Emoji Snippets]
- [ES7 React/Redux/GraphQL/React-Native snippets]
- [ESLint]
- [GitLens — Git supercharged]
- [HTML CSS Support]
- [JavaScript (ES6) code snippets]
- [Live Sass Compiler]
- [Live Server]
- [Live Share]
- [Material Icon Theme]
- [Monokai Pro]
- [npm]
- [Path Intellisense]
- [Peacock]
- [PHP Debug]
- [PHP DocBlocker]
- [PHP Getters & Setters]
- [PHP Intelephense]
- [PHP Namespace Resolver]
- [Prettier - Code formatter]
- [Remote - Containers]
- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
- [Simple React Snippets]
- [TSLint]
- [Turbo Console Log]
- [Filesize]
- [Project Manager]
- [Code Spell Checker]
- [Remote - SSH]
- [codestream]


### My Custom Snippets for React Functional Components

Here's my custom snippet that I use. you'll see me type `rfc` to create a React Component.

1. Open command palette
2. Preference: Configure User Snippets
3. Add these two objects to the file

```json
"React Functional Component":{
    "scope":"javascript, typescript",
    "prefix":"rfc",
    "body": [
        "import React from 'react';\n",
        "export default function ${1:name}($
        {2:props}) {",
        "\t${3:your stuff}",
        "}"
    ]
},
"Export Default Function":{
    "scope":"javascript, typescript",
    "prefix":"exdf",
    "body": [
        "export default function ${1:name}(${2:props}
        ) {",
        "\t${3:your stuffs}",
        "}"
    ]
}

### Themes
- [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Monokai Pro](https://monokai.pro/vscode)(https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode)

### Fonts

- [Cascadia Code](https://github.com/microsoft/cascadia-code) (Free): My current daily font
- [Dank Mono](https://dank.sh) (Paid)
- [Operator Mono](https://www.typography.com/fonts/operator/styles) (Paid)
- [Fira Code](https://github.com/tonsky/FiraCode) (Free)
- [Inconsolata] (Free)

### Turn on Ligatures -->

Found in settings. Search for ligatures.


### Keyboard Shortcuts

- Show command palette: cmd shift p
- Show settings: cmd ,
- Show and hide sidebar: cmd b
- Show explorer: cmd shift e
- Show terminal: ctrl `
- Show find: ctl shift f
- Multiple cursors


### npm vs yarn
npm i = yarn 
npm start = yarn start