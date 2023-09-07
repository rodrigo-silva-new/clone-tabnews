- Instalar a extensão EditorConfig;
- Instalar prettier via npm e depois a extensão do vscode;
- Criar no package.json os scripts:
    "lint:check": "prettier --check .",
    "lint:fix": "prettier --write ."

- Settar no VSCode para que use o formatardor do Prettier ao salvar um arquivo;