# Biome bug minimal reproduction repository

## Steps to reproduce

- open workspace in VS Code
- open `index.ts`
- notice that biome extension doesn't highlight it as a problem
- hit CTRL+S to save the file
- notice that biome extension auto-fixed it nevertheless

## Expected behavior

1. don't autofix linter rules when linter is disabled.
2. don't autofix what is not highlighted as a problem.


***

See https://github.com/biomejs/biome-vscode/issues/491