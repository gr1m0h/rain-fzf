# Install

- [fzf](https://github.com/junegunn/fzf)

## Setup the theme

### Dark Theme (Night Rain)

On Bash or Zsh, add the following to your `~/.bashrc`, `~/.zshrc` or another file loaded on your shell startup:

```sh
export FZF_DEFAULT_OPTS=' --color=fg:#f8f8f2,bg:#32324b,hl:#8be9fd --color=fg+:#f8f8f2,bg+:#616175,hl+:#8be9fd --color=info:#8be9fd,prompt:#a8ffde,pointer:#f1fa8c --color=marker:#f1fa8c,spinner:#8be9fd,header:#a8ffde'
```

On Fish, add the following to your `~/.config/fish/config.fish` or run the following one time:

```sh
set -Ux FZF_DEFAULT_OPTS ' --color=fg:#f8f8f2,bg:#32324b,hl:#8be9fd --color=fg+:#f8f8f2,bg+:#616175,hl+:#8be9fd --color=info:#8be9fd,prompt:#a8ffde,pointer:#f1fa8c --color=marker:#f1fa8c,spinner:#8be9fd,header:#a8ffde'
```

### Light Theme (Day Rain)

On Bash or Zsh, add the following to your `~/.bashrc`, `~/.zshrc` or another file loaded on your shell startup:

```sh
export FZF_DEFAULT_OPTS=' --color=fg:#1f2328,bg:#fafbfc,hl:#0366d6 --color=fg+:#1f2328,bg+:#e1e4e8,hl+:#0366d6 --color=info:#0366d6,prompt:#28a745,pointer:#b08800 --color=marker:#b08800,spinner:#0366d6,header:#28a745'
```

On Fish, add the following to your `~/.config/fish/config.fish` or run the following one time:

```sh
set -Ux FZF_DEFAULT_OPTS ' --color=fg:#1f2328,bg:#fafbfc,hl:#0366d6 --color=fg+:#1f2328,bg+:#e1e4e8,hl+:#0366d6 --color=info:#0366d6,prompt:#28a745,pointer:#b08800 --color=marker:#b08800,spinner:#0366d6,header:#28a745'
```
