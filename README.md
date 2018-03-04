# dotfiles

An i3 window manager setup from 2018.

> Archived. No longer maintained.

Everything lives under `.config/i3/`:

- `config`: the i3 config (keybindings with Super as the modifier, dmenu launcher, floating-window rules, startup apps, a power menu mode and a gaps mode, which needs i3-gaps on older i3)
- `start-conky-i3statusbar.sh` and `conky-i3statusbar`: feed the i3bar status line from conky
- `compton.conf`: compositor settings (the i3 config does not start compton itself)
- `scripts/i3exit.sh`: lock, log out, suspend, hibernate, reboot and shut down, used by the power menu

To use it, copy `.config/i3/` to `~/.config/i3/`. Read the files first; they assume tools such as conky, dmenu, i3lock, numlockx, pasystray, variety and terminator are installed.

## Credits

`conky-i3statusbar` and `compton.conf` are adapted from Erik Dubois's i3 configs; the conky file's header says it is distributed under the GNU GPL version 2 or later.

## License

GPL-2.0-or-later ([LICENSE](LICENSE)). The i3 config, `conky-i3statusbar` and `compton.conf` are adapted from [Erik Dubois](https://github.com/erikdubois)'s i3 configs, which are licensed GPL-2.0-or-later.
