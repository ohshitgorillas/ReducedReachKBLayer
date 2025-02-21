
# Reduced Reach Keyboard Layer aka RRKB Layer

### This project is under currently under heavy construction and is changing daily. If you are interested, please check back for config files.

## Introduction
The Reduced Reach Keyboard (RRKB) Layer project remaps the Caps Lock key to a left-handed function layer which brings frequently used functions within reach of the home row, enhancing typing ergonomics and efficiency by promoting reduced hand movement.

### Inspiration and Benefits
This project is inspired by the layering necessary for very small custom keyboards. These promote improved ergonomics and reduce hand movement by using far fewer keys; 'missing' functions, or those lacking dedicated keys, are accessed via function key layering. As examples, see https://www.reddit.com/r/MechanicalKeyboards/comments/1h3e8ns/bringing_the_full_keyboard_to_within_reach_of/ and https://github.com/argenkiwi/kenkyo

This project aims to bestow some of those benefits onto users of more traditional, larger keyboards by mapping frequently used features onto the 60% portion of the keyboard under a function layer accessed by reprogramming the "Caps Lock" key. As an example, the following commands may be accessed with your left hand, leaving your right hand free to navigate with arrow keys or the mouse:
- Backspace (backwards delete)
- Delete (forward delete)
- Enter
- All modifiers

This allows users to experience and experiment with the benefits of such keyboards without comitting to a physical downsizing, memorizing multiple complex layers, or needing to re-learn how to type: all original key functions remain unchanged except for Caps Lock (accessed via Caps Lock + Space), letting users revert to old habits in a pinch.

### Compatibility
This layout works with most 60% or larger traditional keyboards (non-ortholinear).

Furthermore, this project is incompatible with most HHKB-style keyboards that place Ctrl in the Caps Lock position. Some HHKB-style keyboards may offer a dedicated left-hand function key that could be used instead, however, the ergonomics are optimized for the key in the traditional Caps Lock position. 

The spacebar can also be used to access the layer with good ergonomics (tap for space, hold for layer) if the user`s software hardware supports it.


## Layout
Below are the specific keymappings within the Caps Lock layer.

For brevity, I use the following symbols:
- ⇪: Caps Lock
- ⌘: Command
- ⌥: Option
- ⌃: Control
- ⇧: Shift
- ↵: Enter/Return
- ⌫: Backspace
- ⌦: Delete (forward delete)
- ⊞: Super/Win key

Letter and number keys are referred to in `code` form, i.e. the the key immediately to the right of Tab is `q` and the key to the left of Backspace is `=+`.

The image below displays the function layer for macOS.

![image](https://github.com/user-attachments/assets/db71a6f9-5c96-43e8-8961-49cd6a71e745)

The image below dispalys the basic function layer for Windows/Linux.

![image](https://github.com/user-attachments/assets/5a0efd9e-7a08-4f3c-b094-782228a78b75)

The image below displays the numpad layer:

![image](https://github.com/user-attachments/assets/a904da2b-2a39-4528-8deb-92ca30bcfb1a)


### Left Hand (main functions + modifiers)
The left hand can be used to access common functions that traditionally require the right hand such as enter, backspace, and delete, allowing the user to comfortably perform these functions while navigating with the right hand or mouse, minimizing repetitive movements of the right hand.
1. `q` opens the numpad layer
2. `w` → ⌃ on Mac, ⊞ on Windows
3. `e` → ⇧
4. `r` → ↵
5. `t` toggles the layer on/off (i.e., so you don't have to hold down ⇪) 
6. `a` → ⌥ on Mac, ⌃ on Windows
7. `s` → ⌘ on Mac, Alt on Windows
8. `d` → ⌫
9. `f` → ⌦
10. `g` → Insert


### Right Hand (navigation)
Navigation functions may be accessed via your right hand:
1. `i` → up 
2. `j` → left
3. `k` → down
4. `l` → right
5. `y` → Page Up
6. `h` → Page Down
7. `u` → Home
8. `o` → End
9. `p` → Print Screen


### Numpad Layer
The numpad layer is accessed by holding ⇪ + `q`:
1. `7`, `8`, and `9` map to themselves
2. `u`, `i`, `o` map to `4`, `5`, `6`
3. `j`, `k`, `l` map to `1`, `2`, `3`
4. `m` and `,<` map to `0` and `00` respectively
5. `.>` maps to a period/decimal point `.`


### Miscellaneous Features
Below are the miscellaneous features of the layout:

- The caps lock feature is accessed by ⇪ + spacebar.
- The layer may be toggled with ⇪ + `t` such that ⇪ does not need to be held to access the layer. Pressing `t` will then un-toggle the layer.
- The number row keys are mapped to the function keys (`1` as `F1`, `2` as `F2`, ... `=/+` as `F12`). This is a common remapping found in most 65% or smaller keyboards.


## Usage
The below sections detail the usage of the RRKB layer.


### Chording
While general usage is straightforward, what may not be is the "chording", or the use of multiple key combinations to access various functions. For example, the following critical functions may be accessed with your left hand exclusively by chording multiple keys:
- Delete the previous or next word: Hold ⇪ + `a` (⌥) and press `d` (⌫) or `f` (⌦).
- Delete all text on the line before or after the cursor: Hold ⇪ + `s` (⌘) and press `d` (⌫) or `f` (⌦).
- Insert a new line without submitting the current text (e.g., when composing a message): Hold ⇪ + `e` (⇧) and press `r` (↵).

Furthermore, by including the navigation functions with our right hand, we may access even more functions. For example:
– Jump the cursor to the next or previous word: Hold ⇪ + `a` (⌥) and press `l` (right arrow) or `j` (left arrow).
- Highlight the previous or next page of text: Hold ⇪ + `e` (⇧) and press `y` (Page Up) or `h` (Page Down).
- Move a line of text up or down (in some editors): Hold ⇪ + `a` (⌥) and press `i` (up) or `k` (down).


### Learning the Layout
Obviously, changing one's typing habits to accommodate the RRKB will take time and practice.

Whenever possible, keys are mapped mnemonically or to be generally easy to remember: 
- Super ("Win" key) to `w`
- Enter ("Return") as `r`
- Backspace ("delete previous") to `d`
- Delete ("forward delete") to `f`
- Print Screen to `p`

In other cases, keys are mapped to optimize ergonomics. For instance, while it may be more mnemonic to place ⇧ (Shift) at `s`, ⌘ is instead mapped to `s` and ⇧ to `e` because the ergonomics are better this way:
- Chording ⌘ + ⌫ or ⌦ is useful, whereas ⇧ is not (to my knowledge). I therefore keep ⌘ on the home row with ⌫ and ⌦, because ⇪ + `s` + `d` is more ergonomic than, e.g., ⇪ + `e` + `d`.
- Chording ⇧ + ↵ is more common than chording ⌘ + ↵ (in my experience), and ⇪ + `e` + `r` is more ergonomic than ⇪ + `s` + `r`, although both are possible without too much effort.

Because the functions within the layer are quite dense and will take time to get used to, it's recommended to start slow. The most useful functions are accessing these from the left hand:
1. ⇪ + `r` as Enter
2. ⇪ + `d` or `f` as Backspace and Delete respectively.
3. ⇪ + `a` + `d` or `f` to delete the previous or next word, respectively.

From there, work on incorporating:
1. Arrow keys as `ijkl`
2. Shift as `e` in combination with `ijkl` for highlighting text
3. Opt or Cmd as `a` or `s` in combination with `e` and `ijkl` to highlight words or lines of text.
4. Ctrl/Win as `w` with `jl` to switch desktops

Lastly, users may work on incorporating the miscellaneous navigation functions, symbols, and numpad layer.


### Customization
The `z` row of the keyboard is left open for user customization. As someone who frequently writes code, I tend to map frequently used symbols like `_`, `+`, `{`, `}` which otherwise require hitting shift and reaching away from home row to access.
