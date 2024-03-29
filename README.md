# karabiner config

## About

### Keyboard 4000

* <kbd>application</kbd> ↦ <kbd>f15</kbd>
* <kbd>left_command</kbd> ↦ <kbd>left_control</kbd>
* <kbd>left_control</kbd> ↦ <kbd>left_command</kbd>
* <kbd>right_control</kbd> ↦ <kbd>right_command</kbd>
* <kbd>keypad_enter</kbd> ↦ <kbd>return_or_enter</kbd>

### `application.json`

* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>⇞</kbd> moves to previous app
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>⇟</kbd> moves to next app

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

### `space.json`

* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>←</kbd> moves to left space with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>←</kbd> moves window to left space with wraparound
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>↑</kbd> moves to above space with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>↑</kbd> moves window to above space with wraparound
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>→</kbd> moves to right space with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>→</kbd> moves window to right space with wraparound
* <kbd>⌘</kbd><kbd>⎇</kbd><kbd>↓</kbd> moves to below space with wraparound
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>⎇</kbd><kbd>↓</kbd> moves window to below space with wraparound

### `tab.json`

* <kbd>⌘</kbd><kbd>⇞</kbd> moves to previous tab
* <kbd>⌘</kbd><kbd>⇟</kbd> moves to next tab

### `window.json`

* <kbd>⌃</kbd><kbd>⇞</kbd> moves to previous window
* <kbd>⌃</kbd><kbd>⇟</kbd> moves to next window

### `word.json`

* <kbd>⌘</kbd><kbd>←</kbd> moves to word start
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>←</kbd> selects to word start
* <kbd>⌘</kbd><kbd>→</kbd> moves to word end
* <kbd>⇧</kbd><kbd>⌘</kbd><kbd>→</kbd> selects to word end

## Install

1. `cd ~/.config && git clone git@github.com:noel-yap/karabiner.git`
2. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
3. Go to _Preferences_ -> _Complex Modifications_ inside _Karabiner_
4. Press `Add rule` and add the rules

## Helpful links

* [complex_modifications manipulator definition](https://karabiner-elements.pqrs.org/docs/json/complex-modifications-manipulator-definition/)
