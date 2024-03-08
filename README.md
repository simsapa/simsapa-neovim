# Simsapa Neovim plugin

If you are using [vim-plug](https://github.com/junegunn/vim-plug), add this in your config files (such as `~/.config/nvim/init.vim`), in the `call plug#begin() ... call plug#end()` section.

Use `:PlugInstall` and `:UpdateRemotePlugins` to install, then close and open neovim.

``` vim-script
" Using the github repository
Plug 'simsapa/simsapa-neovim'

" Or, if you cloned the repository:
Plug '~/path/to/simsapa-neovim'
```

## Try it

Start the Simsapa app, close the main window and let the app stay in the
background. The plugin makes HTTP reqests to the application.

Open this **README.md** file.

Either select or place the cursor on the following word and press `Ctrl+L`: _majjhima patipada_

It should open a _Simsapa Word Lookup_ window with the results (including Pāli accents).
