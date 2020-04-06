SublimeLinter-contrib-candran
================================

[![Build Status](https://travis-ci.org/SublimeLinter/SublimeLinter-contrib-cancheck.svg?branch=master)](https://travis-ci.org/SublimeLinter/SublimeLinter-contrib-cancheck)

This linter plugin for [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter) provides an interface to [cancheck](https://github.com/Reuh/candran). It will be used with files that have the “Candran” syntax.

## Installation
SublimeLinter must be installed in order to use this plugin. 

Please use [Package Control](https://packagecontrol.io) to install the linter plugin.

Before installing this plugin, you must ensure that `cancheck` (which is included with [Candran](https://github.com/Reuh/candran), and requires [luacheck](https://github.com/luarocks/luacheck) to be installed) is installed on your system.

In order for `cancheck` to be executed by SublimeLinter, you must ensure that its path is available to SublimeLinter. The docs cover [troubleshooting PATH configuration](http://sublimelinter.readthedocs.io/en/latest/troubleshooting.html#finding-a-linter-executable).

## Settings
- SublimeLinter settings: http://sublimelinter.readthedocs.org/en/latest/settings.html
- Linter settings: http://sublimelinter.readthedocs.org/en/latest/linter_settings.html
