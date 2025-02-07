[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JCS-ELPA](https://raw.githubusercontent.com/jcs-emacs/badges/master/elpa/v/echo-bar.svg)](https://jcs-emacs.github.io/jcs-elpa/#/echo-bar)

# echo-bar.el
> Display a custom status at the end of the echo area

[![CI](https://github.com/elp-revive/echo-bar.el/actions/workflows/test.yml/badge.svg)](https://github.com/elp-revive/echo-bar.el/actions/workflows/test.yml)

## Customization

The format of the echo bar can be set using the `echo-bar-format` variable. This variable uses the same format as `mode-line-format`.

Alternatively, you can set `echo-bar-function` to a custom function to be run every time the echo bar updates, and the output of this function will be used as the contents of the echo bar.

## Screenshots

Displayed at the end of the echo area

![](./screenshots/echo-area-example.png)

It will also be displayed at the end of the minibuffer

![](./screenshots/minibuffer-example.png)
