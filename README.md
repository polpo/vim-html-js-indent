# vim-html-js-indent #

This indent plugin restores the inline JavaScript/HTML indenting support which
was removed from [vim-javascript](https://github.com/pangloss/vim-javascript).

With the recent rise in web components and
[Polymer](https://www.polymer-project.org/)'s convention of having web
components be self-contained in one .html file, I'm finding myself editing more
JS inside .html files these days. Vim's built-in cindent-style indentation was
driving me nuts, so here we go.

## Requirements ##

Requires [vim-javascript](https://github.com/pangloss/vim-javascript).

## Installation ##

I like [Pathogen](https://github.com/tpope/vim-pathogen).

    cd ~/.vim/bundle
    git clone https://github.com/polpo/vim-html-js-indent

Otherwise, throw html.vim inside your `~/.vim/indent` directory.

## Credits ##

Thanks to [Hsiaoming Yang](https://github.com/lepture) for the original version
of this indent plugin, which was taken out of vim-javascript (for
understandable reasons).

Original html indent plugin by Andy Wokula, with extra changes by Bram
Moolenar.
