# h4xt3rm

A neon green-on-black terminal theme with colorful accents, for a futuristic aesthetic.

![h4xt3rm Preview](preview.png)

---

## Installation

### iTerm2 (Recommended)

1. Open **iTerm2 → Settings → Profiles → Colors**
2. Click the **Color Presets...** dropdown
3. Select **Import...**
4. Choose `h4xt3rm.itermcolors`
5. Select **h4xt3rm** from the Color Presets list

### Terminal.app

1. Open **Terminal → Settings → Profiles**
2. Click the **齿轮** button → **Import...**
3. Choose `h4xt3rm.terminal`
4. Select **h4xt3rm** from the Profiles list

### Alacritty

Add to your `alacritty.yml`:

```yaml
import:
  - h4xt3rm.alacritty.yml
```

Or copy the contents into your colors section.

### WezTerm

Add to your `wezterm.lua`:

```lua
local wezterm = require 'wezterm'
local config = {}
if wezterm.config_builder then
  config = wezterm.config_builder()
end
config.colors = require 'h4xt3rm.wezterm'
return config
```

### Kitty

Copy `h4xt3rm.kitty` to `~/.config/kitty/h4xt3rm.conf` and add to your `kitty.conf`:

```
include h4xt3rm.kitty
```

---

## Color Palette

| Name | Hex | Sample |
|------|-----|--------|
| Background | `#050D09` | <span style="background-color: #050D09; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Foreground | `#69F097` | <span style="background-color: #69F097; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Cursor | `#75F2C0` | <span style="background-color: #75F2C0; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Selection | `#ADFFCC` | <span style="background-color: #ADFFCC; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Black (Ansi 0) | `#000000` | <span style="background-color: #000000; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Red (Ansi 1) | `#FF6ECD` | <span style="background-color: #FF6ECD; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Green (Ansi 2) | `#73F6B2` | <span style="background-color: #73F6B2; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Yellow (Ansi 3) | `#63FF7B` | <span style="background-color: #63FF7B; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Blue (Ansi 4) | `#50FF91` | <span style="background-color: #50FF91; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Magenta (Ansi 5) | `#C27DFF` | <span style="background-color: #C27DFF; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Cyan (Ansi 6) | `#79FFF5` | <span style="background-color: #79FFF5; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| White (Ansi 7) | `#C3FFBA` | <span style="background-color: #C3FFBA; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright Black (Ansi 8) | `#000000` | <span style="background-color: #000000; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright Red (Ansi 9) | `#F090A4` | <span style="background-color: #F090A4; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright Green (Ansi 10) | `#75F2C0` | <span style="background-color: #75F2C0; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright Yellow (Ansi 11) | `#C3FC95` | <span style="background-color: #C3FC95; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright Blue (Ansi 12) | `#60C8F8` | <span style="background-color: #60C8F8; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright Magenta (Ansi 13) | `#DDB0F8` | <span style="background-color: #DDB0F8; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright Cyan (Ansi 14) | `#A6D6FC` | <span style="background-color: #A6D6FC; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |
| Bright White (Ansi 15) | `#FFFFFF` | <span style="background-color: #FFFFFF; width: 20px; height: 20px; display: inline-block;">&nbsp;</span> |

---

## Files

| File | Description |
|------|-------------|
| `h4xt3rm.itermcolors` | iTerm2 color scheme |
| `h4xt3rm.terminal` | Apple Terminal color scheme |
| `h4xt3rm.alacritty.yml` | Alacritty color scheme |
| `h4xt3rm.wezterm.lua` | WezTerm color scheme |
| `h4xt3rm.kitty` | Kitty color scheme |
| `h4xt3rm.json` | Universal JSON (importable) |

---

## License

MIT License
