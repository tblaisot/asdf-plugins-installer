# asdf-plugins-installer

[asdf-plugins-installer](https://github.com/tblaisot/asdf-plugins-installer) is a plugin installer for the [asdf version manager](https://asdf-vm.com).

It will install all plugins listed in the `$HOME/.asdf-plugins` file.

## Contents

- [Install](#install)
- [Usage](#usage)
- [License](#license)

## Install

```shell
asdf plugin add plugins-installer https://github.com/tblaisot/asdf-plugins-installer.git
```

On install the plugin will install the plugins listed in the `$HOME/.asdf-plugins` file.

## Export list of plugins

```sh
asdf plugin list --urls > "$HOME/.asdf-plugins"
```

## Usage

To install new plugins from the `$HOME/.asdf-plugins` file.

```sh
asdf plugins-installer
```

## License

See [LICENSE](LICENSE) © [Thomas Blaisot](https://github.com/tblaisot/)
