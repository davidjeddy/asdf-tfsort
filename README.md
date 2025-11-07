<div align="center">

# asdf-tfsort [![Build](https://github.com/davidjeddy/asdf-tfsort/actions/workflows/build.yml/badge.svg)](https://github.com/davidjeddy/asdf-tfsort/actions/workflows/build.yml) [![Lint](https://github.com/davidjeddy/asdf-tfsort/actions/workflows/lint.yml/badge.svg)](https://github.com/davidjeddy/asdf-tfsort/actions/workflows/lint.yml)

[tfsort](https://docs.tfsort.io/intro) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `git`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
# recommended
asdf plugin add tfsort https://github.com/davidjeddy/asdf-tfsort.git
# using asdf-vm plugins shorthand https://github.com/asdf-vm/asdf-plugins
asdf plugin add tfsort
```

tfsort:

```shell
# Show all installable versions
asdf list-all tfsort

# Install specific version
asdf install tfsort latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tfsort latest

# Now tfsort commands are available
tfsort --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/davidjeddy/asdf-tfsort/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David J eddy](https://github.com/davidjeddy/)
