<div align="center">

# asdf-skeema [![Build](https://github.com/jatinn/asdf-skeema/actions/workflows/build.yml/badge.svg)](https://github.com/jatinn/asdf-skeema/actions/workflows/build.yml) [![Lint](https://github.com/jatinn/asdf-skeema/actions/workflows/lint.yml/badge.svg)](https://github.com/jatinn/asdf-skeema/actions/workflows/lint.yml)

[skeema](https://www.skeema.io/docs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add skeema
# or
asdf plugin add skeema https://github.com/jatinn/asdf-skeema.git
```

skeema:

```shell
# Show all installable versions
asdf list-all skeema

# Install specific version
asdf install skeema latest

# Set a version globally (on your ~/.tool-versions file)
asdf global skeema latest

# Now skeema commands are available
skeema --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jatinn/asdf-skeema/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [jatinn](https://github.com/jatinn/)
