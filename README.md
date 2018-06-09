# Why tigrana

Okay, so [xoria256]() looks great, but it's missing a few things and it
appears to be stuck at v1.5 if I want to use it in a Pluggable format.  The
author has an open pull request from a non-public repository for v1.6.  I
could go with the non-pluggable version, but why?

Whilst looking for that, I found [bubblegum]().  Since there are a few things
I think I'd like to improve with xoria, I thought I'd have a look.

I'd say bubblegum is better organized and easier to maintain, but it needs
"more work" for me than xoria did.  It has less contrast and at times with
xoria I wanted more.  Since bubblegum gets more updates though and is easier
to maintain, I figured I'd go with that and de-bubblegum it back to xoria
settings where needed and then tweak the things I want.


## How do you install/use it?

I use [vim-plug](), and the installation for tigrana under that looks
something like this:

```vim
" Specify a directory for plugins (for Neovim: ~/.local/share/nvim/plugged)
call plug#begin('~/.config/nvim/plugged')

Plug 'https://gitlab.com/iKarith/tigrana.git'

call plug#end()

colorscheme tigrana-256-dark
```

I use neovim and prefer my plugged directory in ~/.config.  Note the full URL
is specified because I'm using the repository from GitLab.


## So why the name?

Xoria is a genus of moth.  Tigrana is another genus in the same family.  I'm
clever like that.  Or at least, Wikipedia is and I know how to use it.  :)


## Will you be updating both dark and light?

Generally yes.  I'm not a light person, although I've been maintaining some
parity with the dark version in the light.  I can't say it looks great, but
if you want to contribute changes to it, feel free.  :)


## Are you interested in sharing?

I didn't exactly ask @baskerville for permission to mod his colorscheme, and I
really didn't ask Dmitriy Zotikov.  Bastien, if you care to pull any of my
changes upstream at some point, feel free.  And if anyone else finds this theme
useful, feel free to derive from it.


## Where's that colors pic?

The one from the bubblegum `README.md`?  Right here:

![preview](https://gitlab.com/iKarith/tigrana/raw/master/preview/bubblegum_preview.png)

And here's one I made using my little Python script:

![preview](https://gitlab.com/iKarith/tigrana/raw/master/preview/256colors.png)


[xoria256]: https://github.com/vim-scripts/xoria256.vim
[bubblegum]: https://github.com/baskerville/bubblegum
[vim-plug]: https://github.com/junegunn/vim-plug
