# Seiheki port for Alacritty

> An elegant colorscheme for a rusty terminal

## Install

Download the file `seiheki.yml` to somewhere you know, for example `$HOME/.config/alacritty/`.

```
wget https://raw.githubusercontent.com/delightfulagony/seiheki-alacritty/master/seiheki.yml -O $HOME/.config/alacritty/seiheki.yml 
```

Configure whether to use the light or the dark variant.

```
colors: *light
===
colors: *dark
```

Import the theme in your `alacritty.yml` config

```
import:
  - ~/.config/alacritty/seiheki.yml
```
