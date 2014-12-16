angular-gettext-cli
===================

A command line interface for angular-gettext-tools

## Installation

`npm install angular-gettext-cli -g` for global using or
`npm install angular-gettext-cli --save-dev` for local.

## Usage:

`angular-gettext-cli --base ./app --match .html$ --dest ./extracted.pot`

## Parameters:
    *. --base - base path for search files
    *. --match - an regexp to specify files to process
    *. --dest - path to file to write extracted words.
