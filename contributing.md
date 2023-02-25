# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test elm-test https://github.com/ianlet/asdf-elm-test.git "elm-test --help"
```

Tests are automatically run in GitHub Actions on push and PR.
