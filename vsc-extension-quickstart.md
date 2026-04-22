# VS Code Extension Quickstart

English | [日本語](./vsc-extension-quickstart.ja.md)

## Folder Contents

- This folder contains the files required for the color theme extension.
- `package.json`
  The extension manifest. It defines the theme names and the locations of the theme files.
- `themes/noctis-rose-color-theme.json`
  Theme definition for `Noctis Rose`.
- `themes/noctis-verdant-color-theme.json`
  Theme definition for `Noctis Verdant`.
- `themes/noctis-amber-color-theme.json`
  Theme definition for `Noctis Amber`.
- `themes/noctis-slate-color-theme.json`
  Theme definition for `Noctis Slate`.
- `themes/noctis-coral-color-theme.json`
  Theme definition for `Noctis Coral`.
- `themes/noctis-teal-color-theme.json`
  Theme definition for `Noctis Teal`.
- `themes/noctis-copper-color-theme.json`
  Theme definition for `Noctis Copper`.

## Try It Quickly

- Press `F5` to open an Extension Development Host with this extension loaded.
- In the new window, run `Preferences: Color Theme` and choose one of the seven `Noctis` themes.
- Open a language file to see token scopes applied by the grammar.
- To inspect scopes, run `Developer: Inspect Editor Tokens and Scopes` from the Command Palette.

## Make Changes

- When you edit the theme JSON files, changes can be reloaded in the Extension Development Host for visual verification.

## Theme Tuning Notes

- Syntax highlighting is based on TextMate scopes.
- Use `colors` for UI colors and `tokenColors` for code token styling.

For more details, see the VS Code [Color Theme extension guide](https://code.visualstudio.com/api/extension-guides/color-theme).

## Install the Extension

- For local use, create a `.vsix` with `vsce package` and install it with `code --install-extension <vsix-file>`.
- If you later decide to publish it, follow the standard VS Code extension publishing workflow.
