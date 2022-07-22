# asdf-bun

[Bun](https://bun.sh/) plugin for asdf version manager

## Prerequirements

- Make sure you have the required dependencies installed:
  - curl
  - git
  - unzip

## Installation

```bash
asdf plugin-add bun https://github.com/BurntCaramel/asdf-bun.git

# Now you can manage bun through asdf:
asdf list all bun
asdf install bun latest
asdf install bun 0.1.4 # Install multiple versions at once
asdf install bun 0.1.3 # Install multiple versions at once
asdf global bun latest

# Now bun is installed!
bun --version
bun help
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions.

## License

Licensed under the
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
