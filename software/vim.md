
# vim

I spend an unusually large amount of my time in the terminal, generally on remote systems using ssh.  While it is possible to connect graphical tools, it is far from convenient.  The best skill you can learn when managing remote systems is a good editor.  In my case I favor vim.

I have mixed feelings as far as the editor goes.  At times its the best editor in my arsenal, and other times I find myself cursing its existence.


## installation

One of the biggest problems is that the version of vim that comes with each system varies, some have a significantly older version (such as osx), and others come with a smaller version by default (eg. `vim.tiny` for debian/ubuntu).

_So the first thing you want to do is make sure you have the latest feature-complete copy available to your platform using your systems package manager._


## configuration

My configuration focuses on solving consistency and functionality where vim is lacking.

_In my experience, vim package managers made the editor itself sluggish, so I don't bother with [pathogen](https://github.com/tpope/vim-pathogen) or [vundle](https://github.com/gmarik/Vundle.vim)._

I have settled on a single lightweight [`~/.vimrc`](https://github.com/cdelorme/dot-files/blob/master/src/.vimrc) which automatically loads my selection of plugins in the fastest way possible:

- [ctrlp](https://github.com/kien/ctrlp.vim)
- [json](https://github.com/elzr/vim-json)
- [go](https://github.com/fatih/vim-go)
- [node](https://github.com/moll/vim-node)
- [ansi esc](https://github.com/powerman/vim-plugin-AnsiEsc)

I also add color-schemes that make the editor a bit more readable or easy-on-the-eyes:

- [VividChalk](https://github.com/tpope/vim-vividchalk)
- [Sunbirst](https://github.com/tangphillip/SunburstVIM.git)
