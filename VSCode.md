# Visual Studio Configuration Recommendation

> \* represents the configuration is just personal (for myself only)



## EXTENSIONS

- **Beautify**: Beautify code in place for VS Code
- **Better Cooments**: Improve your code commenting by annotating with alert, informational, TODOs, and more!
- **Document This**: Automatically generates detailed JSDoc comments in TypeScript and JavaScript files.
- **ESLint**: Integrates ESLint JavaScript into VS Code.
- **GitLens**: Supercharge the Git capabilities built into Visual Studio Code
- **open in browser**: This allows you to open the current file in your default browser or application.
- **Prettier**: VS Code plugin for prettier/prettier
- **TSLint(deprecated)**: TSLint for Visual Studio Code
- **LaTex Workshop**: Boost LaTeX typesetting efficiency with preview, compile, autocomplete, colorize, and more.



## User Settings*

```json
{
    "window.zoomLevel": 1,
    "workbench.colorTheme": "Quiet Light",
    "workbench.editor.enablePreview": false,
    "terminal.integrated.fontFamily": "Cousine for Powerline",
    "better-comments.tags": [{
        "tag": "!",
        "color": "#FF8C00",
        "strikethrough": false,
        "backgroundColor": "transparent"
    }, {
        "tag": "?",
        "color": "#FF2D00",
        "strikethrough": false,
        "backgroundColor": "transparent"
    }, {
        "tag": "//",
        "color": "#474747",
        "strikethrough": true,
        "backgroundColor": "transparent"
    }, {
        "tag": "todo",
        "color": "#3498DB",
        "strikethrough": false,
        "backgroundColor": "#fbbc05"
    }, {
        "tag": "*",
        "color": "#98C379",
        "strikethrough": false,
        "backgroundColor": "transparent"
    }],
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "prettier.tslintIntegration": true,
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.formatOnSave": true,
    "editor.fontFamily": "Consolas, 'Microsoft Yahei', 'Courier New', monospace",
    "terminal.integrated.shell.windows": "C:\\Windows\\System32\\wsl.exe",
    "latex-workshop.latex.tools": [{
        "name": "xelatex",
        "command": "xelatex",
        "args": [
            "-synctex=1",
            "-interaction=nonstopmode",
            "-file-line-error",
            "%DOC%"
        ]
    }, {
        "name": "pdflatex",
        "command": "pdflatex",
        "args": [
            "-synctex=1",
            "-interaction=nonstopmode",
            "-file-line-error",
            "%DOC%"
        ]
    }, {
        "name": "bibtex",
        "command": "bibtex",
        "args": [
            "%DOCFILE%"
        ]
    }],
    "latex-workshop.latex.recipes": [{
        "name": "pdflatex -> bibtex -> pdflatex*2",
        "tools": [
            "pdflatex",
            "bibtex",
            "pdflatex",
            "pdflatex"
        ]
    }, {
        "name": "PDFLaTeX",
        "tools": [
            "pdflatex"
        ]
    }, {
        "name": "XeLaTeX",
        "tools": [
            "xelatex"
        ]
    }, {
        "name": "latexmk",
        "tools": [
            "latexmk"
        ]
    }, {
        "name": "BibTeX",
        "tools": [
            "bibtex"
        ]
    }, {
        "name": "xelatex -> bibtex -> xelatex*2",
        "tools": [
            "xelatex",
            "bibtex",
            "xelatex",
            "xelatex"
        ]
    }],
    "latex-workshop.view.pdf.viewer": "tab",
}
```

