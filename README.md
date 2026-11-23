# tile

`tile` arranges all visible Terminal windows on macOS in a grid that fills the screen.

## Usage

```sh
tile      # grid with an automatic number of columns
tile 3    # grid with 3 columns
```

All windows have the same size. If the last row has fewer windows, the space at the right of that row stays empty. Minimized windows do not change.

## Install

```sh
ln -s "$PWD/tile" ~/.local/bin/tile
```

Make sure that `~/.local/bin` is in your `PATH`.

## Requirements

- macOS with Apple Terminal.
- The first time you run `tile`, macOS asks for permission to control Terminal. Allow it.
