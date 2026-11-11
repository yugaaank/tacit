# Tacit

Wallpaper-dependent, glass-mode desktop shell. This repository contains the Zed editor theme integration.

## Zed Theme

See `zed/README.md` for the Zed editor theme that follows Tacit's matugen palette and transparency modes.

### Quick install

```bash
cd zed
./install.sh
# Restart Zed
```

### What it provides

- `Tacit.json` theme regenerated from Tacit's wallpaper colors on every change
- Zenburn transparency (blurred + 8-digit RGBA) across solid / frosted / clear modes
- All editor, terminal, panel, and tab backgrounds share one color per mode
- systemd user watcher — no root, polls mtime every 5s
