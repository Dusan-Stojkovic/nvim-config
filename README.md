# nvim configuration

Requires nvim 0.9.x or later

This neovim configuration is inspired by this youtube playlist:
<https://www.youtube.com/watch?v=X6AR2RMB5tE&list=PLm323Lc7iSW_wuxqmKx_xxNtJC_hJbQ7R>

Especially important is the 0 to LSP video tutorial:
<https://www.youtube.com/watch?v=w7i4amO_zaE>

## Main features of config

* LSPs configured for C/C++, python, C# and lua
* Fuzzy search files and strings within files
* Git commands integrated 
* Markdown preview support
* And many more

## Setup

Here are the steps to configure neovim.

### 1. Clone the repository

### 2. Configure packer

Complete quickstart steps for packer:
https://github.com/wbthomason/packer.nvim

### 3. Download telescope.nvim dependencies

These would be ripgrep and fd. Install them so that telescope can work properly.

### 4. Run PackerInstall to install plugins

Open lua/v2/packer.lua with nvim lua/v2/packer.lua
And type :PackerInstall in Normal Mode.

### 5. Restart editor

After the restart config features are ready to use.
