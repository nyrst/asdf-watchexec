<div align="center">

# asdf-watchexec ![Build](https://github.com/nyrst/asdf-watchexec/workflows/Build/badge.svg) ![Lint](https://github.com/nyrst/asdf-watchexec/workflows/Lint/badge.svg)

[watchexec](https://github.com/watchexec/watchexec) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`.

# Install

Plugin:

```shell
asdf plugin add watchexec https://github.com/nyrst/asdf-watchexec.git
```

watchexec:

```shell
# Show all installable versions
asdf list-all watchexec

# Install specific version
asdf install watchexec latest

# Set a version globally (on your ~/.tool-versions file)
asdf global watchexec latest

# Now watchexec commands are available
watchexec --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nyrst/asdf-watchexec/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Siegfried Ehret](https://github.com/SiegfriedEhret/), except lib/semver.sh file which is from https://github.com/cloudflare/semver_bash
