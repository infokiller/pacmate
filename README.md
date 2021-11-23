# Pacmate

A simple pacman wrapper that does 3 things:

- Checks Arch Linux news before running pacman
- Summarizes all warnings after running pacman
- Runs sudo on-demand, so that you can just run pacman and not think about
  whether you need sudo for what you're trying to do

## Requirements

The only hard requirement is `pacman` and `bash` (which is included in
`pacman`).

All the requirements below are optional, but some features won't work without
them.

- For printing warnings: one of {`wc`, `grep`, `python`} _AND_ one of {`tail`,
  `sed`, `awk`}
- For printing news: one of {`yay`, `archnews`, `informant`}

## Configuration

TODO

## TODOs

- Add config file
- Add `PACMATE_CONFIG_FILE` variable to control config file path (can be used
  for per-machine config, although bash control flow can also be used for that)
- Add ignore regexes for warnings as a config option
- Add `PKGBUILD` and upload to AUR
- Document configuration options
- Consider adding other pacman utilities
- Add tests and CI
