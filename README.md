# HTML Editor - Hard Full-Bleed No Right Bar Fix

Fix:
- Removes right-side bars/strips caused by centered or max-width section backgrounds.
- Uses real viewport full-bleed: 100vw / 100dvw + calc(50% - 50vw).
- Normalizes existing/imported sections before preview and export.
- Exported HTML includes the hard full-bleed CSS.
- Keeps previous carousel, transparent PNG, ZIP import, autosave, desktop/mobile features.
