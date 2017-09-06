# VS Code setup 
This is my configurations and extensions for VS Code, my new editor.

### Begin
##### Shortcuts
basic commands that I use

- `Cmd + P` to open any file
- `Cmd + Shift + P` to access the command palette
- `Cmd + Shift + ´` to access the terminal
- `Cmd + K + B` to open and close explorer
- `Cmd + ,` to open settings file

### Set your User Settings
Open the user settings file, `Cmd + ,`. Here, you'll find all of the settings that can be modified for VS Code. Once you find one that you want to modify, click next to it and it will be copied over into your own settings file. A few good custom settings to start with are font size and font family.

```json
{
    "editor.fontFamily": "Fira Code Medium",
    "editor.fontSize": 15,
    "editor.fontLigatures": true,
    "editor.lineHeight": 40,
    "workbench.colorTheme": "Magoon",
    "workbench.iconTheme": "vs-seti",
    "workbench.sideBar.location": "left",
    "window.menuBarVisibility": "toggle",
    "editor.minimap.enabled": false,
    "explorer.openEditors.visible": 0,
    "workbench.statusBar.visible": false,
    "vsicons.projectDetection.autoReload": true,
    "editor.renderIndentGuides": false,
    "vsicons.dontShowNewVersionMessage": true,
    "atomKeymap.promptV3Features": true
}
```
### Extensions
The list of extensions with links to the VSCode marketplace. To install press `Cmd + P` and paste the install command listed next to each extension.

#### Workspace enhancements
- [All Autocomplete](https://marketplace.visualstudio.com/items?itemName=Atishay-Jain.All-Autocomplete)

  `ext install All-Autocomplete`

  > Provides autocompletion in Visual Studio Code items based on all open editors.
  
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

  `ext install auto-close-tag`
  
  > Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.
  
- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)

  `ext install autoimport`

  > Automatically finds, parses and provides code actions and code completion for all available imports. Works with Typescript and TSX.

- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)

  `ext install beautify`

  > Beautify javascript, JSON, CSS, Sass, and HTML in Visual Studio Code.
  
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)

  `ext install code-settings-sync`

  > Previously known as Visual Studio Code Settings Sync.
  
- [PHP Intellisense - Crane](https://marketplace.visualstudio.com/items?itemName=HvyIndustries.crane)

  `ext install crane`

  > Crane is a productivity enhancement extension for Visual Studio Code that provides code-completion for PHP.

- [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

  `ext install html-snippets`

  > This extension adds rich language support for the HTML Markup to VS Code.

- [Laravel Blade Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel-blade)

  `ext install laravel-blade`

  > Laravel blade snippets and syntax highlight support for Visual Studio Code.
