<div align="center">

# asdf-smithy [![Build](https://github.com/haydenbaker/asdf-smithy/actions/workflows/build.yml/badge.svg)](https://github.com/haydenbaker/asdf-smithy/actions/workflows/build.yml)

[smithy](https://github.com/haydenbaker/smithy) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add smithy
# or
asdf plugin add smithy https://github.com/haydenbaker/asdf-smithy.git
```

smithy:

```shell
# Show all installable versions
asdf list-all smithy

# Install specific version
asdf install smithy latest

# Set a version globally (on your ~/.tool-versions file)
asdf global smithy latest

# Now smithy commands are available
smithy --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.
