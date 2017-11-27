# Molokai Color Scheme for Vim

Molokai is a Vim port of the monokai theme for TextMate originally created by Wimer Hazenberg.

By default, it has a dark gray background based on the version created by Hamish Stuart Macpherson for the E editor.

![Gray Background](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_normal_small_3.png)

![Molokai Original](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_original_small_3.png)

256-Color terminals are also supported, though there are some differences with the Gui version. Only the dark gray background style is supported on terminal vim at this time.

## Installation

molokai follows the standard runtime path structure. Below are some helper lines
for popular package managers:

* [Pathogen](https://github.com/tpope/vim-pathogen)
  * `git clone https://github.com/hhktony/molokai.git ~/.vim/bundle/molokai`
* [vim-plug](https://github.com/junegunn/vim-plug)
  * `Plug 'hhktony/molokai'`

If you prefer the scheme to match the original monokai background color, put this in your .vimrc file: 
```vim
let g:molokai_original = 1
```

There is also an alternative scheme under development for color terminals which attempts to bring the 256 color version as close as possible to the the default (dark) GUI version. To access, add this to your .vimrc:
```vim
let g:rehash256 = 1
```

Transparent mode

```vim
let g:molokai_transparent = 1
```
