# Homebrew Tap for BigEdit

This is the official Homebrew tap for [bigedit](https://github.com/jopdorp/bigedit), a fast text editor for very large files.

## Installation

```bash
brew tap jopdorp/bigedit
brew install bigedit
```

## Requirements

- macOS
- [macFUSE](https://osxfuse.github.io/) (for FUSE features)

## Usage

```bash
bigedit <filename>
```

## Features

- Edit files larger than RAM
- Nano-like keybindings
- FUSE virtual filesystem - other programs can see your changes
- Journal-based saves for instant writes

## Keybindings

- `Ctrl+O` - Save (journal mode, instant)
- `Ctrl+J` - Compact (full file rewrite)
- `Ctrl+T` - Toggle FUSE mode
- `Ctrl+X` - Exit
- `Ctrl+G` - Help

## More Information

See the [main repository](https://github.com/jopdorp/bigedit) for more details.
