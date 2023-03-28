# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test talosctl https://github.com/bjw-s/asdf-talosctl.git "talosctl"
```

Tests are automatically run in GitHub Actions on push and PR.
