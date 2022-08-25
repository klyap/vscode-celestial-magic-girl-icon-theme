# VSCode Stardew Icon Theme

A celestial magic girl themed product icon pack!
Currently for common front-end web development file types

### Download and use at https://marketplace.visualstudio.com/items?itemName=klyap.vscode-celestial-magic-girl-icon-theme


## Development

This extension uses image files directly from the `icons` folder in `icons.json`.

Open this repo in VSCode and hit F5 to test it out.

You will need to run to develop:
```yarn install```
```yarn global add vsce``` or ```npm install -g vsce```

### To test changes
Hit F5 while you're inside this repo in VSCode

### To publish a new version to the VS Code Extension Marketplace
Update the version number in package.json and run:
```vsce publish```
And follow steps here: https://code.visualstudio.com/api/working-with-extensions/publishing-extension

If this command doesn't work, you can just package instead, and upload on the VSCode website https://marketplace.visualstudio.com/manage/publishers/<your publisher name here>

### To package for sharing with others
Run this command to generate a VSIX file:
 ```vsce package```
To load this VSIX extension into your VS Code IDE, replacing the file name with the generated one:
```code --install-extension vscode-celestial-magic-girl-icon-theme-0.0.3.vsix```


