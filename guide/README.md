# Paths to Nix

**About Flakes:** The Nix world is in an ongoing ad long-lasting transition process from a channel-based mechanism toward the flake system. As flakes provider better reproducibility and are more verbose at the same time, we recommend to use flakes wherever you can, and right from the beginning of your journey. How flakes can be enabled is described in the [wiki entry on flakes](https://nixos.wiki/wiki/Flakes).

## Nix, the package manager

### Installation

- [Determinate Systems Nix Installer](https://github.com/DeterminateSystems/nix-installer) is what we would recommend to install Nix on another Linux distribution.

### Nix language & packaging

- [Nix Pills](https://nixos.org/guides/nix-pills/) is a great tutorial series that explain essential concepts of Nix and of packaging software with Nix. It also has an introduction to the Nix language.
- [Package existing software - nix.dev](https://nix.dev/) is a tutorial that guides you through packaging a C/C++ program.
- [Nix - A One Pager](https://github.com/tazjin/nix-1p) everything short and on one page, in case you are in a hurry.

## NixOS

### Installation

- [NixOS manual](https://nixos.org/manual/nixos/stable/#sec-installation) provides instructions how to install NixOS from an installer medium.

### Starter configuration

- [Nix Starter Config](https://github.com/Misterio77/nix-starter-configs) is an inofficial repo with some NixOS configurations you could start from.

## References

Sometimes, it isn't easy to fine what you are looking for. Here are some tips that might help:

- [search.nixos.org](https://search.nixos.org/packages) lets you search for packages and NixOS options.
- [Nix manual](https://nixos.org/manual/nix/stable/) documents all the commands and options of Nix and everything related to the nix CLI.
- [Nixpkgs manual](https://nixos.org/manual/nixpkgs/unstable/) is what you should read if you don't know how to package something.
- [NixOS manual](https://nixos.org/manual/nixos/unstable/) documents how to install and maintain a NixOS installation, and covers many topics of system configuration.
- [GitHub search](https://github.com/search?q=zramSwap.enable+language%3ANix&type=code&l=Nix) lets you search the Nix code and configuration of other people.
- [NixOS wiki](https://nixos.wiki/) has many helpful articles to specific topics, for example the [NixOS boot process](https://nixos.wiki/wiki/Bootloader)

## Get the concepts

- [Recommended reading - nix.dev](https://nix.dev/recommended-reading) lists some essential articles and videos.
- [Zero to Nix](https://zero-to-nix.com/) articles on Nix concepts, with a focus on flakes.
