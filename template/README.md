# cra-template-typescript-standard-prettier

TypeScript template for [Create React App](https://github.com/facebook/create-react-app) with standardjs (eslint), prettier, editorconfig, axios, react-router-dom, react-icons and styled-components.

**IMPORTANT**

Due to an eslint config limitation **you have to install all dependencies** that this config uses manually with:

```sh
yarn setup

# or

npm run setup-npm
```

## Editor integration

### VSCode

I recommend the best editor for JavaScript/TypeScript to use with this template: [Visual Studio Code](https://code.visualstudio.com/) (VSCode).

And these extensions to best integration (Prettier extension it's not necessary!):
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

Change your `settings.json`:

```
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
```

That's it. Reload the window or restart your VSCode to load config.