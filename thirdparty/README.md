# Thirdparty Color Profiles

Here are some config files for other tools to match with the nvim fluoromachine
theme. The configurations are designed to match with the base theme, with the
following configuration / adjustments:

```.lua
 {
  "maxmx03/fluoromachine.nvim",
  lazy = false,
  priority = 1000,
  opts = {
   glow = true,
   transparent = true,
   theme = "fluoromachine",
   colors = {
    fg = "#BFFFFF",
    comment = "#8298FF",
    editor = {
     selection = "#F010A0",
    },
   },
  },
 },
```

## kitty

The theme can be placed into the kitty config directory and loaded via

```.conf
include fluoromachine.conf
tab_bar_style custom
```

## tmux

The configuration can be copied into the tmux config file or loaded via

```.conf
source-file ~/.tmux/fluoromachine.conf
```

## zsh-powerlevel10k prompt

The powerlevel10k prompt config file is very extensive, copy the provided file
and customize it.
