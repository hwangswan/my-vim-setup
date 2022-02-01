# my-vim-setup

List of plugged-in plugin:
- vim-airlines (statusbar)
- fzf (fuzzyfinder)
- vim-fugitive (git support)
- sonokai (color scheme)

## Installation
1. Run `install.sh`
2. Enter vim, type `:PlugInstall` to install plugs!

## Tips:
### Open terminal inside vim
`:terminal` or `:term` would do the trick, but a horizontally splitted.

To split vertically: `:vertical terminal`, or shorter, `:vert term`

### Vim-fugitive
- Checkout to a branch:
```
:Git checkout <branch_name>
```

## Note:
- If the installation works well, but the airline shape is still weird, try
decreasing line width (terminal).
