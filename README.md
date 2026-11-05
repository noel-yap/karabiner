# karabiner config

## About

Rules are kept as importable files in `assets/complex_modifications/`, grouped by what they do
(`word.json`, `window.json`, ...). Files for one specific app are prefixed `apps∕` (U+2215 DIVISION SLASH, which looks like `/`; Karabiner only lists files at the top level, so a real subfolder would hide them).
The rules that actually run are in `karabiner.json`; the assets files are source copies to import from.

### Keyboard 4000

* <kbd>application</kbd> ↦ <kbd>f15</kbd>
* <kbd>left_command</kbd> ↦ <kbd>left_control</kbd>
* <kbd>left_control</kbd> ↦ <kbd>left_command</kbd>
* <kbd>right_control</kbd> ↦ <kbd>right_command</kbd>
* <kbd>keypad_enter</kbd> ↦ <kbd>return_or_enter</kbd>

### `application.json`

* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>⇞</kbd> moves to previous app
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>⇟</kbd> moves to next app

### `desktop.json`

> Below assumes a 3×3 desktop grid when using an external keyboard or a single row of desktops when using the internal keyboard

* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>←</kbd> moves to left desktop with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>←</kbd> moves window to left desktop with wraparound
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>↑</kbd> moves to above desktop with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>↑</kbd> moves window to above desktop with wraparound
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>→</kbd> moves to right desktop with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>→</kbd> moves window to right desktop with wraparound
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>↓</kbd> moves to below desktop with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>↓</kbd> moves window to below desktop with wraparound
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>1</kbd>–<kbd>9</kbd> or <kbd>KP1</kbd>–<kbd>KP9</kbd> moves to that desktop; with <kbd>⇧</kbd>
  moves the window there (keypad layout mirrors the 3×3 grid, so <kbd>KP7</kbd> is desktop 1)
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>KP0</kbd> moves to the full-screened window

### `document.json`

* <kbd>⌘</kbd><kbd>⇱</kbd> moves to document start
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⇱</kbd> selects to document start
* <kbd>⌘</kbd><kbd>⇲</kbd> moves to document end
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⇲</kbd> selects to document end

### `edit.json`

* <kbd>button1</kbd> copies
* <kbd>button3</kbd> pastes
* <kbd>shift+button3</kbd> opens pasteboard

### `exit.json`

* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>⎀</kbd> locks screen
* <kbd>⇧</kbd><kbd>⎇</kbd><kbd>⎀</kbd> logs out
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>⌦</kbd> shuts down

### `keyboard-symbols.json`

* <kbd>⇧</kbd><kbd>F20</kbd> types ⇧
* <kbd>⌘</kbd><kbd>F20</kbd> types ⌘
* <kbd>⌃</kbd><kbd>F20</kbd> types ⌃
* <kbd>⎇</kbd><kbd>F20</kbd> types ⌥

### `line.json`

* <kbd>⇱</kbd> moves to line start
* <kbd>⇧</kbd><kbd>⇱</kbd> selects to line start
* <kbd>⇲</kbd> moves to line end
* <kbd>⇧</kbd><kbd>⇲</kbd> selects to line end
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⌫</kbd> deletes to line start
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⌦</kbd> deletes to line end

### `pane.json`

* <kbd>⎇</kbd><kbd>←</kbd> moves to previous pane or leftward pane
* <kbd>⎇</kbd><kbd>↑</kbd> moves to previous pane or upward pane
* <kbd>⎇</kbd><kbd>→</kbd> moves to next pane or rightward pane
* <kbd>⇧</kbd><kbd>⎇</kbd><kbd>→</kbd> splits pane rightward
* <kbd>⎇</kbd><kbd>↓</kbd> moves to next pane or downward pane
* <kbd>⇧</kbd><kbd>⎇</kbd><kbd>↓</kbd> splits pane downward

### `paragraph.json`

* <kbd>⌘</kbd><kbd>↑</kbd> moves to paragraph start
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>↑</kbd> selects to paragraph start
* <kbd>⌘</kbd><kbd>↓</kbd> moves to paragraph end
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>↓</kbd> selects to paragraph end

### `tile.json`

* <kbd>⌃</kbd><kbd>⎇</kbd><kbd>↑</kbd> tiles to top
* <kbd>⌃</kbd><kbd>⎇</kbd><kbd>→</kbd> tiles to right
* <kbd>⌃</kbd><kbd>⎇</kbd><kbd>↓</kbd> tiles to bottom
* <kbd>⌃</kbd><kbd>⎇</kbd><kbd>←</kbd> tiles to left

### `window.json`

* <kbd>⌃</kbd><kbd>⇞</kbd> moves to previous window
* <kbd>⌃</kbd><kbd>⇟</kbd> moves to next window

### `word.json`

* <kbd>⌘</kbd><kbd>←</kbd> moves to word start
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>←</kbd> selects to word start
* <kbd>⌘</kbd><kbd>→</kbd> moves to word end
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>→</kbd> selects to word end
* <kbd>⌘</kbd><kbd>⌫</kbd> deletes to word start
* <kbd>⌘</kbd><kbd>⌦</kbd> deletes to word end

## Per-app mappings (`apps∕*.json`)

### `apps∕browser.json`

* <kbd>⌘</kbd><kbd>⇞</kbd> or <kbd>🌐</kbd><kbd>⌘</kbd><kbd>↑</kbd> moves to previous tab
* <kbd>⌘</kbd><kbd>⇟</kbd> or <kbd>🌐</kbd><kbd>⌘</kbd><kbd>↓</kbd> moves to next tab
* <kbd>⌘</kbd><kbd>⌫</kbd> deletes to word start
* <kbd>⌘</kbd><kbd>⌦</kbd> deletes to word end

### `apps∕finder.json`

* <kbd>⌦</kbd> deletes the selected file in Finder (sends <kbd>⌘</kbd><kbd>⎇</kbd><kbd>⌫</kbd>)

### `apps∕idea.json`

* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>KP0</kbd> toggles fullscreen in IntelliJ IDEA

### `apps∕linear.json`

* <kbd>⌘</kbd><kbd>PgUp</kbd> moves to previous tab in Linear (<kbd>⇧</kbd><kbd>⌘</kbd><kbd>[</kbd>)
* <kbd>⌘</kbd><kbd>PgDn</kbd> moves to next tab in Linear (<kbd>⇧</kbd><kbd>⌘</kbd><kbd>]</kbd>)

### `apps∕zoom.json`

* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>KP0</kbd> toggles fullscreen in Zoom

## Install

1. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
2. `cd ~/.config && git clone git@github.com:noel-yap/karabiner.git`

## Helpful links

* [complex_modifications manipulator definition](https://karabiner-elements.pqrs.org/docs/json/complex-modifications-manipulator-definition/)
