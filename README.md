<div align="center">

# asdf-s3cmd [![Build](https://github.com/rubentsirunyan/asdf-s3cmd/actions/workflows/build.yml/badge.svg)](https://github.com/rubentsirunyan/asdf-s3cmd/actions/workflows/build.yml) [![Lint](https://github.com/rubentsirunyan/asdf-s3cmd/actions/workflows/lint.yml/badge.svg)](https://github.com/rubentsirunyan/asdf-s3cmd/actions/workflows/lint.yml)

[s3cmd](https://s3tools.org/s3cmd) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add s3cmd
# or
asdf plugin add s3cmd https://github.com/rubentsirunyan/asdf-s3cmd.git
```

s3cmd:

```shell
# Show all installable versions
asdf list-all s3cmd

# Install specific version
asdf install s3cmd latest

# Set a version globally (on your ~/.tool-versions file)
asdf global s3cmd latest

# Now s3cmd commands are available
s3cmd --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rubentsirunyan/asdf-s3cmd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ruben Tsirunyan](https://github.com/rubentsirunyan/)
