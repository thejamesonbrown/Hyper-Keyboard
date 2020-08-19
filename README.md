# Hyper Keyboard

**Transforms Caps Lock into a Hyper key and creates additional keyboard shortcuts.**

* Powerful: Make Caps Lock a great new modifier key: **Hyper(✱)**. 
* Well-Designed:  High-Freq key in hot-area. Bring lots of useful functionalities.
* Compatiable: Work well with other modifiers, appliactions, devices.
* Light-Weight:  Just a small script, carry it everywhere !




## Systems

- [Mac](mac/)  via  [Karabiner-Elements](https://karabiner-elements.pqrs.org)
  - macOS 10.12 (Sierra) - 10.15 (Catalina)
- [Windows](win/) via AutoHotKey  *(currently not maintained)*
  - Windows XP, Vista, 7, 8, 10




## Install (Mac)

1. Download and install [Karabiner-Elements](https://karabiner-elements.pqrs.org).

2. Copy the URL to your browser to import the configuration script.

```bash
# Open in Safari
karabiner://karabiner/assets/complex_modifications/import?url=https://raw.githubusercontent.com/thejamesonbrown/Hyper-Keyboard/main/mac/hyper-keyboard.json
```

3. In Karabiner-Elements:
    1. Open "Complex modifications" tab
    2. Click "Add Rule" button
    3. Enable Hyper Keyboard rules
4. Default config file path is: `$HOME/.config/karabiner/assets/complex_modifications`
    * Modifications can be made in the .json file




## Usage (Mac)

![](images/keyboard.png)

### Basic Function

`✱` Hyper actually maps to `⌃⌥⇧⌘` (all right modifier keys). It can also work with the left modifier keys for creating more key combinations. A single Caps Lock press will send `Escape` and holding Caps Lock enables `Hyper`.

| Origin    | Maps to    | Comment                    |
| --------- | ---------- | -------------------------- |
| `⇪` Press | `⎋` Escape | Single press to escape     |
| `⇪` Hold  | `✱`  Hyper | Enable Hyper               |


### Text Editing

- Hold  `✱` Hyper to enable navigators
- Hold additional `⌘` Command for **selection** . (just like holding ⇧shift in normal)

| Origin | Maps to        | Comment                  |
| ------ | -------------- | ------------------------ |
| `H`    | `←` LeftArrow  | cursor left              |
| `J`    | `↓` DownArrow  | cursor down              |
| `K`    | `↑` UpArrow    | cursor up                |
| `L`    | `→` RightArrow | cursor right             |
| `U`    | `⇞` PageUp     | cursor page up           |
| `I`    | `↖` Home       | cursor to line(doc) head |
| `O`    | `↘`  End       | cursor to line(doc) end  |
| `P`    | `⇟` PageDn     | cursor page down         |
| `⌘H`    | `⇧←` LeftArrow  | cursor left and selection         |
| `⌘J`    | `⇧↓` DownArrow  | cursor down and selection         |
| `⌘K`    | `⇧↑` UpArrow    | cursor up and selection         |
| `⌘L`    | `⇧→` RightArrow | cursor right and selection         |


### Mouse Keys

Emulate mouse movement with the keyboard

| Origin | Maps to        | Comment                  |
| ------ | -------------- | ------------------------ |
| `⌥H`    | `←` LeftArrow  | mouse left              |
| `⌥J`    | `↓` DownArrow  | mouse down              |
| `⌥K`    | `↑` UpArrow    | mouse up                |
| `⌥L`    | `→` RightArrow | mouse right             |
| `←`    | MouseLeft  | mouse cursor left              |
| `↓`    | MouseDown  | mouse cursor down              |
| `↑`    | MouseUp    | mouse cursor up                |
| `→`    | MouseRight | mouse cursor right             |
| `↩`    | MouseLeft     | mouse left button click           |
| `⌘↩`    | MouseRight      | mouse right button click |


### Text Deletion

| Origin    | Maps to                            | Comment             |
| --------- | ---------------------------------- | ------------------- |
| `N`       | `⌥⌫`  Option + ForwardDelete       | Delete a word ahead |
| `M`       | `⌫` ForwardDelete                  | Delete a char ahead |
| `,`       | `⌦` Delete                         | Delete a char after |
| `.`       | `⌥⌦` Option + Delete               | Delete a word after |
| `⌘M`,`⌘N` | `⌘⌥⌫` Command+Option+ForwardDelete | Delete to line head |


### Desktop/Window Control

- Hold additional `⇧` with `JK` for **switching applications** (same as Command+Tab)
- Hold additional `⌃`  with `HJKL` for **desktop management** (same as Control+Arrow Keys)

| Origin           | Maps to                 | Comment                                  |
| ---------------- | ----------------------- | ---------------------------------------- |
| `⌃H`    | `←` LeftArrow  | expose all              |
| `⌃J`    | `↓` DownArrow  | show desktops              |
| `⌃K`    | `↑` UpArrow    | switch prev desktop               |
| `⌃L`    | `→` RightArrow | switch next desktop        |
| `⇥` Tab          | `⌘⇥` Command+Tab        | Switch Window                            |
| `⌘⇥` Command+Tab | `⌘⇧⇥` Command+Shift+Tab | Switch Window Reversely                  |
| `Q`              | `⌘Q`                    | Close Window                             |
| `W`              | `⌘W`                    | Close Tab                                |
| `A`              | `⌃⌥⇧⌘A`                 | Leaves to [Moom](https://manytricks.com/moom/), ※a window resize app |
| `⌘A`             | `⌃↑`  Ctrl+UpArrow      | OSX Expose All                           |
| `S`              | `⌃⇥`  Ctrl+Tab          | Switch Tab                               |
| `⌘S`             | `⌃⇧⇥` Ctrl+Shift+Tab    | Swtich Tab Reversely                     |
| `⌘D`             | `F11`                   | Show Desktop                             |


### Shifter

- A more convient shift for most case
- Semicolon`;` and Quote  `'` have some special treatment, makes input `!=` and `:=`  easier

| Origin             | Maps to | Comment                  |
| ------------------ | ------- | ------------------------ |
| `1`                | `!`     | Exclamation              |
| `2`                | `@`     | At                       |
| `3`                | `#`     | Sharp                    |
| `4`                | `$`     | Dollar                   |
| `5`                | `%`     | Percent                  |
| `6`                | `^`     | Caret                    |
| `7`                | `&`     | Ampersand                |
| `8`                | `*`     | Star                     |
| `9`                | `(`     | Left Round Bracket       |
| `0`                | `)`     | Right Round Bracket      |
| `-` Minus          | `_`     | Hyphen                   |
| `=` Equal          | `+`     | Plus                     |
| `[` Left Bracket   | `(`     | Left Round Bracket `⇧9`  |
| `]`  Right Bracket | `)`     | Right Round Bracket `⇧0` |
| `;` Semicolon      | `!`     | Exclamation              |
| `'` Single Quote   | `=`     | EqualSign                |
| `⌘;` Semicolon     | `:`     | Colon                    |
| `⌘'` Single Quote  | `=`     | EqualSign                |


### Miscellaneous

| Origin                 | Maps to             | Comment                                        |
| ---------------------- | ------------------- | ---------------------------------------------- |
| `~` BackQuote          | `⌃⇧⌘4`              | macOS Area Screenshot to Clipboard             |
| `⌘~` Command+BackQuote | `⌃⇧4`               | macOS Area Screenshot to Desktop File          |
| `⌫` Backspace          | `⌘⌫`                | macOS Delete File                              |
| `/` Slash              | `⌘/` Command+Slash  | Comment/Uncomment in many IDE                  |
| `\` Backslash          | `⌘/` Command+Slash  | Comment/Uncomment in many IDE                  |
| `␢` Spacebar           | `⌃␢`  Ctrl+Spacebar | Switch Input Source                            |



## Symbol Reference

### Modifiers: Mac

| Sym  | Key     |
| ---- | ------- |
| ✱    | Hyper   |
| ⌃    | Control |
| ⌥    | Option  |
| ⇧    | Shift   |
| ⌘    | Command |

### Modifiers: ⊞Windows

| Sym  | Key     |
| ---- | ------- |
| ✱    | Hyper   |
| ⌃    | Control |
| ⊞    | Windows |
| ⇧    | Shift   |
| ⎇    | Alter   |

### Normal Keys

| GLYPH   | NAME                                   |
| ------- | -------------------------------------- |
|        | Apple                                  |
| ⌘       | Command, Cmd, Clover, (formerly) Apple |
| ⌃       | Control, Ctl, Ctrl                     |
| ⌥       | Option, Opt, (Windows) Alt             |
| ⎇       | Alt                                    |
| ⇧       | Shift                                  |
| ⇪       | Caps lock                              |
| ⏏       | Eject                                  |
| ↩, ↵, ⏎ | Return, Carriage Return                |
| ⌤       | Enter                                  |
| ⌫       | Delete, Backspace                      |
| ⌦       | Forward Delete                         |
| ⎋       | Escape, Esc                            |
| →       | Right arrow                            |
| ←       | Left arrow                             |
| ↑       | Up arrow                               |
| ↓       | Down arrow                             |
| ⇞       | Page Up, PgUp                          |
| ⇟       | Page Down, PgDn                        |
| ↖       | Home                                   |
| ↘       | End                                    |
| ⌧       | Clear                                  |
| ⇥       | Tab, Tab Right, Horizontal Tab         |
| ⇤       | Shift Tab, Tab Left, Back-tab          |
| ␢       | Space, Blank                           |
| ␣       | Space, Blank                           |
| ❘⃝      | Power                                  |
| ⇭       | Num lock                               |
| ?⃝      | Help                                   |
|        | Context menu                           |



## FAQ

- Q： Why using ✱ as symbol of hyper key？

  A：Cause asterisk have the ascii code 42, which is the answer to life, the universe, and everything!  while itself has meaning 'star'. ✱ (Heavy-Asterisk) is a pretty version of `*` (Asterisk). Actually I would choose ☯  if Github could render it properly...

- Q：Why Linux support is missing？

  A：because I choose Mac, and use Linux through terminal.

- Q:  Why there is some different key bindings between Mac version and Win version?

  A:   I don't use windows anymore,  Win version is no longer maintained. Welcome if you can fix that.

- Q:  Why there's an old Mac version?

  A:  Apple is really capricious. macOS Sierra changes it's kernel architecture, so the old version karabiner is incompatible with macOS after 10.12. But now there's a new version of karabiner named karabiner-elements. While karabiner-elements use a new JSON-format conf instead of old XML-format. Please using the new version.



## About

Author：Jameson Brown