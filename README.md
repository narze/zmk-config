# ZMK Config

Following this instruction https://zmk.dev/docs/user-setup#github-repo

## Building

For Aurora Lily58 in https://github.com/narze/zmk-config, run `make` in Devcontainer on [narze/zmk](https://github.com/narze/zmk), then copy them to each side in bootloader mode in this repo

```shell
cp ~/zmk-config/build/aurora_lily58_left.uf2 /Volumes/NICENANO/
cp ~/zmk-config/build/aurora_lily58_right.uf2 /Volumes/NICENANO/
```
