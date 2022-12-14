// Place your key bindings in this file to override the defaults
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
    "key": "left",
    "command": "-cursorLeft",
    "when": "textInputFocus"
  },
  {
    "key": "alt+l",
    "command": "cursorRight",
    "when": "textInputFocus"
  },
  {
    "key": "right",
    "command": "-cursorRight",
    "when": "textInputFocus"
  },
  {
    "key": "alt+i",
    "command": "cursorUp",
    "when": "textInputFocus"
  },
  {
    "key": "up",
    "command": "-cursorUp",
    "when": "textInputFocus"
  },
  {
    "key": "alt+k",
    "command": "cursorDown",
    "when": "textInputFocus"
  },
  {
    "key": "down",
    "command": "-cursorDown",
    "when": "textInputFocus"
  },
  {
    "key": "ctrl+k",
    "command": "selectNextSuggestion",
    "when": "suggestWidgetMultipleSuggestions && suggestWidgetVisible && textInputFocus"
  },
  {
    "key": "ctrl+down",
    "command": "-selectNextSuggestion",
    "when": "suggestWidgetMultipleSuggestions && suggestWidgetVisible && textInputFocus"
  },
  {
    "key": "ctrl+i",
    "command": "selectPrevSuggestion",
    "when": "suggestWidgetMultipleSuggestions && suggestWidgetVisible && textInputFocus"
  },
  {
    "key": "ctrl+up",
    "command": "-selectPrevSuggestion",
    "when": "suggestWidgetMultipleSuggestions && suggestWidgetVisible && textInputFocus"
  }
]
