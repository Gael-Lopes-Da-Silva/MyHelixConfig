<h3 align="center">
  Helix configuration
</h3>

---

<p align="center">
  :gear: This is my configuration for Helix. If you want to use it, just copy the settings in your `config.toml`. See <a href="https://docs.helix-editor.com/configuration.html">here</a> if you don't understand.</p>

---

### :spiral_notepad: Font
- [Cascadia Mono](https://github.com/microsoft/cascadia-code)

### :national_park: Theme
- [Yellowed](https://github.com/Gael-Lopes-Da-Silva/YellowedHelix)

### :gear: Settings
~~~toml
theme = "yellowed"

[editor]
scrolloff = 0
mouse = true
middle-click-paste = false
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
left = ["mode", "diagnostics"]
center = ["file-name", "file-modification-indicator"]
right = ["version-control", "total-line-numbers", "position", "position-percentage", "file-encoding", "file-line-ending", "file-type"]
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

[keys.normal]
esc = ["collapse_selection", "keep_primary_selection"]
~~~
