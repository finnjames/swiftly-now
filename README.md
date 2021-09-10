# Swiftly, Now!

This is an extension that aims to make VSCode(ium) match the aesthetic of macOS. Defintiely a work in progress :)

Add the following to `settings.json`:

```json
"customizeUI.stylesheet": {
  ".composite.title": "background: transparent !important",
  ".monaco-workbench .activitybar > .content": "justify-content: center !important",
  ".explorer-folders-view .monaco-list-row": "border-radius: 0.3rem !important; margin: 0 3% !important; width: 94% !important",
  ".monaco-list-row.selected": "outline: none !important",
  ".monaco-tl-indent": "visibility: hidden !important",
  ".pane-header": "background-color: rgba(128,128,128,0) !important"
},
```