{
  "editor.accessibilitySupport": "off",
  "editor.fontFamily": "Monaco, Consolas, 'Courier New', monospace",
  "editor.fontSize": 14,
  "editor.cursorStyle": "line-thin",
  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": "on",
  // "editor.tabSize": 2,
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "name": "One Dark italic",
        "scope": [
          "comment",
          "entity.other.attribute-name",
          "keyword",
          "markup.underline.link",
          "storage.modifier",
          "storage.type",
          "string.url",
          "variable.language.super",
          "variable.language.this"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "One Dark italic reset",
        "scope": [
          "keyword.operator",
          "keyword.other.type",
          "storage.modifier.import",
          "storage.modifier.package",
          "storage.type.built-in",
          "storage.type.function.arrow",
          "storage.type.generic",
          "storage.type.java",
          "storage.type.primitive"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  },
  "files.maxMemoryForLargeFilesMB": 999999999,
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },
  "files.autoSave": "afterDelay",
  "material-icon-theme.activeIconPack": "react",
  "window.confirmBeforeClose": "always",
  "symbols.hidesExplorerArrows": false,
  "explorer.compactFolders": false,
  "workbench.activityBar.location": "hidden",
  "workbench.statusBar.visible": true,
  "workbench.editor.enablePreview": true,
  "workbench.preferredHighContrastColorTheme": "Community Material Theme Darker",
  "workbench.iconTheme": "catppuccin-perfect-dark",
  "workbench.layoutControl.enabled": false,
  "workbench.preferredDarkColorTheme": "Aura Dark (Soft Text)",
  "workbench.colorTheme": "Moonlight II",
  // ----PHP----------------------------------------------------------------------------------------------------
  "php.suggest.basic": false,
  "[php]": {
    "editor.defaultFormatter": "Sophisticode.php-formatter",
    "editor.wordSeparators": "`~!@#%^&*()-=+[{]}\\|;:'\",.<>/?",
  },
  // ----PHP----------------------------------------------------------------------------------------------------
  "animations.Install-Method": "Apc Customize UI++",
  "apc.imports": [
    "file://${userHome}/.vscode/extensions/brandonkirbyson.vscode-animations-2.0.3/dist/updateHandler.js"
  ],
  "apc.theme": [

  ],
  "apc.electron": {
    "titleBarStyle": "customButtonsOnHover",
  },
  "window.titleBarStyle": "native",
  "apc.parts.font.family": {
    "sidebar": "Monaco",
    "titlebar": "Monaco",
    "activityBar": "Monaco",
    "panel": "Monaco",
    "tabs": "Monaco",
    "statusbar": "Monaco",
    "settings-body": "Monaco",
    "extension-editor": "Monaco", // Install the font and restart vscode
    "monaco-menu": "Monaco"
  },
  "apc.header": {
    "default": 25, // Applied with "window.density.editorTabHeight": "default"
    "compact": 20, // Applied wtih "window.density.editorTabHeight": "compact"
    "height": 10, // Applied when neither "default" nor "compact" is specified
    "fontSize": 14,
  },
  "apc.statusBar": {
    "position": "bottom",
    "height": 35,
    "fontSize": 14
  },
  "apc.sidebar.titlebar": {
    "height": 36,
    "fontSize": 12
  },
  "apc.listRow": {
    "lists": [
      "explorer-folders-view",
      "results",
      "quick-input-list",
    ],
    "fontSize": 16,
    "height": 26,
  },
  "terminal.integrated.fontSize": 14,
  "apc.stylesheet": {
    ".mtk9": "color: #7AF8CA !important",
    // ".mtk5": "color: #D1D5DA !important",
    // ".mtk7": "color: #70B0FF !important",
    // ".mtk4": "color: #BAACFF !important",
    // "div.view-line span>span.mtk6": "color: #D1D5DA !important",
    ".sidebar .title-label": "padding: 100px !important",
    // ".monaco-icon-label>.monaco-icon-label-container>.monaco-icon-name-container>.label-name": "text-shadow: 0px 2px 4px rgba(0,0,0,.15)",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.sizing-shrink>.tab-label>.monaco-icon-label-container:after": "display: none",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title>.tabs-and-actions-container": "--tabs-border-bottom-color: var(--al-pane-split-color) !important",
    // ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container": "--editor-group-tab-height: calc(var(--al-tab-height) - (var(--al-tab-y-offset) * 2)); padding: var(--al-tab-y-offset) 0px var(--al-tab-y-offset) 5px; gap: 8px;",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container": "height: 40px; padding: var(--al-tab-y-offset) 0px var(--al-tab-y-offset) 5px; gap: 8px;",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab": "border-radius: 2px; overflow: hidden; border-right: none !important; --tab-border-bottom-color: transparent !important; margin-left: 9px",
    // пунктирная линия вокруг активного таба
    // ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active": "outline: 2px dashed var(--vscode-tab-activeBackground) !important; outline-offset: 2px !important; outline-color: #0085d9 !important;",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active": "outline: 2px dashed var(--vscode-tab-activeBackground) !important; outline-offset: 2px !important; outline-color: grey !important;",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.active .monaco-icon-name-container": "color: var(--vscode-tab-activeForeground) !important",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab>.tab-border-top-container": "display: none !important",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab .tab-label a, .monaco-workbench .part.editor>.content .editor-group-container>.title .title-label a": "font-size: 14px",
    ".monaco-workbench .part.editor>.content .editor-group-container>.title .tabs-container>.tab.sizing-fit": "margin-top: 10px !important;",
    // fix(tabs) remove traffic offset when no sidebar
    ".monaco-workbench:not(.nopanel), .monaco-workbench.fullscreen": "--traffic-X: 0 !important;",
    // TERMINAL
    ".panel:has(.terminal-outer-container) .composite.title": "visibility: hidden",
    ".panel .composite.title": "padding-left: 3.5rem",
    ".fullscreen .panel .composite.title": "padding-left: 0",
    ".fullscreen .panel:has(.terminal-outer-container) .composite.title": "display: none;",
    ".fullscreen.monaco-workbench .xterm": "padding-top: 1rem !important; padding-left: 1rem !important",
    // style(sidebar): hide explorer actions
    // ".monaco-workbench .part>.composite.title>.title-actions": "display: none !important",
    // "body .monaco-workbench": "--vscode-tab-inactiveBackground: rgba(255, 255, 255, 0.05); --vscode-tab-activeBackground: var(--vscode-tab-activeBorderTop, rgba(255, 255, 255, 0.12)); --vscode-editor-background-proxy:  color-mix(in srgb, var(--vscode-editor-background) calc(100% - var(--al-transparency-percent)), transparent) !important; --titlebar-height: var(--al-tab-height)",
    "body .monaco-workbench": "--vscode-tab-inactiveBackground: rgba(255, 255, 255, 0.05); --vscode-tab-activeBackground: #0085d9; --vscode-editor-background-proxy:  color-mix(in srgb, var(--vscode-editor-background) calc(100% - var(--al-transparency-percent)), transparent) !important;",    // style(editor): hide title actions
    // fix(search): file icon positions  
    ".filematch .monaco-icon-label:before, .custom-list-row.results .monaco-list-row .monaco-icon-label:before": "background-position: 0 bottom !important",
    // fix(search) file badge inset text position
    ".filematch .monaco-count-badge": "padding: 5px 6px 0 6px !important",
  },
  "window.commandCenter": false
}
