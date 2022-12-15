[
  {
    "key": "capslock",
    "command": "extension.vim_escape",
    "when": "editorTextFocus && vim.active && !inDebugRepl"
  },
  {
    "key": "alt+j",
    "command": "cursorLeft",
    "when": "textInputFocus"
  },
  {
    "key": "alt+l",
    "command": "cursorRight",
    "when": "textInputFocus"
  },
  {
    "key": "alt+i",
    "command": "cursorUp",
    "when": "textInputFocus"
  },
  {
    "key": "alt+k",
    "command": "cursorDown",
    "when": "textInputFocus"
  },
  {
    "key": "ctrl+k",
    "command": "selectNextSuggestion",
    "when": "suggestWidgetMultipleSuggestions && suggestWidgetVisible && textInputFocus"
  },
  {
    "key": "ctrl+i",
    "command": "selectPrevSuggestion",
    "when": "suggestWidgetMultipleSuggestions && suggestWidgetVisible && textInputFocus"
  },
  {
    "key": "alt+i",
    "command": "workbench.action.quickOpenSelectNext",
    "when": "inQuickOpen"
  },
  {
    "key": "alt+k",
    "command": "workbench.action.quickOpenSelectPrevious",
    "when": "inQuickOpen"
  }
]
