# Steps to reproduce

1. `yarn init -2`
1. `yarn add -D eslint`
1. add extensions `vscode-eslint`
1. `yarn dlx @yarnpkg/sdks vscode`
1. set `"eslint.experimental.useFlatConfig": true` in `.vscode/settings.json`
1. create `eslint.config.js` file
1. create `test.js` file
1. `yarn dlx eslint .` observe errors
1. vscode-eslint only outputs

   ```
   [Info  - 20:04:53] ESLint server is starting.
   [Info  - 20:04:53] ESLint server running in node v18.15.0
   [Info  - 20:04:53] ESLint server is running.
   ```
