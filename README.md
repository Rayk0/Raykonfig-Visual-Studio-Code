# Raykonfig-Visual-Studio-Code
Here you can find everything that i use for Visual Studio Code, from extensions, to theme and font. But also what settings i like to enable.

## Theme
First of all, for my main VS Code Theme, I like to use [1mm Dracula Theme](https://marketplace.visualstudio.com/items?itemName=joytrekker.1mm-themes). It has some fresh color vibes and great syntax highlighting.

![VSCode Theme example](https://github.com/Rayk0/Raykonfig-Visual-Studio-Code/blob/master/images/Code%20Screenshot.png)

## Font
The font I use often is called [JetBrains Mono](https://www.jetbrains.com/lp/mono/). It's a free font, so feel free to try it out. It also support font ligatures.

*Note : You can see an example of the font on the screenshot above.*

## Icons
When I'm using the 1mm Dracula Theme, I like to use [VSCode Great Icons](https://marketplace.visualstudio.com/items?itemName=emmanuelbeziat.vscode-great-icons). It offers great visible icons, and add a nice effect when a folder is opened or not. You can also find an example on the screenshot above.

Somehow, I also like to use [Helium icons](https://marketplace.visualstudio.com/items?itemName=helgardrichard.helium-icon-theme) which offer more colorful icons.

## Settings
Here is the JSON Version of my settings, if you ever feel to copy them. You can also find them in the repository.

```
{
    "editor.matchBrackets": false,
    "editor.cursorSmoothCaretAnimation": true,
    "editor.smoothScrolling": true,
    "workbench.colorCustomizations": {
        "editorError.foreground": "#ffcb6b", // squiggly line
    },
    "workbench.startupEditor": "newUntitledFile",
    "[c]": {
        "editor.defaultFormatter": "ms-vscode.cpptools"
    },
    "explorer.compactFolders": false,
    "window.zoomLevel": 0,
    "terminal.integrated.fontFamily": "Roboto Mono for Powerline",
    "[cpp]": {
        "editor.defaultFormatter": "ms-vscode.cpptools"
    },
    "workbench.sideBar.location": "left",
    "workbench.editor.tabCloseButton": "left",
    "breadcrumbs.enabled": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "workbench.activityBar.visible": true,
    "vscode_custom_css.policy": true,
    "vscode_custom_css.imports": [
        ""
    ],
    "workbench.colorTheme": "1mm - Dracula",
    "editor.fontFamily": "JetBrains Mono",
    "editor.fontSize": 13,
    "editor.lineHeight": 16,
    "editor.fontLigatures": false,
    "editor.cursorStyle": "block",
    "workbench.iconTheme": "vscode-great-icons",
}
```
My favorite setting in Visual Studio Code is the cursor smooth caret animation. It feels really cool to code with it. I also enabled a few settings and disabled somes that for my personal usage were annoying. I'm actually looking for a vscode extension that could help me change the position of the tabs, so that they're not at the top anymore.

## Extensions
Visual Studio Code offers a large variety of extensions, and here are the ones I use :
- [Jumpy](https://marketplace.visualstudio.com/items?itemName=wmaurer.vscode-jumpy) | Allows you to jump to some words in your code easily.
- [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar) | Adds a shortcut for your left bar in the activity bar.
- [Better C++ Syntax](https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax) | Gives a better look to your theme when using C++.

- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare) | Allows you to create sessions and code with someone else on the same PC. This is really useful when working with someone else on the same file.

All of the other extensions that I have are related to themes or programming languages.
