angular-gettext-cli
===================

A command line interface for angular-gettext-tools

## Installation

`npm install angular-gettext-cli -g` for global using or
`npm install angular-gettext-cli --save-dev` for local.

## Usage:

`angular-gettext-cli  --files "./app/*.+(js|html)" --dest ./extract.pot --marker-name i18n`

## Parameters:
    *. --files - an [glob](https://github.com/isaacs/node-glob) pattern to specify files to process
    *. --dest - path to file to write extracted words.
    *. --marker-name - a name of marker to search in js-files (see angular-gettext-tools)
