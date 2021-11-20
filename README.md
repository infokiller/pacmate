# Pacmate

A simple pacman wrapper that does 3 things:

- Checks Arch Linux news before running pacman
- Summarizes all warnings after running pacman
- Runs sudo on-demand, so that you can just run pacman and not think about
  whether you need sudo for what you're trying to do

## Requirements

All requirements are optional, but some features won't work without them.

- For printing warnings: one of {`wc`, `grep`, `python`} *AND* one of {`tail`,
  `sed`, `awk`}
- For printing news: one of {`yay`, `archnews`, `informant`}

## Configuration

TODO

## TODOs

- Document configuration options
- Add `PKGBUILD` and upload to AUR
- Consider adding other pacman utilities
