<div align="center">

# asdf-freqtrade [![Build](https://github.com/mskutlu/asdf-freqtrade/actions/workflows/build.yml/badge.svg)](https://github.com/mskutlu/asdf-freqtrade/actions/workflows/build.yml) [![Lint](https://github.com/mskutlu/asdf-freqtrade/actions/workflows/lint.yml/badge.svg)](https://github.com/mskutlu/asdf-freqtrade/actions/workflows/lint.yml)


[freqtrade](https://www.freqtrade.io/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add freqtrade
# or
asdf plugin add freqtrade https://github.com/mskutlu/asdf-freqtrade.git
```

freqtrade:

```shell
# Show all installable versions
asdf list-all freqtrade

# Install specific version
asdf install freqtrade latest

# Set a version globally (on your ~/.tool-versions file)
asdf global freqtrade latest

# Now freqtrade commands are available
freqtrade --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mskutlu/asdf-freqtrade/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mskutlu](https://github.com/mskutlu/)
