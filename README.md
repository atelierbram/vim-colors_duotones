# DuoTones
Based on [Duotone Themes](http://simurai.com/projects/2016/01/01/duotone-themes/) by [Simurai](http://simurai.com/) for Atom.

> “DuoTone themes use only 2 hues (7 shades in total). It tones down less important parts (like punctuation and brackets) and highlights only the important ones. This leads to a more calm color scheme, but still lets you find the stuff you're looking for.”

Go to [demopage](http://atelierbram.github.io/syntax-highlighting/duotones)

## Screenshot
![DuoTone Dark](http://atelierbram.github.io/syntax-highlighting/assets/img/duotones-dark_vim_960x640.png "DuoTone Dark")

- [DuoTone darkSea](http://atelierbram.github.io/syntax-highlighting/assets/img/duotones-darkSea_vim_960x640.png "DuoTone Dark")
- [DuoTone darkSpace](http://atelierbram.github.io/syntax-highlighting/assets/img/duotones-darkSpace_vim_960x640.png "DuoTone Dark")
- [DuoTone darkEarth](http://atelierbram.github.io/syntax-highlighting/assets/img/duotones-darkEarth_vim_960x640.png "DuoTone Dark")
- [DuoTone darkForest](http://atelierbram.github.io/syntax-highlighting/assets/img/duotones-darkForest_vim_960x640.png "DuoTone Dark")
- [DuoTone darkPool](http://atelierbram.github.io/syntax-highlighting/assets/img/duotones-darkPool_vim_960x640.png "DuoTone Dark")

Font used in screenshots is [FiraMono](http://www.carrois.com/fira-4-1/#download), set in generous lineheight.

```bash
set guifont=FiraMono-Regular:h14
set linespace=4
```

## Installation

### Option 1: Manual installation

1.  Move `base16-duotones*.vim` to your `.vim/colors` directory. After downloading the
vim script or package:

```bash
$ cd vim-colors_duotones/colors
$ mv *.vim ~/.vim/colors/
```

### Option 2: Pathogen installation ***(recommended)***
Easy clone [Duotones Themes](http://atelierbram.github.io/syntax-highlighting/duotones/ "colorschemes, made with Base16 Builder") for Vim colorschemes, with plugin manager [Pathogen].

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
### Credits
Credits to [Simurai](http://simurai.com/), for these themes are based on [Duotone Themes](http://simurai.com/projects/2016/01/01/duotone-themes/) for Atom.

### Resources
- [Orginal Colorscheme for Atom on simurai.com](http://simurai.com/projects/2016/01/01/duotone-themes/)
- [Orginal Colorscheme for Atom on Github](https://github.com/simurai/duotone-dark-syntax/blob/master/styles/colors.less)
- [Creating Colorschemes for Vim on vimcasts.org](http://vimcasts.org/episodes/creating-colorschemes-for-vim/)

### License
Released under [MIT Licence](http://atelierbram.mit-license.org)

[Pathogen]: https://github.com/tpope/vim-pathogen
