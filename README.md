<div align="center">

# asdf-talosctl [![Build](https://github.com/bjw-s/asdf-talosctl/actions/workflows/build.yml/badge.svg)](https://github.com/bjw-s/asdf-talosctl/actions/workflows/build.yml) [![Lint](https://github.com/bjw-s/asdf-talosctl/actions/workflows/lint.yml/badge.svg)](https://github.com/bjw-s/asdf-talosctl/actions/workflows/lint.yml)


[talosctl](https://www.talos.dev/latest/learn-more/talosctl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add talosctl
# or
asdf plugin add talosctl https://github.com/bjw-s/asdf-talosctl.git
```

talosctl:

```shell
# Show all installable versions
asdf list-all talosctl

# Install specific version
asdf install talosctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global talosctl latest

# Now talosctl commands are available
talosctl
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bjw-s/asdf-talosctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bernd Schorgers](https://github.com/bjw-s/)
