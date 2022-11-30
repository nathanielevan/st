# nathanielevan's build of st

[st (simple terminal)](https://st.suckless.org) is a terminal implementation for Xorg by [suckless](https://suckless.org). This repository hosts nathanielevan's st configuration, including a selection of patches hosted in [the suckless website](https://st.suckless.org/patches/) to make it usable.

Included in this build:
- Colour configuration based on the Nord colour scheme
- [Box draw patch](https://st.suckless.org/patches/boxdraw/)
- [Bold is not bright patch](https://st.suckless.org/patches/bold-is-not-bright/)
- [Blinking cursor patch](https://st.suckless.org/patches/blinking_cursor/)
- [External pipe patch](https://st.suckless.org/patches/externalpipe/)
- [font2 patch](https://st.suckless.org/patches/font2/)
- [Glyph wide support patch](https://st.suckless.org/patches/glyph_wide_support/)
- [Scrollback patches](https://st.suckless.org/patches/scrollback/)
- [Swap mouse patch](https://st.suckless.org/patches/swapmouse/)
- [Vert center patch](https://st.suckless.org/patches/vertcenter/)
- [w3m patch](https://st.suckless.org/patches/w3m/)

Keybinds:
- Alt+j/k to scroll down/up a line.
- Alt+d/u to scroll down/up a screen.
- Alt+=/- to increase/decrease font size. Reset with Alt+Shift+-.
- Ctrl+Shift+c/v to copy/paste from clipboard.
- Alt+e to open URLs with dmenu.

Dependencies:
- dmenu for opening URLs. Do note that in the `st-openurl` script, I use several command-line options not available in vanilla dmenu:
  * `-h` to adjust line height (provided by the [line height patch](https://tools.suckless.org/dmenu/patches/line-height/))
- Fonts used:
  * FantasqueSansMono Nerd Font Mono
  * Noto Color Emoji (emoji)
