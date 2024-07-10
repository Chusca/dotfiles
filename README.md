# dotfiles

This repo contains the configuration to replicate my setup using [Chezmoi](https://chezmoi.io).

This setup only supports Ubuntu OS.

## How to run

```shell
export GITHUB_USERNAME=chusca
sh -c "$(curl -fsLS get.chezmoi.io/lb)" -- init --apply $GITHUB_USERNAME
```
