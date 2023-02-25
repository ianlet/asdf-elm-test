<div align="center">

# asdf-elm-test [![Build](https://github.com/ianlet/asdf-elm-test/actions/workflows/build.yml/badge.svg)](https://github.com/ianlet/asdf-elm-test/actions/workflows/build.yml) [![Lint](https://github.com/ianlet/asdf-elm-test/actions/workflows/lint.yml/badge.svg)](https://github.com/ianlet/asdf-elm-test/actions/workflows/lint.yml)


[elm-test](https://github.com/rtfeldman/node-test-runner) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add elm-test
# or
asdf plugin add elm-test https://github.com/ianlet/asdf-elm-test.git
```

elm-test:

```shell
# Show all installable versions
asdf list-all elm-test

# Install specific version
asdf install elm-test latest

# Set a version globally (on your ~/.tool-versions file)
asdf global elm-test latest

# Now elm-test commands are available
elm-test --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ianlet/asdf-elm-test/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ian Letourneau](https://github.com/ianlet/)
