# React + TypeScript + Vite + Panda

Template providing a minimal setup to get React working in Vite with HMR, Panda CSS, ESLint rules, and Prettier.

## Getting started

```shell
pnpm install

pnpm dev
```

## VSCode

See the list of recommended extensions `.vscode/extensions.json`.

Here is my vscode settings `.vscode/settings.json`.

```jsonc
{
  // autosave
  "files.autoSave": "onFocusChange",

  // linter
  "eslint.format.enable": true,
  "eslint.workingDirectories": [
    {
      "mode": "auto",
    },
  ],
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "always",
  },

  // formatter
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
}
```
