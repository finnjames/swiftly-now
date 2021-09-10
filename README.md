# Swiftly, Now!

This is an extension that aims to make VSCode(ium) match the aesthetic of macOS. Defintiely a work in progress :)

Add the following to `settings.json`:

```json
// Swiftly, Now!
"editor.fontSize": 13,
"editor.fontFamily": "SF Mono, Menlo, Monaco, monospace",
"terminal.integrated.fontSize": 13,
"terminal.integrated.lineHeight": 1.2,
"customizeUI.stylesheet": {
    ".composite.title": "background: transparent !important",
    ".monaco-workbench .activitybar > .content": "justify-content: center !important",
    ".explorer-folders-view .monaco-list-row": "border-radius: 0.3rem !important; margin: 0 3% !important; width: 94% !important",
    ".monaco-list-row.selected": "outline: none !important",
    ".monaco-tl-indent": "visibility: hidden !important",
    ".pane-header": "background-color: rgba(128,128,128,0) !important"
},
"window.titleBarStyle": "native",
"customizeUI.titleBar": "inline",
"customizeUI.activityBar": "bottom",
"workbench.statusBar.visible": false,
"workbench.iconTheme": null,
"workbench.productIconTheme": "sf-symbol-icons",
"vscode_vibrancy.opacity": 0.5,
"editor.fontWeight": 500,
"extensions.ignoreRecommendations": true,
"terminal.integrated.gpuAcceleration": "off",
"workbench.colorTheme": "Swiftly, Now! Dark",
// "window.autoDetectColorScheme": false,
// "workbench.preferredDarkColorTheme": "MacOS Modern Dark - Big Sur Xcode",
// "workbench.preferredLightColorTheme": "MacOS Modern Light - Big Sur Xcode Default",
"vscode_vibrancy.theme": "Dark (Only Subbar)",
"vscode_vibrancy.type": "sidebar",
```