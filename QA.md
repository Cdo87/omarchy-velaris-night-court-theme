# Release validation — 29 September 2026

Validated on Omarchy 4.0.4-1, Hyprland, eDP-1 1920×1080 at scale 1.25.

- Twelve distinct PNGs, with decoded image integrity and approximate 16:9 aspect ratios checked. Every wallpaper was set on the real display and captured; all twelve screenshots matched the intended image.
- Native wallpaper size 1672×941; the desktop scales them approximately 1.15×. This is a disclosed source-resolution limit, not native 1080p or 4K output.
- The real background-cycle command selected the next image correctly. The default panorama was restored.
- Installed Omarchy templates generated supported terminal/editor/browser/shell/Hyprland configurations without unresolved tokens. Generated TOML and JSON parsed. Foot's own configuration validator passed.
- Hyprland reload and configuration-error checks passed after applying the theme.
- Body/background contrast 14.53:1; secondary/background 7.37:1; secondary/selected-row 5.23:1. All tested semantic text/background combinations exceeded 4.5:1. This does not claim a complete accessibility audit of every application.
- Visually reviewed the real terminal, bar, menu, notification and non-locking lock-screen preview. Other supported apps were template-validated, not individually exercised; authentication was not tested.
- Gallery loaded all twelve selected images at the laptop's logical viewport width without horizontal overflow.
- No executable files, symlinks, downloaded third-party art or private machine backups are included. This package remains under the registry's published 400 MB repository size ceiling.

## Artwork iteration

Twelve initial compositions were produced. Starfall was revised twice to remove connected filaments and repeated ring-like lights. The Illyrian scene was recomposed once to improve variety and distinguish wing silhouettes. The palette was refined for subdued-text contrast.

Coordinator's subjective rubric: composition 25, atmosphere 20, rendering 20, scene fidelity 15, collection variety 10, resolution 10. Selected scores range 86–92, mean 89.25/100. These are production judgements, not external ratings or user approval. All images received 6/10 for resolution because the native output is below the laptop resolution.

Interpretive limits: architecture is not a canonical map; tiny eye colours and concealed wing attachment points cannot be fully verified. Successive editing softened some fine detail in the Starfall background. No major visible defect was accepted during review.

`preview.png` is a genuine 1920×1080 desktop screenshot showing the palette in a real terminal, not a generated mockup. Registry listing and approval are separate from these local checks.
