# mpv-flash-pause

Displays an animated pause/play icon overlay when playback state changes. The icon scales up and fades out over a short animation.

https://github.com/user-attachments/assets/e220aa4e-905f-4f49-bdbd-cb66ed845f12

## Installation

Copy `pause.lua` to your mpv scripts directory:

```
~/.config/mpv/scripts/pause.lua
```

Optionally copy `pause.conf` to your script-opts directory to customize behavior:

```
~/.config/mpv/script-opts/pause.conf
```

## Configuration

| Option | Default | Description |
|--------|---------|-------------|
| `icon_size` | `100` | Base size of the icon in pixels |
| `corner_radius` | `12` | Corner rounding radius for pause bars and play triangle |
| `color` | `#000000` | Icon fill color (RGB hex) |
| `icon_alpha_start` | `100` | Icon opacity at animation start (0 = opaque, 255 = transparent) |
| `icon_alpha_end` | `50` | Icon opacity at animation end |
| `outline_thickness` | `3` | Outline stroke width in pixels (`0` to disable) |
| `outline_color` | `#FFFFFF` | Outline color (RGB hex) |
| `outline_alpha_start` | `100` | Outline opacity at animation start |
| `outline_alpha_end` | `50` | Outline opacity at animation end |
| `animation_duration` | `0.35` | Animation duration in seconds |
| `scale_factor` | `1.5` | How much the icon grows during the animation (`1.5` = 150% of original size) |
