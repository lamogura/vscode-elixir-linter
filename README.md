# README

"elixir-linter" is a wrapper around `elixirc`.

It expects elixir and elixirc to be installed and already added to the path. If it is installed but cannot be found, add the path to your preferences as seen below.

```json
{
	"elixir.linter.executablePath": "PathToExecutable"
}
```

## Configuration:
There are various options that can be configured by making changes to your user or workspace preferences.

### Lint onType or onSave or not at all
By default the linter will lint on the fly but can be changed to linting as you save. Note that linting on save is most useful when auto-save is on. Use the setting below if to change the behavior with the values `onType`, `onSave`, and `off`.

```json
{
	"elixir.linter.run": "onType"
}
```

## Acknowledgements
The extension architecture is forked from the [vscode-ruby-linter](https://github.com/hoovercj/vscode-ruby-linter) extension and the implementation is a port of [sublimelinter-contrib-elixirc](https://packagecontrol.io/packages/SublimeLinter-contrib-elixirc) extension for SublimeText (WIP).
