# Neovim Monokai

## Supported Monokai Flavours
- Monokai (monokai)
- Monokai Pro (monokai_pro)
- Monokai Soda (monokai_soda)
- Monokai Ristretto (monokai_ristretto)

## Prerequisites

Neovim >= 0.5.

## Installation
| Plugin Manager                                       | Command                                                                              |
|------------------------------------------------------|--------------------------------------------------------------------------------------|
| [Packer](https://github.com/wbthomason/packer.nvim)  | `use 'tanvirtin/monokai.nvim'`                                                       |
| [Vim-plug](https://github.com/junegunn/vim-plug)     | `Plug 'tanvirtin/monokai.nvim'`                                                      |
| [NeoBundle](https://github.com/Shougo/neobundle.vim) | `NeoBundle 'tanvirtin/monokai.nvim'`                                                 |
| [Vundle](https://github.com/VundleVim/Vundle.vim)    | `Bundle 'tanvirtin/monokai.nvim'`                                                    |
| [Pathogen](https://github.com/tpope/vim-pathogen)    | `git clone https://github.com/tanvirtin/monokai.nvim.git ~/.vim/bundle/monokai.nvim` |
| [Dein](https://github.com/Shougo/dein.vim)           | `call dein#add('tanvirtin/monokai.nvim')`                                            |

## Usage

In VimL:

```viml
syntax on
colorscheme monokai
colorscheme monokai_pro
colorscheme monokai_soda
colorscheme monokai_ristretto
```

In Lua:

```lua
require('monokai').setup {}
require('monokai').setup { palette = require('monokai').pro }
require('monokai').setup { palette = require('monokai').soda }
require('monokai').setup { palette = require('monokai').ristretto }
```


## Extras

Extra color configs for **Kitty**, can be found in [extras](extras/). To use them, refer to their respective documentation.
