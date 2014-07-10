## Current Features ##

  * NerdTree - nice tree-view file browsing [F2]
  * Command-T - fuzzy searching to quickly switch files [Meta-T]
  * Conque-Shell - built in terminals [F3] & [F4]
  * Gundo - undo history management [F5]
  * Tagbar - easily browse through a programs structure [F9]
  * Supertab - tab-complete anything you have used in the curent buffer
  * Fugitive - built in Git management
  * Syntastic - syntax checking and correction helpers for most major languages
  * Vim-Indent-Guides - easily see indentions. Customized to match Solarized
  * Pathogen - for easily managing plugins as git submodules
  * Other various helper plugins to aid programming as I find them useful

## Usage / Installation ##

1. Clone .vim directory

    ```bash
    git clone https://github.com/lrvick/dotvim.git ~/.vim
    ```
2. Install submodules

    ```bash
    cd ~/.vim
    git submodule update --init
    ```

3. Install dummy vimrc file

    ```bash
    echo "runtime vimrc" > ~/.vimrc
    ```

