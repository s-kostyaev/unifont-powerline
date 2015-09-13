# What
It is a patched for powerline version of gnu unifont

# Usage

```bash
git clone https://github.com/s-kostyaev/unifont-powerline ~/.fonts
```

In `~/.xinitrc`:

```bash
xset fp+ ~/.fonts
xset fp rehash
```

In ~/.Xresources`:

```
URxvt.font: -gnu-unifont-medium-r-normal-sans-16-160-75-75-c-80-iso10646-1
```
