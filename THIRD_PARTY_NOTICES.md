# Third-party notices

## Background images

`backgrounds/1-starbase.jpg` and `backgrounds/2-liftoff.jpg` are photographs of Starship launches by SpaceX, published on SpaceX's account on X ([@SpaceX](https://x.com/SpaceX)). `1-starbase.jpg` has its top edge slightly darkened so a transparent Omarchy bar stays legible.

`backgrounds/3-morning-pad.jpg` is a photograph of a Starship launch by SpaceX, converted from CMYK to sRGB, with its top edge slightly darkened so a transparent Omarchy bar stays legible.

All three backgrounds were upscaled to 6016 × 3384 with [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) (BSD-3-Clause), a super-resolution model that sharpens existing detail rather than generating new content, then resized with Lanczos. The model itself is not included in this theme.

SpaceX retains all rights to the original photographs. None of the background images are covered by this theme's MIT license.

## Omarchy

Starship To Orbit includes adaptations of [Omarchy](https://github.com/omacom/omarchy) theme templates:

- `shell.toml` and `extras/glass/shell.*.toml`, adapted from `default/themed/shell.toml.tpl`.
- `hyprland.lua`, adapted from `default/themed/hyprland.lua.tpl`.
- `btop.theme`, adapted from `default/themed/btop.theme.tpl`.
- `ghostty.conf`, `alacritty.toml`, `kitty.conf` and `foot.ini`, generated from the matching templates, with added background opacity.

The following upstream MIT notice is retained for the adapted portions. Starship To Orbit's own license is in [LICENSE](LICENSE).

```text
Copyright (c) David Heinemeier Hansson

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
