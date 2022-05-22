# Puple Depth 💜
[![](https://img.shields.io/badge/Made%20With-nvim%20%E2%9D%A4-red?style=for-the-badge)](https://github.com/neovim/neovim)
[![](https://img.shields.io/badge/Folder%20Size-84.1%20KB-yellow?style=for-the-badge)]()

## Why purpledepth?

Honestly idk, but it is an entirely purple schema, well... not fully but it has purple 🤠

**Enjoy it**

## Get Started

With vim-plug, add this into ur plug calls `Plug 'simmxns/purpledepth'` then `:PlugInstall`

**Also u need to add this into ur vimrc/init.vim file:**
```viml
if exists('+termguicolors')
  let &t_8f = "\<Esc>[38;2;%lu;%lu;%lum"
  let &t_8b = "\<Esc>[48;2;%lu;%lu;%lum"
  set termguicolors
endif

colorscheme purpledepth
```


## Preview

<div align="center">
  <img src="https://user-images.githubusercontent.com/62354548/169699232-d3a805de-245e-49af-9fb8-33054906ce9b.png" />
  <i>Screenshot to the statusline (lightine)</i>
</div>


## Plugins

- To put it on [lightline](https://github.com/itchyny/lightline.vim): `let g:lightline = { 'colorscheme': 'purpledepth' }`

## Contributing

- [pull requests](https://github.com/sssimxn/pinkple/pulls) are welcome ;)
