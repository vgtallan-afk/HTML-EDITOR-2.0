# HTML Editor - Real Device Background/Gradient Fix

Fixes:
- Desktop and mobile backgrounds/gradients are now stored separately.
- Desktop Edit writes to --vhe-desktop-bg / data-vhe-desktop-bg.
- Mobile Edit writes to --vhe-mobile-bg / data-vhe-mobile-bg.
- The editor iframe forces the correct mode using data-vhe-edit-mode.
- Exported HTML uses media queries so desktop and mobile show their own gradients.
- Reset/remove gradient affects only the current mode.
- Keeps clear move handle, logical grouping, soft undo, carousel fixes, transparent PNG, ZIP import, and autosave.
