<div align="center">

# asdf-docker [![Build](https://github.com/rmgpinto/asdf-docker/actions/workflows/build.yml/badge.svg)](https://github.com/rmgpinto/asdf-docker/actions/workflows/build.yml) [![Lint](https://github.com/rmgpinto/asdf-docker/actions/workflows/lint.yml/badge.svg)](https://github.com/rmgpinto/asdf-docker/actions/workflows/lint.yml)

[docker](https://github.com/docker/cli) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add docker
# or
asdf plugin add docker https://github.com/rmgpinto/asdf-docker.git
```

docker:

```shell
# Show all installable versions
asdf list-all docker

# Install specific version
asdf install docker latest

# Set a version globally (on your ~/.tool-versions file)
asdf global docker latest

# Now docker commands are available
docker version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rmgpinto/asdf-docker/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ricardo Pinto](https://github.com/rmgpinto/)
