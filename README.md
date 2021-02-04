# Gruvbox color theme configuration for Tmux

This theme is a fork of [tmux-gruvbox].

Screenshots:

| Dark theme | Light theme |
|---|---|
| TODO | TODO |

## Installation

### Install manually

The simplest way is just:

> HINT: Always make a backup of your config files before any action.

```bash
cat tmux-gruvbox-dark.conf >> ~/.tmux.conf
```

### Install through [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

Add plugin to the list of TPM plugins in `.tmux.conf` and select desired theme

```bash
set -g @plugin 'ctong94/tmux-gruvbox'
set -g @tmux-gruvbox 'dark' # or 'light'
```

Hit `prefix + I` to fetch the plugin and source it. Your Tmux should be updated with the theme at this point.

## License

GPLv3 - Maciej Sypień

[tmux-gruvbox]: https://github.com/egel/tmux-gruvbox
