# Printed Colors 

### Installation
To install, just simply run:
```bash
pip install printedcolors
```
### Usage
The usage is simple. You can use it like this in normal prints:
```python
import printedcolors
print(printedcolors.Color.fg.red + printedcolors.Color.bold + "I'm red and bold!" + printedcolors.Color.reset)
```
But if you want to keep it even more simple, You can do it like this:
```python
import printedcolors
Color = printedcolors.Color
fg = Color.fg
print(fg.red + "Hi! I'm red!" + Color.reset)
```
Color.reset is recommended to not affect future prints.

Both Color and Colour can be used.

### Supported Colours/Colors

FG (Foreground) Colors/Color:

| Color Name    | Code Example             |
|---------------|--------------------------|
| Black         | `Colour.fg.black`        |
| Red           | `Colour.fg.red`          |
| Green         | `Colour.fg.green`        |
| Yellow        | `Colour.fg.yellow`       |
| Blue          | `Colour.fg.blue`         |
| Magenta       | `Colour.fg.magenta`      |
| Cyan          | `Colour.fg.cyan`         |
| Light Grey    | `Colour.fg.lightgrey`    |
| Dark Grey     | `Colour.fg.darkgrey`     |
| Light Red     | `Colour.fg.lightred`     |
| Light Green   | `Colour.fg.lightgreen`   |
| Light Yellow  | `Colour.fg.lightyellow`  |
| Light Blue    | `Colour.fg.lightblue`    |
| Light Magenta | `Colour.fg.lightmagenta` |
| Light Cyan    | `Colour.fg.lightcyan`    |

BG (Background) Colours/Color:

| Color Name | Code Example          |
|------------|-----------------------|
| Black      | `Colour.bg.black`     |
| Red        | `Colour.bg.red`       |
| Green      | `Colour.bg.green`     |
| Yellow     | `Colour.bg.yellow`    |
| Blue       | `Colour.bg.blue`      |
| Magenta    | `Colour.bg.magenta`   |
| Cyan       | `Colour.bg.cyan`      |
| Light Grey | `Colour.bg.lightgrey` |


Misc (Other):

| Style Name    | Code Example           |
|---------------|------------------------|
| Bold          | `Colour.bold`          |
| Dim           | `Colour.dim`           |
| Underline     | `Colour.underline`     |
| Reverse       | `Colour.reverse`       |
| Strikethrough | `Colour.strikethrough` |
| Invisible     | `Colour.invisible`     |
| Reset         | `Colour.reset`         |

As a reminder, both `Colour` and `Color` can be used. As both is defined in the library.