# Changelog

## 2.0.0 [2026-08-08]

Retargeted from the Visual Studio 2019 look to Visual Studio 2026.

- Icons now come from the official Visual Studio 2026 Image Library: 303 of
  x64dbg's 322 icon names, recoloured for a dark background, at 16px and 32px
  (`icons/` and `icons32/`) so HiDPI no longer upscales a 16px bitmap.
- Two-level surfaces: `#121314` editor, `#191A1B` tool window, `#202122`
  floating.
- VS 2026 scroll bars: 14px, no stepper buttons, square, transparent track,
  translucent slider.
- VS 2026 tabs: active tab on the editor colour with a 2px accent strip on top.
- Status bar moved off the permanent blue band. Only the debug status chip is
  tinted.
- Added the four colour keys current x64dbg defines that were missing:
  `CallStackHighlightColor`, `CallStackHighlightBackgroundColor`,
  `TraceNewValueColor`, `TraceNewValueBackgroundColor`.

## 1.0.0

Original Visual Studio 2019 style theme, based on the work by
[ThunderCls](https://github.com/ThunderCls/x64dbg_vs_dark).
