# Dotfiles by pokeballstore

Welcome to my dotfiles repository! This repository contains configuration files for various tools and software that I use daily. These dotfiles are designed to set up and customize your development environment quickly and efficiently.

## Features

This repository includes configurations for the following tools:

- **Zsh**: Personalized `.zshrc` for an enhanced shell experience, including aliases and plugins.
- **Neovim**: A modern and fast configuration based on LazyVim, featuring:
  - Custom key mappings.
  - Plugin management with Lazy.nvim.
  - Preconfigured options for productivity.
- **Ghostty Terminal**: Custom terminal settings for a sleek and functional workflow.
- **tmux**: A `.tmux.conf` file for better terminal multiplexing.
- **VS Code**: Essential settings for a consistent development environment.
- **Docker**: Configuration for containerized workflows.

## Preview

### Folder Structure
```
dotfiles/
├── .zshrc                  # Zsh shell configuration
├── .tmux.conf              # Tmux configuration
├── ghostty/config          # Ghostty terminal settings
├── nvim/                   # Neovim configuration
│   ├── init.lua            # Main Neovim configuration
│   ├── lua/                # Custom Lua modules
│   │   ├── config/         # Neovim configurations
│   │   ├── plugins/        # Plugin settings
│   ├── README.md           # Neovim-specific documentation
│   └── stylua.toml         # Style configuration for Lua
└── vscode/                 # VS Code settings
    └── User/
        ├── settings.json   # User settings
        └── workspaceStorage/ # Workspace-specific configurations
```

## Installation

### Prerequisites

- **Git**: Ensure Git is installed on your system.
- **Zsh**: Install Zsh and optionally Oh My Zsh.
- **Neovim**: Install Neovim 0.8 or higher.
- **tmux**: Install tmux for terminal multiplexing.
- **VS Code**: Install Visual Studio Code for development.

### Clone and Install

Clone this repository to your home directory:

```bash
git clone https://github.com/pokeballstore/dotfiles.git ~/dotfiles
```

Navigate to the directory:

```bash
cd ~/dotfiles
```

Run the setup script to back up existing configuration files and link the new ones:

```bash
./setup_and_upload.sh
```

Restart your terminal to apply the new configurations.

## Customization

Feel free to customize these dotfiles to suit your needs. Each configuration file includes comments to guide you in making changes.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

## License

This repository is licensed under the MIT License.

## Author

Created and maintained by pokeballstore.


