# TODO

## General

* Decide for a build system (meson vs CMake).
* Rename prev/next to arrowhead-left/right? Add arrowhead-up/dpwn? (Check naming conventions.)

## Cinnamon

* Make assets configurable with an accent color.
* Share some assets (checkboxes, switches, radio buttons) with GTK theme.
* Understand 'selected'/normal vs 'focused', 'active', ...

## Icon theme (Papirus)

* Include or reference? (submodule?)
* Make the theme configurable (the accent color for folders) from the build system.

## Notes

* Symbolic icons can be recolored in GTK (file name must end with `-symbolic.NNN`):
  <https://stackoverflow.com/questions/57809783/how-to-use-the-text-color-from-the-system-wide-gtk-theme-for-svg-icons-gtkimage>
* Documentation for CSS properties in [GTK3](https://docs.gtk.org/gtk3/index.html) and
  [GTK4](https://docs.gtk.org/gtk4/index.html).
