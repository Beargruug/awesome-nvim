# Awesome Neovim PDE Resources

A curated list of plugins, configurations, and resources for Neovim.

## Table of Contents

- [Official Documentation](#official-documentation)
- [Getting Started](#getting-started)
- [Plugins](#plugins)
  - [Core Plugins](#core-plugins)
  - [Language Support](#language-support)
  - [Utilities](#utilities)
  - [Themes](#themes)
  - [Linter and Formatter](#linter-and-formatter)
  - [File Navigation](#file-navigation)
  - [Debugging](#debugging)
  - [Snippets](#snippets)
  - [Git Integration](#git-integration)
  - [Testing](#testing)

## Official Documentation

- [Neovim Documentation](https://neovim.io)
- [Getting Started with Neovim](https://neovim.io/start)
- [Neovim Lua Guide](https://github.com/nanotee/nvim-lua-guide)

## Getting Started

To get started with Neovim, you can install it using your package manager or download it from the [official website](https://neovim.io).

### Installation

For installation instructions, visit the [installation guide](https://github.com/neovim/neovim/wiki/Installing-Neovim).

## Plugins

Here are some of the most popular and useful plugins for enhancing your Neovim experience.

### Core Plugins

- [vim-plug](https://github.com/junegunn/vim-plug) - A minimalist plugin manager for Neovim.
- [packer.nvim](https://github.com/wbthomason/packer.nvim) - A plugin manager for Neovim.
- [lazy.nvim](https://github.com/folke/lazy.nvim) - A modern plugin manager for Neovim.
- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - A fuzzy finder for Neovim.
- [nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua) - A file explorer tree for Neovim.
- [vim-obsession](https://github.com/tpope/vim-obsession) - Manage Vim sessions effortlessly.
- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Syntax highlighting with treesitter.
- [nvim-notify](https://github.com/rcarriga/nvim-notify) - A fancy notification manager for Neovim.
- [bufferline.nvim](https://github.com/akinsho/bufferline.nvim) - A buffer line for Neovim.
- [nvim-lsp-installer](https://github.com/wbthomason/packer.nvim) - Installer for LSP servers.
- [vim-sensible](https://github.com/tpope/vim-sensible) - A set of sensible defaults for Vim.
- [harpoon](https://github.com/ThePrimeagen/harpoon) - Quick navigation between files.
- [nvim-colorizer.lua](https://github.com/norcalli/nvim-colorizer.lua) - Colorize hex codes and color names in Neovim.
- [vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors) - Add multiple cursors in Neovim.

### Language Support

- [nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - Quickstart configurations for the Neovim LSP client.
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp) - A completion plugin for Neovim.
- [cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp) - LSP completion source for nvim-cmp.
- [null-ls.nvim](https://github.com/jose-elias-alvarez/null-ls.nvim) - Inject external tools into the LSP.
- [rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim) - Rust-specific enhancements for Neovim.
- [python-lsp-server](https://github.com/python-lsp/python-lsp-server) - Python language server for Neovim.
- [clangd](https://clangd.llvm.org/) - C/C++ language server.
- [tsserver](https://github.com/typescript-language-server/typescript-language-server) - TypeScript/JavaScript language server.
- [gopls](https://github.com/golang/tools/tree/master/gopls) - Go language server.
- [html-lsp](https://github.com/iamcco/markdown-preview.nvim) - HTML language server with Neovim support.

### Utilities

- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) - Git signs for Neovim.
- [which-key.nvim](https://github.com/folke/which-key.nvim) - Displays a popup with possible keybindings.
- [comment.nvim](https://github.com/numToStr/Comment.nvim) - A smart comment toggle for Neovim.
- [nvim-autopairs](https://github.com/windwp/nvim-autopairs) - Automatically insert closing pairs.
- [todo-comments.nvim](https://github.com/folke/todo-comments.nvim) - Highlight TODO comments in your code.
- [vim-surround](https://github.com/tpope/vim-surround) - Easily delete, change, and add surroundings.
- [vim-fugitive](https://github.com/tpope/vim-fugitive) - A Git wrapper for Neovim.
- [vim-abolish](https://github.com/tpope/vim-abolish) - Easily substitute and manipulate text.
- [nvim-comment](https://github.com/terrortylor/nvim-comment) - Commenting plugin for Neovim.
- [nvim-dap](https://github.com/mfussenegger/nvim-dap) - Debug Adapter Protocol client for Neovim.
- [nvim-dap-python](https://github.com/mfussenegger/nvim-dap-python) - Python support for nvim-dap.
- [vim-hexokinase](https://github.com/RRethy/vim-hexokinase) - A plugin for visualizing colors.
- [vim-floaterm](https://github.com/voldikss/vim-floaterm) - A terminal emulator for Neovim.
- [vim-closetag](https://github.com/alvan/vim-closetag) - Automatically close HTML/XML tags.

### Themes

- [kanagawa.nvim](https://github.com/rebelot/kanagawa.nvim) - NeoVim dark colorscheme inspired by the colors of the famous painting by Katsushika Hokusai.
- [gruvbox](https://github.com/morhetz/gruvbox) - A retro groove color scheme for Neovim.
- [onedark.nvim](https://github.com/navarasu/onedark.nvim) - One Dark color scheme for Neovim.
- [tokyonight.nvim](https://github.com/folke/tokyonight.nvim) - A clean and beautiful color scheme.
- [nord.nvim](https://github.com/shaunsingh/nord.nvim) - An arctic, north-bluish color palette.
- [nightfox.nvim](https://github.com/foxflv/nightfox.nvim) - A bright, colorful theme with many variations.
- [catppuccin](https://github.com/catppuccin/nvim) - A mocha-inspired color scheme.
- [dracula.nvim](https://github.com/Dracula/Dracula) - A dark theme with vibrant colors.
- [solarized](https://github.com/altercation/solarized) - A color scheme based on Solarized.
- [edge.nvim](https://github.com/sainnhe/edge) - A soft and elegant color scheme.

### Linter and Formatter

- [ale](https://github.com/dense-analysis/ale) - Asynchronous linting and fixing for Neovim.
- [efm-langserver](https://github.com/mattn/efm-langserver) - A general purpose Language Server that can serve any linter/formatter.
- [lint.nvim](https://github.com/mfussenegger/lint.nvim) - Simple asynchronous linting for Neovim.
- [formatter.nvim](https://github.com/mfussenegger/nvim-lint) - File formatter for Neovim.
- [isort](https://github.com/PyCQA/isort) - Python import sorting tool.
- [prettier](https://prettier.io/) - Code formatter for JavaScript, TypeScript, and more.
- [eslint](https://eslint.org/) - A tool for identifying and reporting on patterns in JavaScript.
- [stylelint](https://stylelint.io/) - A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.
- [rubocop](https://github.com/rubocop/rubocop) - A Ruby static code analyzer and formatter.
- [flake8](https://flake8.pycqa.org/en/latest/) - A tool for enforcing style guide enforcement in Python.

### File Navigation

- [fzf.vim](https://github.com/junegunn/fzf.vim) - Fuzzy file finder for Neovim.
- [nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua) - A file explorer tree for Neovim.
- [vim-vinegar](https://github.com/tpope/vim-vinegar) - A smarter file browser for Vim.
- [vim-dirvish](https://github.com/justinmk/vim-dirvish) - A minimalist file explorer for Vim.
- [nerdtree](https://github.com/preservim/nerdtree) - A tree explorer plugin for navigating the filesystem.

### Debugging

- [nvim-dap](https://github.com/mfussenegger/nvim-dap) - Debug Adapter Protocol client for Neovim.
- [nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui) - A UI for nvim-dap to visualize debugging.
- [nvim-dap-python](https://github.com/mfussenegger/nvim-dap-python) - Python support for nvim-dap.
- [nvim-dap-go](https://github.com/leoluz/nvim-dap-go) - Go debugging support for nvim-dap.
- [nvim-dap-ruby](https://github.com/cheusov/nvim-dap-ruby) - Ruby debugging support for nvim-dap.
- [nvim-dap-javascript](https://github.com/mfussenegger/nvim-dap-javascript) - JavaScript debugging support for nvim-dap.
- [nvim-dap-lua](https://github.com/mfussenegger/nvim-dap-lua) - Lua debugging support for nvim-dap.
- [vimspector](https://github.com/puremourning/vimspector) - A multi-language debugging system for Vim.
- [CodeLLDB](https://github.com/mfussenegger/nvim-dap) - A DAP client for Rust and C/C++.

### Snippets

- [LuaSnip](https://github.com/L3MON4D3/LuaSnip) - Snippet engine for Neovim written in Lua.
- [snipmate.nvim](https://github.com/garbas/snipmate.nvim) - Snippet management for Neovim.
- [vim-vsnip](https://github.com/hrsh7th/vim-vsnip) - Snippet plugin for Neovim.
- [friendly-snippets](https://github.com/rafamadriz/friendly-snippets) - A collection of snippets for various languages.
- [ultisnips](https://github.com/SirVer/ultisnips) - Snippet solution for Vim.
- [snippy](https://github.com/dabams/snippy) - Snippet engine for Neovim.
- [vim-snippets](https://github.com/honza/vim-snippets) - Collection of snippets for various languages.

### Git Integration

- [vim-gitgutter](https://github.com/airblade/vim-gitgutter) - Show a git diff in the 'gutter' (sign column).
- [vim-signify](https://github.com/mhinz/vim-signify) - Shows a git diff in the sign column.
- [gitblame.nvim](https://github.com/f-person/gitblame.nvim) - Blame for Neovim with detailed information.
- [vim-rhubarb](https://github.com/tpope/vim-rhubarb) - GitHub integration for Vim.
- [git-messenger.vim](https://github.com/rhysd/git-messenger.vim) - Show git commit messages in a popup.
- [vim-fugitive](https://github.com/tpope/vim-fugitive) - A Git wrapper for Neovim.
- [vim-obsession](https://github.com/tpope/vim-obsession) - Manage Vim sessions effortlessly.

### Testing

- [vim-test](https://github.com/junegunn/vim-test) - Run tests in Neovim.
- [nvim-test](https://github.com/akinsho/nvim-test) - A better testing experience for Neovim.
- [vim-cucumber](https://github.com/kevinhwang91/vim-cucumber) - Cucumber syntax highlighting.
- [plenary.nvim](https://github.com/nvim-lua/plenary.nvim) - Useful lua functions used by many plugins, including testing tools.
- [pytest](https://docs.pytest.org/en/stable/) - Framework that makes building simple and scalable test cases easy.
- [jest](https://jestjs.io/) - Delightful JavaScript Testing.
- [mocha](https://mochajs.org/) - Simple, flexible, fun JavaScript test framework.
