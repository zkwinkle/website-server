# NixOS server for my [website](https://github.com/zkwinkle/website)

This repo contains the configuration files that I use in my NixOS server
to host my [website](https://github.com/zkwinkle/website-server).

## Cloning

```sh
git clone --recurse-submodules https://github.com/zkwinkle/website-server.git
```

## Install configuration remotely

```sh
nixos-rebuild switch --flake 'git+https:github.com/zkwinkle/website-server?submodules=1#website-server --no-write-lock-file'
```
