# ASDF Dapr CLI

[dapr-cli](https://github.com/dapr/cli) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager

## Installation

```
asdf plugin-add dapr-cli https://github.com/mindovermiles262/asdf-dapr-cli.git
```

## Use

Check out the [asdf documentation](https://asdf-vm.com/#/core-manage-versions?id=install-version) for instructions on how to install and manage versions of dapr-cli

```
% asdf install dapr-cli 1.11.0
[*] Downloading dapr-cli from https://github.com/dapr/cli/releases/download/v1.11.0/dapr_darwin_amd64.tar.gz
[*] dapr-cli has been installed. Use 'dapr' to get started

% asdf global dapr-cli 1.11.0

% which dapr
$HOME/.asdf/shims/dapr

% dapr -v
CLI version: 1.11.0
```

## Architecture Override

The `ASDF_KPACKCLI_OVERWRITE_ARCH` variable can be used to override the architecture that is used for determining which kpack-cli build to download.

