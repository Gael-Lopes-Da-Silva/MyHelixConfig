<h3 align="center">
  Helix configuration
</h3>

---

<p align="center">
  :gear: This is my configuration for Visual Studio Code. The key bindings can be difficult to understand. You can see with the keybindings.json and the keybinding extention.</p>

---

### Font
- [Cascadia Mono](https://github.com/microsoft/cascadia-code)

### Theme
- [Yellowed](https://github.com/Gael-Lopes-Da-Silva/YellowedHelix)

### Settings
~~~toml
theme = "yellowed"

[editor]
scrolloff = 0
mouse = true
middle-click-paste = false
shell = ["powershell", "-nologo"]
line-number = "relative"
cursorline = true
auto-completion = true
auto-format = true
auto-save = true
idle-timeout = 0
completion-trigger-len = 1
completion-replace = true
auto-info = true
true-color = true
undercurl = true
color-modes = true
text-width = 80

[editor.statusline]
left = ["mode", "spinner", "diagnostics", "version-control"]
center = ["file-name", "file-modification-indicator"]
right = ["total-line-numbers", "position", "position-percentage", "file-encoding", "file-line-ending", "file-type"]
mode.normal = "NORMAL"
mode.insert = "INSERT"
mode.select = "SELECT"

[editor.lsp]
enable = true
display-messages = true
auto-signature-help = true
display-inlay-hints = false
display-signature-help-docs = true
snippets = true
goto-reference-include-declaration = true

[editor.cursor-shape]
insert = "bar"
normal = "block"
select = "underline"

[editor.file-picker]
hidden = false

[editor.whitespace]
render = "none"

[editor.indent-guides]
render = true
character = "|"

[editor.soft-wrap]
enable = true
max-wrap = 20
max-indent-retain = 0
wrap-indicator = ""
~~~
