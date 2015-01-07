Solarized color scheme for [taskwarrior](http://taskwarrior.org/).  See the [Solarized homepage](http://ethanschoonover.com/solarized) for the main project and themes for other applications.

Requirements
============

This theme depends on `.Xresources` having color definitions from the main solarized repo: https://github.com/altercation/solarized/blob/master/xresources/solarized

Installing
==========

To use, just include the theme file in your `~/.taskrc`:

```
include /path/to/solarized-16.theme
```

Unlike most other apps, there is little need for separate light/dark themes with taskwarrior. Since it is largely non-interactive, output is printed to the terminal which should already have one of the solarized themes applied to it.  In fact, this theme is as much for removing default taskwarrior colors as it is for replacing them.


