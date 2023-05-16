# Elune theme

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-green.svg)](https://www.gnu.org/licenses/gpl-3.0)

## About
Elune is a dark theme inspired by visual studio dark color scheme, it
is modified for making it more readable.

![elune-theme](https://user-images.githubusercontent.com/53369750/238607312-4207a62a-a289-46ab-813e-2b2bb750c5f3.png)

## Installation

### Manual

Download `elune-theme.el` to the directory `~/.emacs.d/themes/` and add this
to your `.emacs` or `init.el`

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
```
If you want to load it by default you can add this line to your init file
```lisp
(load-theme 'elune)
```

### Package.el

elune is avaliable on MELPA, you can install it with
`M-x package-install elune-theme`

If you cannot find the package try `M-x package-refresh-contents`
