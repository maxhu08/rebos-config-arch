# rebos-config-arch

This repo contains my rebos config for all my machines using arch.

## requirements

Make sure these are installed:

- git
- rust + cargo
- base-devel
- paru
- flatpak

```shell
sudo pacman -S git rust base-devel

# paru
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
cd ..
rm -rf paru

# flatpak
sudo pacman -S flatpak
```

## getting-started

```shell
## clone rebos config and gen current build
cargo install rebos
git clone https://github.com/maxhu08/rebos-config-arch ~/.config/rebos
rebos gen current build
```

That's it!
