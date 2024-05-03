# Clip-path

## Getting Started

Using LazyVim

```lua
return {
  {
    "Ryutaro95/clip-path",
    keys = {
      {
        "cp",
        function()
          require("clip-path").copy_relative_file_path()
        end,
      },
    },
  }
}

```
