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

```
git clone https://github.com/Dusan-Stojkovic/nvim-config
```

### 2. Configure lazy nvim

Follow the lazy.nvim docs!
https://www.lazyvim.org/installation

### 3. Download telescope.nvim dependencies

These would be ripgrep, fzf and fd. Install them so that telescope can work properly.

### 4. Run Lazy upadate to install plugins

```bash
:Lazy update
```
will install all the plugins added in this nvim config

### 5. Install LSPs

Using meson you should install LSPs. This can be done from nvim in normal mode:

```
:MasonInstall  clangd jdtls ltex_ls lua_ls omnisharp python-lsp-server rust-analyzer

```

### 6. Restart editor

After the restart config features are ready to use.
