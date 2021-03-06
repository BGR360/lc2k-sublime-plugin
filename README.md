# LC-2K Sublime Text Plugin

LC-2K syntax highlighting and autocompletion for Sublime Text 3

## Intro

The LC-2K is the "Little Computer 2K" architecture for a computer. 
The LC-2K ISA supports 8 basic instructions and allows for full functionality of a computer.

The LC-2K ISA is used by students of the "EECS 370: Computer Architecture" course at
the University of Michigan. Students also learn the popular [MIPS](https://en.wikipedia.org/wiki/MIPS_instruction_set) ISA.

There is already a [Sublime Text Plugin for the MIPS ISA](https://github.com/contradictioned/mips-syntax),
but not for LC-2K. So I decided to make one.

## Planned Features

[Make a suggestion!](https://github.com/BGR360/lc2k-sublime-plugin/issues)

- [x] Syntax Highlighting
- [x] Instruction Autocompletion
- [ ] LC-2K Quick-Reference

## Installation

**Note: This plugin has only been tested on [Sublime Text 3](https://www.sublimetext.com/3)**

### Package Control (Recommended)

Install [PackageControl](https://packagecontrol.io/installation).
Then open the command palette (default keybinding: `Ctl+Shift+P` or `Cmd+Shift+P`), select `Package Control: Install Package` and choose `LC-2K Assembly`.

### Manual (Not Recommended)

[Download the repo as a ZIP file](https://github.com/BGR360/lc2k-sublime-plugin/releases/latest) and extract it to Sublime's Package Directory:

**Linux:** `~/.config/sublime-text-3/Packages/User/LC-2K Assembly/`

**OS X:** `/Users/<you>/Library/Application Support/Sublime Text 3/Packages/User/LC-2K Assembly/`

**Windows:** `AppData\Roaming\Sublime Text 3\Packages\LC-2K Assembly\`

## Features

### Syntax Highlighting

Shown on a variety of color schemes:

<img src="http://gifyu.com/images/output_hXUEOh.gif" width="700">

### Autocompletion

<img src="https://i.gyazo.com/1b4b9a66c5a509d580dcbbac291e7b35.gif" width="600">
