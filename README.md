# Dim 

A Colorscheme which tries to use dim colors

## Usage

To enable this colorscheme:

```vim
colorscheme dim
```

```lua
vim.cmd[[colorscheme dim]]
```

To override the default settings you need to call setup before enabling the
colorscheme. Dim will use these settings, unless you call setup
and override these.

```lua
require("dim").setup({
  transparent = false, -- Enable this to disable the bg color
  styles = {
    -- You can set any of the style values specified for `:h nvim_set_hl`
    comments = {},
    keywords = {},
    functions = {},
    variables = {},
    type = { bold = true },
    lsp = { underline = true }
  },
})
```

## Supported Plugins

- Alpha
- Dadbod-ui
- Git
- Hop
- Lazy
- Leap
- Lir
- LSP
- Lualine
- Markdown
- Mason
- Neogit
- NvimCmp
- NvimTree
- StatusLine
- Telescope
- Treesitter
- WhichKey
