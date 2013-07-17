# About

This repo versions my git configuration so that I can easily replicate my git settings
across all computers. And setting up a new computer for development is fast.

It works by creating a symlink from the user's home directory to the versioned `gitconfig`
file which has aliases and settings I like (e.g. autorebasing on pull). The `gitignore_global`
ignores compiled source files, packages, logs, databases, and OS and Vim-generated files.

# Installation

    git clone https://github.com/tranzfuse/git-config.git ~/.git-conf
    ln -s ~/.git-conf/gitconfig ~/.gitconfig
    ln -s ~/.git-conf/gitignore_global ~/.gitignore_global

If you are not Adam Smith, make sure to change the name and email address in `gitconfig`.
