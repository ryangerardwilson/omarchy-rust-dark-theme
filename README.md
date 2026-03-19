# rust-dark

A local Omarchy theme that pairs the rust family with a dark cocoa base and
warm copper accents.

This repository follows Omarchy's extra-theme layout:

- Theme files live at the repository root.
- Wallpapers live in `backgrounds/`.
- The repo name uses the `omarchy-<theme>-theme` pattern so
  `omarchy-theme-install` resolves the theme name correctly.

## Install

```bash
omarchy-theme-install https://github.com/ryangerardwilson/omarchy-rust-dark-theme.git
```

If you clone it manually:

```bash
git clone https://github.com/ryangerardwilson/omarchy-rust-dark-theme.git ~/.config/omarchy/themes/rust-dark
omarchy-theme-set rust-dark
```

## Included Overrides

- `colors.toml` for Omarchy-generated theme files
- `alacritty.toml`, `btop.theme`, `hyprland.conf`, `mako.ini`, and `tmux.conf`
  for the rust dark-mode UI treatment
- `rust-dark.tmTheme`, `neovim.lua`, `zathurarc`, and `swayimgrc` for editor
  and app alignment
- `icons.theme` and `vscode.json` for app-specific theme selection
- `wallpaper.txt`, `wallpaper.svg`, `preview.png`, and `backgrounds/0-rust-dark.png`
