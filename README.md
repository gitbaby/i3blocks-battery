# i3blocks-battery
A battery status blocklet script for i3blocks.

Inspired by https://github.com/gportay/i3blocks-status#battery

# Installation

To use with i3blocks, clone this repository:

```
git clone https://github.com/gitbaby/i3blocks-battery.git ~/.config/i3blocks/i3blocks-battery
```

Add the following lines into your ~/.config/i3blocks/config file:

```INI
[battery]
command=~/.config/i3blocks/i3blocks-battery/battery 0
interval=30

[battery]
command=~/.config/i3blocks/i3blocks-battery/battery 1
interval=30
```
