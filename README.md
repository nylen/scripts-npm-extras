# scripts-npm-extras

This package provides scripts that perform additional tasks related to `npm`
packages.

The scripts are packaged using `npm` for convenience.

## Installation

This module depends on [`json-align`](https://github.com/nylen/node-json-align)
as well, so you need to install it globally, because
[npm won't do it for you](https://github.com/isaacs/npm/issues/2949#issuecomment-11408461)
(to prevent possible dependency hell issues).

    sudo npm install -g scripts-npm-extras
    sudo npm install -g json-align

Similarly, to uninstall:

    sudo npm rm -g scripts-npm-extras
    sudo npm rm -g json-align

## Scripts

### npmi

`npmi` is a wrapper for `npm install` that will automatically add the given
packages to the `package.json` file, then re-indent it using
[`json-align`](https://github.com/nylen/node-json-align).

    # To install package abcde:
    npmi abcde

### More to come eventually!
