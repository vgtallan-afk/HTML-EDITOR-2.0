# HTML Editor - Project ZIP Import/Export

New workflow:
1. In the old/current editor, use Export Project ZIP before updating GitHub.
2. Update GitHub/Vercel with this editor package.
3. Open the new editor.
4. Use Import Project ZIP to continue editing from exactly where you stopped.

Notes:
- Project ZIP is for continuing editing later.
- Publishing ZIP is for the final landing page.
- Import Project ZIP looks for index.html inside the ZIP.
- Local image assets inside the ZIP are converted to embedded data URLs for safe editing.
