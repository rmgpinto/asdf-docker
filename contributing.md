# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test docker https://github.com/rmgpinto/asdf-docker.git "docker version"
```

Tests are automatically run in GitHub Actions on push and PR.
