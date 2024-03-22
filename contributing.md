# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test s3cmd https://github.com/rubentsirunyan/asdf-s3cmd.git "s3cmd --version"
```

Tests are automatically run in GitHub Actions on push and PR.
