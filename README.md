# File Filter Plugin for Sublime Text


## Overview
This plugin allows you to filter file content using regular expressions (RegExp). It provides functionality match text, highlight matches and fold content around matches.

### Features

- File Filtering with RegExp: Matches text 
  - Filter content based on custom or predefined regular expressions
  - Supports both single-line and multiline matching.
- Flexible Text Folding Options
  - Adjust how content is collapsed around matches for better readability
- Customizable Highlighting Styles
    - Highlight matched regions using various styles to visually distinguish them.


### Installation

1. From `Command Palette`, run `Package Control: Install Package` command.
2. In opened packages list, find `FileFilter` package and install it

### Filter File command

1. From `Command Palette`, run `vsc : Filter File` command.
2. Select     - Select one of the options    - `prompt` for a new/custom RegExp (RegExp may be multi-line)3. File is now filter
### Folding Type command

Adjust how content is collapsed around matches for better readability

1. From `Command Palette`, run `vsc : Filter File : Folding Style` command.

### Highlight Type command

Adjust how matched text is highlighted

1. From `Command Palette`, run `vsc : Filter File : Highlight Style` command.