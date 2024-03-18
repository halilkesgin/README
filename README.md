{
  "editor.fontFamily": "Martian Mono",
  "editor.fontWeight": "300",
  "editor.fontSize": 12,
  "editor.fontVariations": false,
  "editor.fontLigatures": false,
  "editor.lineNumbers": "on",
  "editor.glyphMargin": false,
  "editor.smoothScrolling": true,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.autoIndent": "full",
  "editor.cursorBlinking": "phase",
  "editor.cursorStyle": "line",
  "editor.formatOnPaste": true,
  "editor.formatOnType": false,
  "editor.formatOnSave": true,

  "editor.parameterHints.enabled": false,
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "editor.snippetSuggestions": "none",
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.inlineSuggest.enabled": false,
  // "editor.suggest.selectionMode": "never",
  // "editor.suggest.showClasses": false,
  // "editor.suggest.showColors": false,
  // "editor.suggest.showConstants": false,
  // "editor.suggest.showConstructors": false,
  // "editor.suggest.showCustomcolors": false,
  // "editor.suggest.showDeprecated": false,
  // "editor.suggest.showEnumMembers": false,
  // "editor.suggest.showEnums": false,
  // "editor.suggest.showEvents": false,
  // "editor.suggest.showFields": false,
  // "editor.suggest.showFiles": false,
  // "editor.suggest.showFolders": false,
  // "editor.suggest.showFunctions": false,
  // "editor.suggest.showIcons": false,
  // "editor.suggest.showInterfaces": false,
  // "editor.suggest.showIssues": false,
  // "editor.suggest.showKeywords": false,
  // "editor.suggest.showMethods": false,
  // "editor.suggest.showModules": false,
  // "editor.suggest.showOperators": false,
  // "editor.suggest.showProperties": false,
  // "editor.suggest.showReferences": false,
  // "editor.suggest.showSnippets": false,
  // "editor.suggest.showUnits": false,
  // "editor.suggest.showTypeParameters": false,
  // "editor.suggest.showStructs": false,
  // "editor.suggest.showUsers": false,
  // "editor.suggest.showValues": false,
  // "editor.suggest.showVariables": false,
  // "editor.suggest.showWords": false,
  // "editor.suggestOnTriggerCharacters": false,

  "editor.wordWrap": "on",
  "editor.minimap.enabled": false,

  "terminal.integrated.smoothScrolling": true,
  "terminal.integrated.fontFamily": "Martian Mono",
  "terminal.integrated.fontWeight": "300",

  "workbench.list.smoothScrolling": true,
  "workbench.activityBar.iconClickBehavior": "toggle",
  "workbench.layoutControl.enabled": false,
  "workbench.editor.editorActionsLocation": "hidden",
  "workbench.statusBar.visible": true,
  "workbench.activityBar.location": "top",

  "explorer.compactFolders": false,

  "git.autofetch": true,

  "html.suggest.html5": false,

  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "name": "Comment",
        "scope": ["comment", "punctuation.definition.comment"],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Keyword, Storage",
        "scope": ["Keyword", "Storage"],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Keyword Control if else",
        "scope": ["keyword.control"],
        "settings": {
          "fontStyle": ""
        }
      },
      {
        "scope": "entity.other.attribute-name",
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "entity.name.method.js",
        "scope": ["entity.name.method.js"],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Language methods",
        "scope": ["variable.language"],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "HTML Attributes",
        "scope": [
          "text.html.basic entity.other.attribute-name.html",
          "text.html.basic entity.other.attribute-name"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Decorators",
        "scope": [
          "tag.decorator.js entity.name.tag.js",
          "tag.decorator.js punctuation.definition.tag.js"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "ES7 Bind Operator",
        "scope": [
          "source.js constant.other.object.key.js string.unquoted.label.js"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Markup - Italic",
        "scope": ["markup.italic"],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Markup - Bold-Italic",
        "scope": [
          "markup.bold markup.italic",
          "markup.italic markup.bold",
          "markup.quote markup.bold",
          "markup.bold markup.italic string",
          "markup.italic markup.bold string",
          "markup.quote markup.bold string"
        ],
        "settings": {
          "fontStyle": "bold"
        }
      },
      {
        "name": "Markup - Quote",
        "scope": ["markup.quote"],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "scope": "variable.other",
        "settings": {
          "foreground": "#82fbff"
        }
      },
      {
        "scope": "entity.name.function",
        "settings": {
          "foreground": "#dfd9a8"
        }
      },
      {
        "scope": "support.function",
        "settings": {
          "fontStyle": "italic",
          "foreground": "#dfd9a8"
        }
      },
      {
        "scope": "string",
        "settings": {
          "foreground": "#CE9178"
        }
      },
      {
        "name": "Async Keyword",
        "scope": "keyword.control.async",
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Const Keyword",
        "scope": "storage.modifier",
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "name": "Export Keyword",
        "scope": "keyword.control.export",
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  },

  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.updateImportsOnFileMove.enabled": "always",

  "window.commandCenter": false,
  "window.menuBarVisibility": "toggle",
  "editor.inlayHints.enabled": "on",
  "breadcrumbs.enabled": true,
  "git.confirmSyanc": false,
  "git.openRepositoryInParentFolders": "never",
  "workbench.iconTheme": "vscode-jetbrains-icon-theme-2023-dark",
  "symbols.hidesExplorerArrows": false
}
