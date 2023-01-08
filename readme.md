<p align="center">
	<img src="https://i.imgur.com/EwZ0O9P.png">
</p>

#### About
Made by [hgoose](https://github.com/hgoose), It is advised 
that you change you terminals cursor color to one that can be 
seen on a white background 


#### Font

click [here](https://github.com/rendello/templeos_font) to get the best font ever made

#### Airline
It is advised that you have Airline for vim click [here](https://github.com/vim-airline/vim-airline) to get Airline for Vim
#### Install
Using vim plug

```vim
call plug#begin('~/.config/nvim/plugged')

Plug `hgoose/temple.vim`

call plug#end()

```

Using Packer



```lua
return require('packer').startup(function(use)

use 'hgoose/temple.vim'

end)
```


Set Colorscheme in vim

```vim
:colorscheme temple
```

#### Set colorscheme on open


with init.vim

```vim
set termguicolors 
colorscheme temple
```

with init.lua

```lua
vim.cmd("colorscheme temple")
```
