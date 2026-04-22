# Noctis Light Plus

English | [日本語](./README.ja.md)

`Noctis Light Plus` is a VS Code color theme extension that adds custom light variants inspired by the Noctis family. It is intended for local use, experimentation, and visual tuning.

It currently includes these seven themes:

- `Noctis Rose`
- `Noctis Verdant`
- `Noctis Amber`
- `Noctis Slate`
- `Noctis Coral`
- `Noctis Teal`
- `Noctis Copper`

The themes preserve the readable syntax balance of Noctis while shifting the overall UI mood through different hue families.

## Included Themes

### Noctis Rose

A soft rose-tinted light theme with warm pink accents and calm neutral surfaces.

### Noctis Verdant

A fresh green-tinted light theme with verdant accents and balanced contrast.

### Noctis Amber

A warm amber-toned light theme with restrained golden accents that avoid blending too closely with warning colors.

### Noctis Slate

A muted blue-gray light theme designed for long sessions and low visual fatigue.

### Noctis Coral

A coral-leaning light theme that sits slightly more orange than `Noctis Rose` for a brighter warm accent.

### Noctis Teal

A teal-leaning light theme with more blue than `Noctis Verdant`, giving it a cleaner information-oriented feel.

### Noctis Copper

A copper and sepia-leaning light theme with a subdued warm tone and a more classic reading feel.

## Local Development

1. Open this folder in VS Code.
2. Press `F5` to launch an Extension Development Host.
3. In the new window, run `Preferences: Color Theme`.
4. Select any of the seven `Noctis` themes.

## Package as VSIX

```bash
vsce package
```

This creates a `.vsix` file in the project folder. To install it into your regular VS Code environment, run:

```bash
code --install-extension noctis-light-plus-0.2.0.vsix
```

## Notes

- This extension is currently intended for local use and testing.
- The design references the Noctis theme family by Liviu Schera.
- Noctis is distributed under the MIT license.
