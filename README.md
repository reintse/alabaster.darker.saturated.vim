# alabaster-darker-saturated.vim

Fork of [sderev's Alabaster dark theme](https://github.com/sderev/alabaster.vim)

Which is based on [tonsky's Alabaster theme](https://github.com/tonsky/sublime-scheme-alabaster).

My theme differs as I changed te colors to be more high contrast, and saturated, out of preference. 
(I know it defeats the point of the originals being minimal and easy on the eyes, but I did it anyway)

Another inspiration for the contrast was [Ethan Schoonover's Solarized](https://ethanschoonover.com/solarized/)

PLEASE NOTE THAT I DID NOT MODIFY ANYTHING OTHER THAN THE COLOR PALETTE OF SDEREV'S DARK THEME AND I CLAIM NO CREDIT FOR ANYTHING OTHER THAN THE NEW COLOR SCHEME

### preview:
![alabaster-darker-saturated.vim](/preview/alabaster-darker-saturated.png)

## Requirements
* Terminal with true color support, such as Kitty or Alacritty (or GUI Vim/Neovim)

## Installation

```bash
mkdir -p ~/.vim/colors
cp /path/to/alabaster-darker-saturated.vim/colors/alabaster-darker-saturated.vim ~/.vim/colors/
```

Add to your `.vimrc`:

```vim
syntax enable
set termguicolors

colorscheme alabaster-darker-saturated.vim
```
