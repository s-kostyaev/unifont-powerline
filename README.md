# What
It is a patched for powerline version of gnu unifont
![unifont-powerline](https://cloud.githubusercontent.com/assets/8576745/9835984/7432bab2-5a1e-11e5-9d03-2b8406a330ba.png)

# Usage

```bash
git clone https://github.com/s-kostyaev/unifont-powerline ~/.fonts
```

In `~/.xinitrc`:

```bash
xset fp+ ~/.fonts
xset fp rehash
```

In `~/.Xresources`:

```
URxvt.font: -gnu-unifont-medium-r-normal-sans-16-160-75-75-c-80-iso10646-1
```
