# Installing Zed Tacit Theme (standalone, outside Tacit OS)

If you are installing Tacit OS, this integration is included automatically.
If you just want the Zed theme on an existing system:

## Prerequisites

- `jq` (JSON processor)
- `bash`
- `systemd` user instance
- Zed editor installed
- Tacit's matugen colors at `~/.local/state/quickshell/user/generated/colors.json`
- Tacit's transparency config at `~/.config/illogical-impulse/config.json`

## Steps

```bash
# Clone or copy this repository
git clone <tacit-repo> ~/Projects/tacit
cd ~/Projects/tacit/zed

# Install
./install.sh

# Restart Zed
```

The theme auto-generates on first install and watches for wallpaper/transparency changes thereafter.

## Manual theme generation

If you don't want the watcher, run the generator manually whenever you change wallpaper:

```bash
~/.config/zed/scripts/zed-tacit-theme.sh
```

Then restart Zed.
