<div align="center">

# asdf-gauge [![Build](https://github.com/ayato-p/asdf-gauge/actions/workflows/build.yml/badge.svg)](https://github.com/ayato-p/asdf-gauge/actions/workflows/build.yml) [![Lint](https://github.com/ayato-p/asdf-gauge/actions/workflows/lint.yml/badge.svg)](https://github.com/ayato-p/asdf-gauge/actions/workflows/lint.yml)


[gauge](https://gauge.org/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gauge
# or
asdf plugin add gauge https://github.com/ayato-p/asdf-gauge.git
```

gauge:

```shell
# Show all installable versions
asdf list-all gauge

# Install specific version
asdf install gauge latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gauge latest

# Now gauge commands are available
gauge version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ayato-p/asdf-gauge/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ayato_p](https://github.com/ayato-p/)
