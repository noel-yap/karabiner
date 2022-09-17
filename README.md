# karabiner config

## About

### Keyboard 4000

* <kbd>left_command</kbd> → <kbd>left_control</kbd>
* <kbd>left_control</kbd> → <kbd>left_command</kbd>
* <kbd>right_control</kbd> → <kbd>right_command</kbd>
* <kbd>keypad_enter</kbd> → <kbd>return_or_enter</kbd>

### `edit.json`

* <kbd>MouseButton3</kbd> pastes

### `line.json`

* <kbd>Home</kbd> moves to line start
* <kbd>Shift</kbd><kbd>Home</kbd> selects to line start
* <kbd>End</kbd> moves to line end
* <kbd>Shift</kbd><kbd>End</kbd> selects to line end

### `document.json`

* <kbd>Ctrl</kbd><kbd>Home</kbd> moves to document start
* <kbd>Shift</kbd><kbd>Ctrl</kbd><kbd>Home</kbd> selects to document start
* <kbd>Ctrl</kbd><kbd>End</kbd> moves to document end
* <kbd>Shift</kbd><kbd>Ctrl</kbd><kbd>End</kbd> selects to document end

### `exit.json`

* <kbd>Ctrl</kbd><kbd>Alt</kbd><kbd>Delete</kbd> shuts down
* <kbd>Ctrl</kbd><kbd>Alt</kbd><kbd>Insert</kbd> locks screen

### `pane.json`

* <kbd>Alt</kbd><kbd>Left</kbd> moves to previous pane or pane aleft
* <kbd>Alt</kbd><kbd>Up</kbd> moves to previous pane or pane above
* <kbd>Alt</kbd><kbd>Right</kbd> moves to next pane or pane aright
* <kbd>Alt</kbd><kbd>Down</kbd> moves to next pane or pane below

### `paragraph.json`

* <kbd>Ctrl</kbd><kbd>Up</kbd> moves to paragraph start
* <kbd>Ctrl</kbd><kbd>Down</kbd> moves to paragraph end

### `tab.json`

* <kbd>Ctrl</kbd><kbd>PgUp</kbd> moves to previous tab
* <kbd>Ctrl</kbd><kbd>PgDn</kbd> moves to next tab

### `window.json`

* <kbd>Window</kbd><kbd>PgUp</kbd> moves to previous window
* <kbd>Window</kbd><kbd>PgDn</kbd> moves to next window

### `word.json`

* <kbd>Ctrl</kbd><kbd>Left</kbd> moves to word start
* <kbd>Shift</kbd><kbd>Ctrl</kbd><kbd>Left</kbd> selects to word start
* <kbd>Ctrl</kbd><kbd>Right</kbd> moves to word end
* <kbd>Shift</kbd><kbd>Ctrl</kbd><kbd>Right</kbd> selects to word end

## Install

1. `cd ~/.config && git clone git@github.com:noel-yap/karabiner.git`
2. Install [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
3. Go to _Preferences_ -> _Complex Modifications_ inside _Karabiner_
4. Press `Add rule` and add the rules

## Helpful links

* [complex_modifications manipulator definition](https://karabiner-elements.pqrs.org/docs/json/complex-modifications-manipulator-definition/)
