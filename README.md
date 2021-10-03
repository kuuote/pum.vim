# pum.vim

Note: It is still experimental version.

[![Doc](https://img.shields.io/badge/doc-%3Ah%20pum-orange.svg)](doc/pum.txt)

Please read [help](doc/pum.txt) for details.

<!-- vim-markdown-toc GFM -->

- [Introduction](#introduction)
- [Install](#install)
- [Configuration](#configuration)
- [Screenshots](#screenshots)

<!-- vim-markdown-toc -->

## Introduction


## Install

**Note:** pum.vim requires Neovim (0.6.0+ and of course, **latest** is
recommended) or Vim 8.2.1978.

For vim-plug

```viml
call plug#begin()

Plug 'Shougo/pum.vim'

call plug#end()
```

For dein.vim

```viml
call dein#begin()

call dein#add('Shougo/pum.vim')

call dein#end()
```

## Configuration

```vim
inoremap <Tab>   <Cmd>call pum#map#select_relative(+1)<CR>
inoremap <S-Tab> <Cmd>call pum#map#select_relative(-1)<CR>
inoremap <C-n>   <Cmd>call pum#map#insert_relative(+1)<CR>
inoremap <C-p>   <Cmd>call pum#map#insert_relative(-1)<CR>
inoremap <C-y>   <Cmd>call pum#map#confirm()<CR>
inoremap <C-e>   <Cmd>call pum#map#cancel()<CR>
```

## Screenshots

## Plans

