# NVM - Node Version Manager

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-nvm.svg?label=Release)](https://github.com/zmicro-design/plugin-nvm/tags)
[![Build Status](https://github.com/zmicro-design/plugin-nvm/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-nvm/actions/workflows/ci.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-nvm.svg)](https://github.com/zmicro-design/plugin-nvm/issues)

## Installation

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zcorky/znvm/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zcorky/znvm/master/install | bash
```

## Usage

```markdown
Node Version Manager (v1.0.4)

Node Version Manager is a tool for managing multiple Go versions.

Usage:
  znvm install <version>   - Install Node version
  znvm use <version>       - Use Node version
  znvm remove <version>    - Remove Node version
  znvm ls                  - List the Go versions installed
  znvm ls-remote           - List all Go versions from remote
  znvm current             - Show current Node version
  znvm exec                - Enter new shell with node -v for tmp
  znvm help                - Show help

Example:
  znvm install v16.14.2
  znvm use v16.14.2
  znvm remove v16.14.2
  znvm ls
  znvm ls-remote
  znvm current
```

## License
ZMicro Design is released under the [MIT License](./LICENSE).