# Caps Lock as a Left-Hand Function Layer


## Introduction
This project reprograms the Caps Lock key to instead yield access to a function layer that increases typing comfort and ergonomics by reducing the amount of hand movement in typing. It brings several critical and often-used features within reach of the home row.

### Inspiration
The inspiration for this project comes from small keyboard designs (40-60%) which promote reduced hand movement fewer keys, using function layers to access the functions of the 'missing' keys. For instance, 60% keyboards eliminate the dedicated keys for the numpad, navigation keys, function keys, and insert/delete keys. These "missing keys" are usually accessed through function layers, e.g. fn + Backspace for Delete.

### Description
This layout is optimized for general writing and coding and probably sucks for gamers.

The approach is such that the left hand has a few tasks:
- Accessing modifiers (Ctrl, Opt/Win, Alt/Cmd, Shift)
- Performing 'main' functions (Enter, Backspace/Delete aka forward delete)
- Bringing up access to the numpad layer.

whereas the right hand is responsible for:
- Navigation features (arrow keys, pg up/dn, etc)
- Access symbol keys that otherwise require reaching
- Accessing the keys for the numpad layer



### Compatibility
This layout can be applied to most traditional (non-ortholinear) keyboards 60% and up, allowing users of larger keyboards to 'test drive' the benefits of a smaller keyboard layout without committing to a physical downsize. While the functionality is not as complex as some custom small keyboard layouts, a significant advantage of this approach is that you don't need to completely re-learn how to type. All the original key functions remain unchanged except for Caps Lock (toggled by Caps Lock + Space), allowing users to fall back on old habits when necessary.

The use of the caps lock to access the function layer with your left hand is incompatible with most HHKB-style keyboards, which place Control in the Caps Lock position. Some HHKB-style boards may offer a dedicated left-hand function key, e.g. next to left shift, however, ergonomics are optimized for the key in the traditional Caps Lock position. The spacebar is also a possibility for accessing the layer (tap for space, hold for layer). 


## Layout
Below are the specific keymappings within the Caps Lock layer.

For brevity, I use the following symbols:
- ⌘: Command
- ⌥: Option
- ⌃: Control
- ⇧: Shift
- ↵: Enter/Return
- ⎋: Escape
- ⌫: Backspace
- ⌦: Delete (forward delete)
- ⊞: Super/Win key

Letter and number keys are referred to within single quotes, i.e. the the key immediately to the right of Tab is 'q'. Symbol keys are denoted with their primary character followed by the shifted character in single quotes, i.e. the key to the left of ⌫ on a US English ANSI layout is '=+'.

The Caps Lock key is denoted ⇪ below.


### Toggle Caps Lock
The caps lock toggle is available by pressing ⇪ + Space.


### Left Hand (main functions + modifiers)
1. 'q' → ⎋
2. 'w' → ⌃ (alt. ⊞ for Windows)
3. 'e' → ↵
4. 'r' → Print
5. 'a' → ⌥ (alt. ⌃ for Windows)
6. 's' → ⌘ (alt. Alt for Windows)
7. 'd' → ⌫
8. 'f' → ⌦
9. 'z' opens access to the Numpad layer below
10. 'x' → F13
11. 'c' → ⇧
12. 'v' opens access to the Media layer below


### Right Hand (navigation + symbols)
Navigation functions may be accessed via your right hand:
1. 'i' → up 
2. 'j' → left
3. 'k' → down
4. 'l' → right
5. 'y' → Page Up
6. 'h' → Page Down
7. 'p' → Home
8. ';:' → End
9. 'u' →'[{'
10. 'o' → ']}'
11. 'n' → '-_'
12. 'm' → '+='
13. '/?' → '\|'


### Function Keys 
The number row keys are mapped to the function keys ('1' as 'F1', '2' as 'F2', ... '=/+' as 'F12').


### Numpad Layer
The numpad layer is accessed by holding Caps Lock + 'z':
1. '7', '8', and '9' map to themselves
2. 'u', 'i', 'o' map to '4', '5', '6'
3. 'j', 'k', 'l' map to '1', '2', '3'
4. 'm' and ',<' map to '0' and '00' respectively
5. '.>' maps to a period/decimal point '.'


### Media Layer
The media layer is accessed by holding ⇪ + 'v':
1. 'j' → skip backwards
2. 'l' → skip forwards
3. 'i' → volume up
4. 'k' → volume down
5. ',<' → previous track
6. '.>' → next track
7. 'h' → stop
8. ';:' → play/pause


## Usage
The below sections detail the usage of the layer.

### Chording
While general usage is straightforward, what may not be is the chording. For example, the following critical functions may be accessed with your left hand exclusively:

- To delete the previous or next word, hold ⇪ + 'a' (⌥) and hit 'd' (⌫) or 'f' (⌦) respectively.
- To delete all text on the line before or after the cursor, hold ⇪ + 's' (⌘) and hit 'd' or 'f' respectively.
- To insert a new line without submitting the current text, hold ⇪ + 'c' (⇧) and hit 'e' (↵).

Furthermore, by including the navigation functions with our right hand:

- To jump the cursor to the next or previous word, hold ⇪ + 'a' (⌥) and hit 'l' (right arrow) or 'j' (left arrow) respectively 
- To highlight the previous or next page of text, hold ⇪ + 'c' (⇧) and press 'h' (Page Up) or 'n' (Page Down) respectively
- To unindent or indent a line in a code editor, hold ⇪ + 's' (⌘) and hit 'u' ('[{') or 'o' (']}') respectively


## Modifier Modifications for Windows
Because modifier keys behave differently in Windows versus macOS, we make the following modifications to adapt the layout for Windows:

1. 'a' → ⌃
2. 's' → Alt
3. 'w' → ⊞


## F13
The layer includes access to the user-programmable F13 key via 'x'.

Personally, I have this key mapped to Non-US Backslash (NUBS) or '§±' in Karabiner-Elements, which then maps to Compose via the use of the US Custom keyboard layout. Compose allows me to write non-standard characters such as → by pressing caps + 'x' to enable composition mode, then typing '->'.

For instructions on enabling the Compose key in macOS, see https://uscustom.sourceforge.net/#installation. Standard key combiations are here: https://github.com/tsibley/compose/blob/master/compose


## Comments
Whenever possible, I have tried to map functions to keys that could be mnemonic or at least easy to remember:
- Escape ('quit') to 'q'
- Win key to 'w'
- Enter to 'e'
- pRint to 'r' (too much of a strech? fair enough...)
- Backspace ('delete') to 'd'
- Delete ('forward delete') to 'f'
- /? aka forward slash to \| aka backslash

In other instances, however, keys are mapped based on usefulness and ergonomics: for example, while it may be more mnemonic to swap ⇧ (Shift) and ⌘ (Command) to 's' and 'c' respectively, the placement of ⌘ at 's' allows for chording the keys ⇪ + 's' + 'f' (⌘ + ⌦), which is far more ergonomic than chording ⇪ + 'c' + 'f'. Because ⌘ + ⌦ is useful, and ⇧ + ⌦ is not, it therefore makes most ergonomic sense to place ⌘ at 's' and ⇧ at 'c'. Furthermore, the location of ⇧ at 'c' enables the chording of 'c' + 'e', or ⇧ + ↵, which is relatively more ergonomic than 's' + 'e'. 

I have tried to avoid remapping common functions which are already easily accessible and ergonomic, e.g., ⌘ + 's' as Save is already easy enough to access, so there's no real need to remap it to this layer.
