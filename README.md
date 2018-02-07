# auto-type

A small python program that types a long string. Useful for programs or web
consoles that don't allow copy and paste.

## Requirements

- Python 3
- xdotool (http://www.semicomplete.com/projects/xdotool/)

## Installation

First, follow the instructions to install xdotool.
Then copy or symlink the file to your local bin folder, or just execute it directly.
On Ubuntu, your local executable folder for scripts is usually `~/bin`.

## Usage

`auto-type "your string goes here"`

Note: The program will wait 3 seconds to give you time to alt-tab into the
window you wish the input to go to.
