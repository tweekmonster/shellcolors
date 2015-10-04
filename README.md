# shellcolors

This helps find a close-enough terminal color for user supplied hexadecimal
colors.  You will need to use a terminal that supports RGB escape sequences
(Apple Terminal won't work).

I built this to help me find close-enough colors to replace my base16 tomorrow
theme with colors that will work in terminals that can't assign colors.


## Usage

``./shellcolors 1d1f21 282a2e 373b41 969896 b4b7b4 c5c8c6 e0e0e0 ffffff cc6666 de935f f0c674 b5bd68 8abeb7 81a2be b294bb a3685a``

* **[hex, ...]**  One or more hexadecimal colors.
* **-q**, **--shutup**  Just print the matching terminal colors.
* **-p**, **--palette**  Display the table of colors in your terminal.
* **--rgb**  Combined with the above, the right side of the swatch will display
  actual rgb colors for the corresponding terminal color.  This is useful for
  displaying the original color if you are using a theme to replace the
  defaults.


## Cool Graphics

Finding close matches for base16-tomorrow-dark:

![base16-tomorrow](https://cloud.githubusercontent.com/assets/111942/10266532/61b4f41a-6a39-11e5-90b0-d6e2c932bebc.png)

Color table with base16-tomorrow-dark.sh:

![colors](https://cloud.githubusercontent.com/assets/111942/10266223/86bac56c-6a22-11e5-8585-4f55660da0c6.png)

Color table with original colors displayed next to the current colors (originals are the right half of the swatch):

![colors-rgb](https://cloud.githubusercontent.com/assets/111942/10266231/e2dd7876-6a22-11e5-8b60-f1c6eca351f5.png)
