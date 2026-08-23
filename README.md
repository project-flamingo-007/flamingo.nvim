# flamingo.nvim

neovim colorscheme based off primeagen's broken tmux rose-pine colorscheme

![flamingo.nvim_preview.png](./assets/flamingo.nvim_preview.png)

```lua
return {
	"rb152080/flamingo.nvim",
    name = "flamingo.nvim",
    config = function()
        -- optional (my preferences)
        require("flamingo").setup({
            styles = {
                italic = false,
                bold = false,
                transparency = false,
            },
        })
        vim.cmd("colorscheme flamingo")
        -- optional (my preferences)
        vim.api.nvim_set_hl(0, "Normal", { bg = "none" })
        vim.api.nvim_set_hl(0, "NormalFloat", { bg = "none" })
    end,
}
```

## palette

| color | variable | hex code |
| :---: | :--- | :--- |
| ![#1c1c1c](https://img.shields.io/badge/-%231c1c1c?style=flat-square&color=1c1c1c) | `_nc` | `#1c1c1c` |
| ![#1c1c1c](https://img.shields.io/badge/-%231c1c1c?style=flat-square&color=1c1c1c) | `base` | `#1c1c1c` |
| ![#262626](https://img.shields.io/badge/-%23262626?style=flat-square&color=262626) | `surface` | `#262626` |
| ![#303030](https://img.shields.io/badge/-%23303030?style=flat-square&color=303030) | `overlay` | `#303030` |
| ![#5f5f87](https://img.shields.io/badge/-%235f5f87?style=flat-square&color=5f5f87) | `muted` | `#5f5f87` |
| ![#8787af](https://img.shields.io/badge/-%238787af?style=flat-square&color=8787af) | `subtle` | `#8787af` |
| ![#d7d7ff](https://img.shields.io/badge/-%23d7d7ff?style=flat-square&color=d7d7ff) | `text` | `#d7d7ff` |
| ![#ff5f87](https://img.shields.io/badge/-%23ff5f87?style=flat-square&color=ff5f87) | `love` | `#ff5f87` |
| ![#ffaf87](https://img.shields.io/badge/-%23ffaf87?style=flat-square&color=ffaf87) | `gold` | `#ffaf87` |
| ![#ffafaf](https://img.shields.io/badge/-%23ffafaf?style=flat-square&color=ffafaf) | `rose` | `#ffafaf` |
| ![#5f8787](https://img.shields.io/badge/-%235f8787?style=flat-square&color=5f8787) | `pine` | `#5f8787` |
| ![#afd7d7](https://img.shields.io/badge/-%23afd7d7?style=flat-square&color=afd7d7) | `foam` | `#afd7d7` |
| ![#d7afd7](https://img.shields.io/badge/-%23d7afd7?style=flat-square&color=d7afd7) | `iris` | `#d7afd7` |
| ![#87afaf](https://img.shields.io/badge/-%2387afaf?style=flat-square&color=87afaf) | `leaf` | `#87afaf` |
| ![#262626](https://img.shields.io/badge/-%23262626?style=flat-square&color=262626) | `highlight_low` | `#262626` |
| ![#444444](https://img.shields.io/badge/-%23444444?style=flat-square&color=444444) | `highlight_med` | `#444444` |
| ![#585858](https://img.shields.io/badge/-%23585858?style=flat-square&color=585858) | `highlight_high` | `#585858` |
| | `none` | `NONE` |
