---
title: "Taming Vim"
date: 2018-08-24T15:01:54+01:00
author: "Darren Jones"
---

As the old story goes, the best way to generate entropy is to ask a Computer Science graduate to exit vim.

Some also say that the only reason they've been using Vim for 10+ years is because they don't know how to quit it.

Vim is awesome. Although the learning curve is steep, once you have mastered it you will spend every day wondering how you survived without it.

When I say the learning curve is steep, it's something like this:

![Example image](/static/img/vim-learning-curve.jpeg)

I've spent a lot of time playing with colors, plugins, macros etc. and after all of the experimentation I have scaled back to just a couple of plugins that I find useful.

I figured it would help me out to write a script that configures Vim on any maching to just the way I like it, so that's what I did.

Once Vim is installed (if not, why not!?), the script will install:

pathogen for managing plugins
NERDTree as an inline file viewer (Ctrl-e will toggle it)
vim-airline (I don't know why I like it but I miss it when it's not there)
ctrl-p for really fast file navigation. Does what it says on the tin!
It will also set up a sensible vimrc to remove any of the common annoyances with vanilla Vim.

![Example image](/static/img/my-vim.png)

You can checkout the script over at my Github.

[https://github.com/dazjones/vim-setup](https://github.com/dazjones/vim-setup)