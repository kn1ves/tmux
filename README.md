# tmux

My tmux config — C-Space prefix, vi copy-mode, Aura theme.

## Highlights

- Prefix remapped to `C-Space` (with `send-prefix` passthrough)
- vi mode keys: `v` = begin selection, `y` = copy
- 1-based window and pane indexes, windows renumber automatically
- Lag fixes: `tmux-256color` terminfo, true color (`Tc`), `escape-time 0`, `focus-events on`
- Aura theme matching my nvim: black status bar, purple `#a277ff` accents, powerline pills, fading-purple pane borders and copy-mode selection
- Status bar extras: orange `PREFIX` / green `COPY` mode indicators, orange pill for zoomed windows, red for ringing bells, pane numbers drawn in borders

## Install

```
git clone https://github.com/kn1ves/tmux ~/tmux
ln -s ~/tmux/tmux.conf ~/.tmux.conf
tmux source-file ~/.tmux.conf
```

Requires tmux >= 3.2 and a Nerd Font for the powerline glyphs.
