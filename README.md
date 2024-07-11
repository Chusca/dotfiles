# dotfiles

This repo contains the configuration to replicate my setup using [Chezmoi](https://chezmoi.io).

This setup only supports Ubuntu OS.

## How to run

```bash
sh -c "$(curl -fsLS get.chezmoi.io/lb)" -- init --apply chusca/dotfiles
```
> [!NOTE]
> In case `curl` is not installed, you can use `wget` instead:
> ```bash
> sh -c "$(wget -qO- get.chezmoi.io/lb)" -- init --apply chusca/dotfiles
> ```
