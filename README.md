# homeos-plugin-scoop

A [homeos](https://github.com/hainet50b/homeos) plugin for [Scoop](https://github.com/ScoopInstaller/Scoop), a command-line installer for Windows.

## Usage

Add the plugin to your homeos repository:

```sh
homeos plugin add scoop
```

Create a package using this plugin:

```sh
homeos package add neovim --plugin scoop --param app=neovim
```

## Parameters

| Parameter | Description |
|-----------|-------------|
| `app` | Scoop app name (e.g., `neovim`) |

## Actions

| Action | Command |
|--------|---------|
| install | `scoop install {{app}}` |
| update | `scoop update {{app}}` |
| uninstall | `scoop uninstall {{app}}` |

## License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
