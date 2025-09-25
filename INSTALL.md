# Install

- [fzf](https://github.com/junegunn/fzf)

## Setup the theme

### Dark Theme (Night Rain)

On Bash or Zsh, add the following to your `~/.bashrc`, `~/.zshrc` or another file loaded on your shell startup:

```sh
export FZF_DEFAULT_OPTS=' --color=fg:#f8f8f2,bg:#32324b,hl:#8be9fd --color=fg+:#f8f8f2,bg+:#616175,hl+:#f1fa8c --color=info:#8be9fd,prompt:#a8ffde,pointer:#f1fa8c --color=marker:#8be9fd,spinner:#8be9fd,header:#ff5555'
```

On Fish, add the following to your `~/.config/fish/config.fish` or run the following one time:

```sh
set -Ux FZF_DEFAULT_OPTS ' --color=fg:#f8f8f2,bg:#32324b,hl:#8be9fd --color=fg+:#f8f8f2,bg+:#616175,hl+:#f1fa8c --color=info:#8be9fd,prompt:#a8ffde,pointer:#f1fa8c --color=marker:#8be9fd,spinner:#8be9fd,header:#ff5555'
```

### Light Theme (Day Rain)

On Bash or Zsh, add the following to your `~/.bashrc`, `~/.zshrc` or another file loaded on your shell startup:

```sh
export FZF_DEFAULT_OPTS=' --color=fg:#1f2328,bg:#fafbfc,hl:#0366d6 --color=fg+:#1f2328,bg+:#e1e4e8,hl+:#ff841f --color=info:#0366d6,prompt:#28A745,pointer:#ff841f --color=marker:#0366d6,spinner:#0366d6,header:#d73a49'
```

On Fish, add the following to your `~/.config/fish/config.fish` or run the following one time:

```sh
set -Ux FZF_DEFAULT_OPTS ' --color=fg:#1f2328,bg:#fafbfc,hl:#0366d6 --color=fg+:#1f2328,bg+:#e1e4e8,hl+:#ff841f --color=info:#0366d6,prompt:#28A745,pointer:#ff841f --color=marker:#0366d6,spinner:#0366d6,header:#d73a49'
```
