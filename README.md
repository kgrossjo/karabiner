# Personal Karabiner Elements Configuration

This `karabiner.json` contains two profiles, the default is derived from
SpaceFN and the Caps lock cursor profile is new.

## Default profile (similar to SpaceFN)

The starting point for this profile is
[SpaceFN](https://ke-complex-modifications.pqrs.org/#spacefn).  The idea is
that tapping the space bar allows it to work normally, as space.  Holding down
the space bar (like a modifier key, similar to Shift and Ctrl) allows it to
act as a modifier key.

Mucho kudos to [Ergoemacs mode](https://ke-complex-modifications.pqrs.org/#ergoemacs_mode)
who provides something similar, but the settings are more refined to avoid
false triggers.

With the standard settings, typing space followed by a letter very quickly
could falsely trigger the SpaceFN binding for that letter.

False triggers are avoided by requiring the space bar to be held down for at
least 100ms before it starts to act as a modifier.

Also, this profile modifies CapsLock to act as Ctrl when held down and to act
as Escape when typed alone.  (I don't need CapsLock itself.)

Keybindings (all with space held down):

* `s` - space.  This allows keyboard repeat.
* `g` - escape.
* `a` - cmd-left (beginning of line)
* `e` - cmd-right (end of line)
* `h` - left (from vi)
* `j` - down (from vi)
* `k` - up (from vi)
* `l` - right (from vi)
* `b` - left (from emacs)
* `f` - right (from emacs)
* `w` - option-right (go word right, from vi)
* `q` - option-left (go word left)
  b from vi is already taken, and q is left of w
* `x` - delete forward (delete character, from vi)
* `d` - option-delete forward (delete word)
* `m` - return (from ctrl-m)
* `p` - page up
* `n` - page down
* `u` - home
* `o` - end
* `1` through `0` - f1 through f10
* `-` - f11 (right of 0)
* `=` - f12 (right of minus)