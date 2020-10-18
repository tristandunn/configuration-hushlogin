# hushlogin

Turn off the UNIX banner.

## Commands

### install

Touches the `~/.hushlogin` file, if it does not exist.

### lint

Lints the scripts in `./bin` with [`shellcheck`][].

### pull

Updates the `git` repository.

### uninstall

Removes the `~/.hushlogin` file, if it exists and is empty.

### update

Uninstalls the plug-in, pulls updates, and installs the plug-in.

[`shellcheck`]: https://github.com/koalaman/shellcheck
