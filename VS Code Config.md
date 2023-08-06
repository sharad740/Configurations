# VS Code default quick setup settings
```
{
    // Security Config 
    "security.workspace.trust.banner": "always",
    "security.workspace.trust.enabled": true,
    "security.workspace.trust.untrustedFiles": "open",

    // Workbench Config
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "welcomePage",
    
    // Explorer Config
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    
    // Django Jinja Config
    "emmet.includeLanguages": {
        "django-html": "html",
        "jinja-html": "html"
    },
    "[django-html]": {
        "editor.defaultFormatter": "HookyQR.beautify",
        "editor.tabSize": 4,"editor.wordWrap": "on",
        "editor.quickSuggestions": {"comments": true,"other": true,"strings": true},
    },

    // Editor Style
    "editor.lineHeight": 1.6,
    "editor.fontSize": 18,
    "editor.fontFamily": "Consolas",
    "editor.cursorStyle": "line",
    "editor.stickyScroll.enabled": false,
    
    // Terminal Config
    "terminal.integrated.fontFamily": "Fira Code Light",
    "terminal.integrated.defaultProfile.windows": "Command Prompt",

    // Live Server Config 
    "liveServer.settings.donotShowInfoMsg": true,
}
```
