# PINKPLE 💗💜
[![](https://img.shields.io/badge/Made%20With-nvim%20%E2%9D%A4-red?style=for-the-badge)](https://github.com/neovim/neovim)
[![](https://img.shields.io/badge/Folder%20Size-84.1%20KB-yellow?style=for-the-badge)]()

## Why PinkPle?

Seriouslly idk, but it is for "Pink" & Pur"ple"

## Preview

*Screenshot to a JS file, Im using tree-sitter btw*
<center>
  <img  src="https://github.com/sssimxn/pinkple/blob/main/jspreview.png" alt="JS FILE">
</center>

*Screenshot to the statusline (lightine)*
<center>
  <img  src="https://github.com/sssimxn/pinkple/blob/main/statuspreview.png" alt="STATUSLINE">
</center>

*Screenshot to the tabline (lightline)*
<center>
  <img  src="https://github.com/sssimxn/pinkple/blob/main/tabpreview.png" alt="TABLINE">
</center>

## Plugins

- [lightline](https://github.com/itchyny/lightline.vim)
To put it on lightline: `let:g lightline = { 'colorscheme': 'pinkple' }`

## Install

With vim-plug, add this into ur plug calls
`Plug 'sssimxn/pinkple'` then `:PlugInstall`

Also add this into ur vimrc/init.vim:
```viml
    if exists('+termguicolors')
      let &t_8f = "\<Esc>[38;2;%lu;%lu;%lum"
      let &t_8b = "\<Esc>[48;2;%lu;%lu;%lum"
      set termguicolors
    endif

   colorscheme pinkple
```

### Extra

- [pull requests](https://github.com/sssimxn/pinkple/pulls) are welcome ;)
 - *I used this theme for start mine* [lucid](https://github.com/cseelus/vim-colors-lucid)
