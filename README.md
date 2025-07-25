# Configurações do VS Code

Este repositório (ou arquivo) serve para documentar minhas preferências de personalização e usabilidade no Visual Studio Code.

## Configurações

```jsonc
{
    /* Icon e Color Theme 
    * --> Icons : Material Icon Theme, VsCode Great Icons
    * --> Color Theme : Dark Github Theme, GruvBox Theme */    
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "GitHub Dark",
    "material-icon-theme.hidesExplorerArrows": true,
    
    /* Configs - Visual */
    "window.menuBarVisibility": "compact",
    "workbench.sideBar.location": "right",
    "workbench.editor.labelFormat": "default",
    "workbench.tree.renderIndentGuides": "none",
    "workbench.activityBar.location": "top",
    "workbench.statusBar.visible": true, // false
    "workbench.editor.showTabs": "multiple", 
    "workbench.layoutControl.enabled": false,
    "workbench.startupEditor": "none",
    "workbench.tips.enabled": false,
    
    /* Configs - Editor */
    "editor.minimap.enabled": false,
    "editor.fontSize": 16,
    "editor.lineHeight": 1.25,
    "editor.fontFamily": "Fira Code Regular", // Fira Code Regular/JetBrainsMono Nerds Fonts
    "editor.fontLigatures": false, /* true : === -> => >= <= == */
    "editor.guides.indentation": true, // false
    "editor.renderWhitespace": "none",
    "editor.hideCursorInOverviewRuler": true,
    "editor.scrollbar.horizontalScrollbarSize": 10,
    "editor.scrollbar.verticalScrollbarSize": 10,
    "editor.renderLineHighlight": "gutter",
    // "editor.semanticHighlighting.enabled": "configuredByTheme", --> false
    /* Animação do Cursor */
    "editor.cursorBlinking": "smooth",
    "editor.cursorSmoothCaretAnimation": "on",

    /* Configs - Gerais */
    "breadcrumbs.enabled": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.confirmDelete": false,
    "explorer.compactFolders": false,
    "files.insertFinalNewline": true, // false
    "extensions.ignoreRecommendations": true,        
    "terminal.integrated.fontFamily": "Fira Code Regular", // Fira Code Regular/JetBrainsMono Nerds Fonts
    "terminal.integrated.fontSize": 14,
    "terminal.integrated.lineHeight": 1,

}
```

---

## Tema , Ícones , Extensões e Fontes

### Temas e Ícones
- [ ] `GitHub Dark` ou `GruvBox Theme`
- [ ] `Material Icon Theme` ou `vscode-great-icons`
  
### Extensões
- [ ] Better Comments
- [ ] Error Lens
- [ ] Code Runner
- [ ] GitHub Theme / Gruvbox Theme
- [ ] Material Icon Theme / VSCode Great Icons
- [ ] Git History / GitLens / Git Graph

### Fontes
- [ ] `Fira Code Regular` ou `JetBrainsMono Nerd Font`

---

## Observações
- Testar performance com `editor.semanticHighlighting.enabled: false`.
- Avaliar o uso de `editor.fontLigatures: true` para programação funcional.

---
