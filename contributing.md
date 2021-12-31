# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test k3d https://github.com/dtomasi/asdf-k3d.git "k3d --version"
```

Tests are automatically run in GitHub Actions on push and PR.
