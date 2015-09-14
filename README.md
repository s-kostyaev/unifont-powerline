# What
It is a patched version of gnu unifont. Powerline symbols was added
and some symbols was changed. Currently changed symbols is `0`, `{` and `}`.
![unifont-powerline](https://cloud.githubusercontent.com/assets/8576745/9845808/3897cac8-5ae7-11e5-8d7d-6311aa0916db.png)


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
