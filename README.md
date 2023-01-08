## What

A GitHub repo containing only assets/shell-integration/wezterm.sh from [wez/wezterm](https://github.com/wez/wezterm), generated with the following one-liner.

```sh
git log --pretty=email --patch-with-stat --reverse --full-index --binary -- assets/shell-integration/wezterm.sh | (cd ~/src/github.com/Riatre/wezterm-shell-integration; git am)
```

## Why

The Zsh plugin manager I use, [zgen](https://github.com/tarjoilija/zgen), clones the entire repo when asked to load a plugin from GitHub.
And wezterm is quite large even with `--depth=1`.
