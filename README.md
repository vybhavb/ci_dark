# CI Dark

![nvim preview](https://raw.githubusercontent.com/chuling/vim-equinusocio-material-preview/master/ci_dark_nvim.png)

![term preview](https://raw.githubusercontent.com/chuling/vim-equinusocio-material-preview/master/ci_dark_term.png)

## Usage

iTerm color preset: [ci_dark.itermcolors](term/)

Neovim/Vim

```viml
Plug 'chuling/ci_dark'
Plug 'luochen1990/rainbow'

syntax on
set termguicolors
" choose type of theme, 'default' or 'darker'
let g:ci_dark_style = 'darker'
colorscheme ci_dark

set fillchars+=vert:│

let g:airline_theme = 'ci_dark'
let g:lightline = {
  \ 'colorscheme': 'ci_dark',
}
```

[basic color preset](preset_doc/color.txt)

## License

MIT OR Apache-2.0
