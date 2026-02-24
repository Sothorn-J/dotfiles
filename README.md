# dotfiles

Personal configuration files for a Linux development environment.

## Structure

```
dotfiles/
├── brew/
│   └── Brewfile          # Homebrew package list
├── mise/
│   └── .config/mise/
│       └── config.toml   # mise tool versions
├── pip/
│   └── .config/pip/
│       └── pip.conf      # pip global config
└── zsh/
    └── .zshrc            # Zsh shell config
```

## Tools Managed

| Tool | Manager | Purpose |
|------|---------|---------|
| [mise](https://mise.jdx.dev) | Homebrew | Runtime version manager |
| [pixi](https://pixi.sh) | Homebrew | Conda-based package manager |
| [bat](https://github.com/sharkdp/bat) | mise | `cat` with syntax highlighting |
| [duckdb](https://duckdb.org) | mise | In-process analytical database |
| [fzf](https://github.com/junegunn/fzf) | mise | Fuzzy finder |
| [btop](https://github.com/aristocratos/btop) | mise | Resource monitor |
| [uv](https://github.com/astral-sh/uv) | mise | Fast Python package manager |
| [fastfetch](https://github.com/fastfetch-cli/fastfetch) | mise | System info display |
| [terraform](https://www.terraform.io) | mise | Infrastructure as code |
| [go](https://go.dev) | mise | Go language toolchain |
| [awscli](https://aws.amazon.com/cli/) | mise | AWS command-line interface |
| [node](https://nodejs.org) | mise | Node.js runtime |
| [gemini-cli](https://github.com/google-gemini/gemini-cli) | mise | Google Gemini AI CLI |
| [pre-commit](https://pre-commit.com) | mise | Git hook framework |

### Zsh plugins (installed manually to `~/.local/share/`)

- [zsh-autosuggestions](https://github.com/ziashamza/webui-aria2) — fish-style command suggestions
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) — syntax coloring in the prompt

### Prompt

- [Starship](https://starship.rs) — cross-shell prompt
