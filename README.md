vim all-in-one plugins package repository

## Information

### Summary
- Collection of (n)vim repositories and designed to be an all-in-one package repository for all things vim
- Uses submodules to link the target repository into this collection without cloning them directly

### Project Filesystem Structure
- root/
    - README.md
    - repositories/
        - vim/  : For all vimscript/vim9script packages
            - README.md : List of packages
            - packages/
                - [author-name]/
                    - [repository-name]/
                        - docs/
                        - [submodule - author/repository]
        - nvim/ : For all lua-based/neovim API packages
            - README.md : List of packages
            - packages/
                - [author-name]/
                    - [repository-name]/
                        - docs/
                        - [submodule - author/repository]

## Setup
### Dependencies
+ vim : Optional; if you are using vim (vimscript/vim9script) and not neovim
+ neovim : Optional; if you are using neovim (lua/vimscript) and not vim

### Pre-Requisites
- Prepare the configuration folder structure of the respective editors
    - vim
        - ~/.vim : Root folder
            - vimrc
    - neovim (nvim)
        - ~/.config/nvim : Root folder
            - init.vim : If you are using vimscript
            - init.lua : If you are using lua
            - lua/ : Contains all your lua configurations
                - [lua-files-here...]

### Plugin Submodules 
- Initialize all plugin submodules
    ```console
    git submodule update --init 
    ```

## Documentations

## Wiki

## Resources

## References

## Remarks
