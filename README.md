# fastfetch-config

Minimalist [fastfetch](https://github.com/fastfetch-cli/fastfetch) configurations (`full-config.jsonc` and `minimal-config.jsonc`).

## Requirements

- [fastfetch](https://github.com/fastfetch-cli/fastfetch) (2.x+)
- A [Nerd Font](https://www.nerdfonts.com/) set in your terminal (for icons)

## Usage

1. Create the config directory if it doesn't exist:

   ```bash
   mkdir -p ~/.config/fastfetch
   ```

2. Move or copy the desired config (`full-config.jsonc` or `minimal-config.jsonc`) to `~/.config/fastfetch/` and rename it to `config.jsonc`.

3. *(Optional)* To use a custom logo file, set `"type": "file"`, uncomment `"source"` in the `logo` section, and enter the path to your logo.

4. Run `fastfetch`.
