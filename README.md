<div align="center">

# asdf-arf [![Build](https://github.com/TimothyMerlin/asdf-arf/actions/workflows/build.yml/badge.svg)](https://github.com/TimothyMerlin/asdf-arf/actions/workflows/build.yml) [![Lint](https://github.com/TimothyMerlin/asdf-arf/actions/workflows/lint.yml/badge.svg)](https://github.com/TimothyMerlin/asdf-arf/actions/workflows/lint.yml)

[arf](https://github.com/eitsupi/arf) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and standard POSIX utilities.
- Supported release targets are macOS and Linux on `x86_64` or `aarch64`.

# Install

Plugin:

```shell
asdf plugin add arf
# or
asdf plugin add arf https://github.com/TimothyMerlin/asdf-arf.git
```

arf:

```shell
# Show all installable versions
asdf list-all arf

# Install specific version
asdf install arf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global arf latest

# Now arf commands are available
arf --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/TimothyMerlin/asdf-arf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Timotheus Merlin Scherer](https://github.com/TimothyMerlin/)
