# Uncategorized

## Rust

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

[Source](https://www.rust-lang.org/learn/get-started)

## VS Code

```sh
sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/yum.repos.d/vscode.repo'
dnf check-update
sudo dnf install code
```

[Source](https://code.visualstudio.com/docs/setup/linux#_rhel-fedora-and-centos-based-distributions)

# Starship Prompt

```sh
starship init bash
starship init fish
starship init zsh
mkdir ~/.config/starship/ && touch ~/.config/starship/starship.toml
export STARSHIP_CONFIG=~/.config/starship/starship.toml

# Essential for starship glyphs emoji etc
yay noto-fonts-emoji noto-fonts-extra
```
