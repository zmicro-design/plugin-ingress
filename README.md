# INGRESS - Virtual Machine Manager Plugin for [ZMicro](https://github.com/zcorky/zmicro)

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-ingress.svg?label=Release)](https://github.com/zmicro-design/plugin-ingress/tags)
[![Build Status](https://github.com/zmicro-design/plugin-ingress/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-ingress/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-ingress.svg)](https://github.com/zmicro-design/plugin-ingress/issues)

## Installation

To install the package, run:

```bash
zmicro plugin install ingress
```

### If you donot install [ZMicro](https://github.com/zcorky/zmicro):

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zmicro-design/plugin-ingress/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zmicro-design/plugin-ingress/master/install | bash
```

## Usage

```markdown
ingress (v0.0.0)

ingress_manager

Usage:
  zmicro ingress start         - Start a virtual machine
  zmicro ingress stop          - Stop a virtual machine
  zmicro ingress restart       - Restart a virtual machine
  zmicro ingress upgrade       - Upgrade a virtual machine
  zmicro ingress help          - Show help

Example:
  zmicro ingress start test01
```

## License

ZMicro Design is released under the [MIT License](./LICENSE).
