![Preview](https://i.imgur.com/KZXS3HT.png)

# SAGBOT.com

This repository contains all the source code for the *Blog* part of the [**sagbot.com**](http://www.sagbot.com/) website. This website can be generated from the website generation tool [**Hugo**](https://gohugo.io/) and uses the theme [**Terminal**](https://themes.gohugo.io/themes/hugo-theme-terminal/) made by [**panr**](https://radoslawkoziel.pl/), with its **CSS** generation tool for this theme [**Terminal.css**](https://panr.github.io/terminal-css/).

## Dependency

- Hugo Extended >= v0.90.x.

## Obtaining and compiling

Retrieves all the code for this repository.

```bash
git clone --recurse-submodules https://github.com/Lurgrid/sagbot.com.git
```

Launches a test server (useful for development).

```bash
cd sagbot.com
hugo server
```

Used to compile the website.

```bash
cd sagbot.com
hugo
# Or
hugo -d /path/to/destination/
```

## License

Copyright © 2024-2024 E. HADDAG ([@lurgrid](https://github.com/Lurgrid/))

All this code is licensed under the GNU General Public License v3.0 (GPLv3), see [README](./README) for more information. This project uses the [**Terminal**](https://themes.gohugo.io/themes/hugo-theme-terminal/) theme which is licensed under the MIT license, [see for more information](https://github.com/panr/hugo-theme-terminal/blob/master/LICENSE.md).