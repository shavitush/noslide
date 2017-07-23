### Build status
[![Build status](https://travis-ci.org/shavitush/noslide.svg?branch=master)](https://travis-ci.org/shavitush/noslide)

[Download](https://github.com/shavitush/noslide/releases)

# noslide
This plugin allows players to not slide after landing while bhopping.  
It's intended to be used on easybhop styles (autobhop included).

Video demonstration: https://www.youtube.com/watch?v=vnxW4QMl0E8

# Installation
1. Drag and drop the `noslide.smx` file to your `addons/sourcemod/plugins/` folder.
2. Load the plugin (`sm plugins load noslide` via the server's console), restart the server or change maps.
3. Add `noslide_enabled 1` to map-configs where you want the plugin enabled, such as "bhop_badges2" or similar maps. Alternatively, navigate to `cfg/sourcemod/plugin.noslide.cfg` and switch it to 1 in order to have the plugin running for every map.

# Usage
* `sm_noslide`, `sm_kzmode` or `sm_kz` will toggle noslide. It's disabled by default.

# Optional requirements:
* [shavit's simple bhop timer](https://github.com/shavitush/bhoptimer) - having `bhoptimer` installed will force this plugin to only work for styles with easybhop disabled, such as easy-scroll or autobhop.
