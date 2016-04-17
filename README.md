# scripts-npm-extras

This package provides scripts that perform additional tasks related to `npm`
packages.

The scripts are packaged using `npm` for convenience.

## Installation

To install:

    sudo npm install -g scripts-npm-extras

Similarly, to uninstall:

    sudo npm rm -g scripts-npm-extras

## Scripts

### npmi

`npmi` is a wrapper for `npm install` that will automatically add the given
packages to the `package.json` file, then re-indent it using
[`json-align`](https://github.com/nylen/node-json-align).

    # To install package abcde:
    npmi abcde

### More to come eventually!
