<div align="center">

# asdf-k3d [![Build](https://github.com/dtomasi/asdf-k3d/actions/workflows/build.yml/badge.svg)](https://github.com/dtomasi/asdf-k3d/actions/workflows/build.yml) [![Lint](https://github.com/dtomasi/asdf-k3d/actions/workflows/lint.yml/badge.svg)](https://github.com/dtomasi/asdf-k3d/actions/workflows/lint.yml)


[k3d](https://k3d.io) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add k3d
# or
asdf plugin add k3d https://github.com/dtomasi/asdf-k3d.git
```

k3d:

```shell
# Show all installable versions
asdf list-all k3d

# Install specific version
asdf install k3d latest

# Set a version globally (on your ~/.tool-versions file)
asdf global k3d latest

# Now k3d commands are available
k3d --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dtomasi/asdf-k3d/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dominik Tomasi](https://github.com/dtomasi/)
