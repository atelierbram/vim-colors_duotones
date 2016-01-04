# Duotones Themes for Vim
Based on [Duotone Themes](http://simurai.com/projects/2016/01/01/duotone-themes/) by [Simurai](http://simurai.com/) for Atom.

> “DuoTone themes use only 2 hues. This leads to a more calm color scheme, but still lets you find the stuff you're looking for.”

Easy clone [Duotones Themes](http://atelierbram.github.io/syntax-highlighting/duotones/ "colorschemes, made with Base16 Builder") for Vim colorschemes, with plugin manager [Pathogen].

## Screenshot
![DuoTone Dark](http://atelierbram.github.io/syntax-highlighting/assets/img/duotones-dark_vim_960x640.png "DuoTone Dark")

## Installation

### Option 1: Manual installation

1.  Move `base16-duotones*.vim` to your `.vim/colors` directory. After downloading the
vim script or package:

```bash
$ cd vim-colors_duotones/colors
$ mv *.vim ~/.vim/colors/
```

### Option 2: Pathogen installation ***(recommended)***

1.  Download and install Tim Pope's [Pathogen].

2.  Next, move or clone the `vim-colors_duotones` directory so that it is
a subdirectory of the `.vim/bundle` directory.

a. **Clone:**

```bash
$ cd ~/.vim/bundle
$ git clone https://github.com/atelierbram/vim-colors_duotones.git
```

b. **Move:**

In the parent directory of vim-colors_duotones:

```bash
$ mv vim-colors_duotones ~/.vim/bundle/
```

### Modify .vimrc

After either Option 1 or Option 2 above, put the following two lines in your
`.vimrc`:

```vim
syntax enable
set background=dark
" BTW these themes do “kind of work” in the light version, but are not optimized for light background mode:
colorscheme base16-duotone-dark
" or any of the other schemes:
" colorscheme base16-duotone-darksea
" colorscheme base16-duotone-darkspace
" colorscheme base16-duotone-darkforest
" colorscheme base16-duotone-darkearth
" colorscheme base16-duotone-darkpool
```

### License

Released under [MIT Licence](http://atelierbram.mit-license.org)

[Pathogen]: https://github.com/tpope/vim-pathogen

### Credits
Credits to [Simurai](http://simurai.com/), for these themes are based on [Duotone Themes](http://simurai.com/projects/2016/01/01/duotone-themes/) for Atom.
