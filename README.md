# config-vscode
O config-vscode refere-se à configuração personalizada do editor de texto e ambiente de desenvolvimento Visual Studio Code (VS Code). Essa configuração pode incluir ajustes de aparência, atalhos de teclado, extensões instaladas, definições de linguagem, integração com ferramentas externas e personalizações de desempenho.


1. Configurações do Usuário (settings.json)
Controle do tema (claro ou escuro) e do layout.
Ajustes de fontes, espaçamento, e tabulação.
Configurações específicas para linguagens (JavaScript, Python, etc.).
Habilitação/desabilitação de recursos como linting, autoformatação e snippets.



{
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    }, //Ajuda no auto complete no react.js
    "workbench.colorTheme": "Dracula Theme",
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "terminal.integrated.allowChords": false,
    "editor.minimap.enabled": false,
    "editor.renderWhitespace": "none",
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true,
    "liveServer.settings.donotShowInfoMsg": true,
    "workbench.startupEditor": "none",
    "terminal.integrated.enableMultiLinePasteWarning": false,
    "[yaml]": {
        "editor.tabSize": 4
    },
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": "explicit"
    },
    "[javascript]": {
        "editor.tabSize": 4,
        "editor.insertSpaces": true,
        "editor.detectIndentation": false
    },
    "vetur.format.options.tabSize": 4,
    "terminal.integrated.tabs.defaultIcon": "beaker",
    "editor.fastScrollSensitivity": 6,
    "emmet.triggerExpansionOnTab": true,
    "git.confirmSync": false,
    "workbench.editorAssociations": {
        "*.lnk": "default"
    },
    "javascript.updateImportsOnFileMove.enabled": "always",
    "git.openRepositoryInParentFolders": "always",
    "workbench.iconTheme": "vscode-icons",
    "git.suggestSmartCommit": false,
    "prettier.tabWidth": 4,
    "prettier.bracketSpacing": false,
    "prettier.printWidth": 180,
    "terminal.integrated.env.windows": {},
    "window.zoomLevel": 1,
    "console-ninja.featureSet": "Community",
    "files.associations": {
        "*.rs": "rust"
    },
    "chat.commandCenter.enabled": false
}
 
