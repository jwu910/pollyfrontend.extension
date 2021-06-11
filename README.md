# Polly Frontend Development Extension Pack

This extension pack contains a set of extensions valuable to the frontend developer experience.

- [Polly Frontend Development Extension Pack](#polly-frontend-development-extension-pack)
  - [Contents](#contents)
  - [Additional Settings](#additional-settings)
    - [settings.json](#settingsjson)

## Contents

- [Better Comments](https://www.digitalocean.com/community/tutorials/how-to-create-an-extension-pack-for-visual-studio-code) Improve your code commenting by annotating with alert, informational, TODOs, and more!
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) EditorConfig Support for Visual Studio Code
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) Integrates ESLint JavaScript into VS Code.
- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) Vue tooling for VS Code
- [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets) Snippets that will supercharge your Vue workflow

## Additional Settings

### settings.json

Additional settings to help get ESLint and editor formatting enabled. Add following snippet to your settings.json in vscode

```json
{
  "eslint.workingDirectories": ["./frontend"],
  "eslint.debug": true,
  "eslint.format.enable": true,
  "eslint.lintTask.enable": true,
  "[vue]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  },
  "[javascript]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint"
  }
}
```
