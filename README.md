# cmp-npm

This is an additional source for nvim-cmp, it allows you to autocomplete npm packages and its versions. The source is only active if you're in a package.json file.

## Requeriments

It needs the Neovim plugin nvim-cmp and the npm command line tool.

## Instalation

For [vim-plug](https://github.com/junegunn/vim-plug):

```
Plug 'nvim-lua/plenary.nvim'
Plug 'Yoliani/cmp-npm'
```

For [packer](https://github.com/wbthomason/packer.nvim):

```
use {
  'Yoliani/cmp-npm',
  requires = {
    'nvim-lua/plenary.nvim'
  }
}
```
