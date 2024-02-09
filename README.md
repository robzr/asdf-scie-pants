<div align="center">

# asdf-scie-pants [![Build](https://github.com/robzr/asdf-scie-pants/actions/workflows/build.yml/badge.svg)](https://github.com/robzr/asdf-scie-pants/actions/workflows/build.yml) [![Lint](https://github.com/robzr/asdf-scie-pants/actions/workflows/lint.yml/badge.svg)](https://github.com/robzr/asdf-scie-pants/actions/workflows/lint.yml)

[scie-pants](https://www.pantsbuild.org/2.19/docs/getting-started/installing-pants) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add scie-pants
# or
asdf plugin add scie-pants https://github.com/robzr/asdf-scie-pants.git
```

pants:

```shell
# Show all installable versions
asdf list-all scie-pants

# Install specific version
asdf install scie-pants latest

# Set a version globally (on your ~/.tool-versions file)
asdf global scie-pants latest

# Now pants commands are available
pants --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/robzr/asdf-scie-pants/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rob Zwissler](https://github.com/robzr/)
