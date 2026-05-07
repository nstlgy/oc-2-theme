# OC-2 Theme for Zed

OC-2 is a paired light and dark theme for [Zed](https://zed.dev), adapted from the OC-2 color palette by [OpenCode](https://opencode.ai/).

## Credits

The original OC-2 theme and color palette were created by [OpenCode](https://opencode.ai/). This repository is an unofficial Zed editor adaptation of that palette.

## Themes

- `OC-2 Light`
- `OC-2 Dark`

## Local Development

To test this extension locally in Zed:

1. Open Zed.
2. Run `zed: install dev extension` from the command palette.
3. Select this repository directory.
4. Choose `OC-2 Light` or `OC-2 Dark` from the theme picker.

## Publishing

Before publishing, update these fields in `extension.toml`:

- `authors`
- `repository`

Then publish by opening a pull request to [`zed-industries/extensions`](https://github.com/zed-industries/extensions):

1. Fork and clone `zed-industries/extensions`.
2. Add this repository as a submodule under `extensions/oc-2-theme`.
3. Add an `[oc-2-theme]` entry to `extensions.toml`.
4. Run `pnpm sort-extensions`.
5. Open the pull request.

Example registry entry:

```toml
[oc-2-theme]
submodule = "extensions/oc-2-theme"
version = "0.0.1"
```

## License

MIT
