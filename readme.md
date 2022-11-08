<div align="center">
<h3>rofi-expressvpn</h3>
<img src="https://github.com/sigfriedcub1990/rofi-expressvpn/raw/master/.meta/rofi-expressvpn.gif">

`expressvpn` `rofi` `dmenu`

</div>

## What it does?

This extension allows you to:

1. List recommended (**default**) or **all** locations `ExpressVPN` provides.
1. Activate `ExpressVPN` from the widget.
1. Connect to other locations without manually disconnecting first.

I made this extension mainly for the third point and also because I'm a have `i3` user and I didn't like to use neither `ExpressVPN` CLI nor their browser extensions.

## Installation

Install from [AUR (rofi-expressvpn-git)](https://aur.archlinux.org/packages/rofi-expressvpn-git/), or:

1. Install dependencies: [rofi](https://github.com/davatorium/rofi), [expect](https://manned.org/expect) and gawk (this is probably installed already)
1. `git clone git@github.com:sigfriedcub1990/rofi-expressvpn.git`
1. `cd rofi-expressvpn`
1. `./rofi-expressvpn`
1. (Optional) For easy access, add the script somewhere in your `$PATH`.

### i3 keybinding

```
bindsym $mod+b exec --no-startup-id rofi-expressvpn
```

### Thanks for the inspiration!

- [bitwarden-rofi](https://github.com/mattydebie/bitwarden-rofi)
- [rofi-bluetooth](https://github.com/nickclyde/rofi-bluetooth/blob/master/README.md)

### Contributions

I made this tailored to my particular needs, I know it's far from perfect and I would appreciate any collaborations in order to improve the script.
