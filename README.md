<p align="center">
    <img src="https://terminalroot.com.br/assets/img/terminalroot.jpg" alt="Terroo Colors on HTML">
</p>

# Terroo Colors
Terroo Colors is a Material Color Scheme Darker for Vim & inspired by [vim-monokai-bold](https://github.com/Mcmartelle/vim-monokai-bold) and [Minimalist](https://github.com/dikiaap/minimalist).

## Installation

To install this color scheme, you can use one of the following ways:

- Use [Vundle](https://github.com/VundleVim/Vundle.vim#quick-start) by adding
to your `.vimrc` Vundle plugin section:

        Plugin 'terroo/terroo-colors'

    Then run `:PluginInstall`.

OR

- Use [vim-plug](https://github.com/junegunn/vim-plug#installation) by adding
to your `.vimrc` vim-plug section:

        Plug 'terroo/terroo-colors'

    Then run `:PlugInstall`.

OR

- Use [Pathogen](https://github.com/tpope/vim-pathogen#installation):

    Run the following in a terminal:

        cd ~/.vim/bundle
        git clone https://github.com/terroo/terroo-colors

## Usage

After finishing installation, put this code to your `.vimrc`:

```viml
set t_Co=256
syntax on
colorscheme terroo-colors
```

This color scheme also built-in with airline theme. If you wanna use:

```viml
let g:airline_theme='terrooairline'
let g:airline_powerline_fonts = 1
let g:airline#extensions#tabline#enabled = 1
```

## Support

As you know, color scheme in vim by default supports many programming languages.
At this time `terroo-colors` is looks beautiful & focused on:

* C++
* CSS/CSS3
* HTML/HTML5
* JavaScript
* Markdown
* PHP
* Python
* Ruby
* Sass
* Shell
* XML

If you need more syntax highlighting, you can use
[vim-polyglot](https://github.com/sheerun/vim-polyglot).

## Links

[GitHub](https://github.com/terroo/terroo-colors) ·
[Vim.org](https://www.vim.org/) ·
[Blog](https://en.terminalroot.com.br/)

## License

GPLv3 © [Terminal Root](https://terminalroot.com.br/)
