# Alfred-TXState-Paper

This is a Alfred 4 workflow simply transform url like
```
https://pubsonline.informs.org/doi/10.1287/mnsc.6.1.80
```
into url like
```
https://pubsonline-informs-org.libproxy.txstate.edu/doi/10.1287/mnsc.6.1.80
```
so that one can download a paper easily using the Texas State University Library proxy (login required).

# Getting Started
1. Install [Alfred 4](https://www.alfredapp.com/) (this workflow may also compatible with Alfred 3 and Alfred 2, not tested) with a [Powerpack](https://www.alfredapp.com/shop/) licence.
2. Download workflow source file form [release page](https://github.com/phguo/Alfred-TXState-Paper/releases) and double-click.
3. Click on "import" to import "TXState Paper" into your Alfred workflows.
4. Set a hotkey for url transformation, "⌘ Cmd + ↑ Shift + P" is recommended.

# Usage
- Using with Alfred hotkey - "⌘ Cmd + ↑ Shift + P".

![hotkey](https://raw.githubusercontent.com/phguo/Alfred-TXState-Paper/master/screenshots/hotkey.gif)

- Using with Alfred keyword - "paper".

![keyword](https://raw.githubusercontent.com/phguo/Alfred-TXState-Paper/master/screenshots/keyword.gif)

# Versioning
For the versions available, see [releases on this repository](https://github.com/phguo/Alfred-TXState-Paper/releases).

- [v1.1](https://github.com/phguo/Alfred-TXState-Paper/releases/tag/v1.1) released on May 4, 2020
    - (update) Using hotkey to transform current tab's URL.
    - (remove) Using hotkey to transform URL on clipboard.
- [v1.0](https://github.com/phguo/Alfred-TXState-Paper/releases/tag/v1.0) released on May 3, 2020
    - (feature) Using hotkey to transform URL on clipboard.
    - (feature) Using keyword "paper" to transform URL.

# TODO
- ✅Identify current tab.
- ❎Identify non-url input.
- ❎Identify not supported databases, supported databases can be found at this [menu](https://libproxy.txstate.edu/menu).

# License
This project is licensed under the MIT License, see the [LICENSE](https://github.com/phguo/Alfred-TXState-Paper/blob/master/LICENSE) file for details.

# Acknowledgments
Thanks for library resources provided by Texas State University during my visiting.
