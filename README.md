# No-Buttons Calculator

A keyboard-first calculator. No buttons — your keyboard already has them.

## Usage

Just start typing a math expression: `12 * 34 + 5`. The result updates live.  
Press **Enter** to force-save the current expression to history.  
Press **Escape** to clear everything and start over.

## Features

### Input field
- **Triple-click** the equation field to instantly clear it
- **Escape** clears the equation and result
- **Enter** saves the current expression to history immediately
- Typing is restricted to valid math characters (`0–9`, `+`, `-`, `*`, `/`, `(`, `)`, `.`)
- Expressions auto-save to history after ~2 s of idle time (requires at least one binary operator)

### Result area
- Typing any math key while the result is focused carries the result forward as a new expression (e.g. type `*2` to double the current result)
- **Right-click** the result to copy it to the clipboard
- **Double-click** the result to select its text

### Unit converters (in / mm)
- Appear automatically whenever a valid numeric result is present
- **Right-click** either converter to copy its value

### History
- **Click** a history row to select it (highlighted in orange)
- **Double-click** an expression in history to reload it into the input field
- **Double-click** a result value in history to load that number into the input field
- **Delete** or **Backspace** removes the selected history entry
- **Right-click** an expression or result in history to copy it

### Install as an app
- Works offline — add to your home screen or install as a Chrome / Edge PWA to keep it in your dock
