# DigiPen Achievements

Steam-style achievement cards for the DigiPen Class of 2026. Pick what you earned, choose a featured achievement and your top 5, then share the image to your story.

**Live site:** https://dhaniyahfarhanah.github.io/digipen-achievements/

## How it works

Everything runs in the browser. Nothing is uploaded or stored on a server; your picks are saved only in your own browser.

## Adding art

Exported SVGs go in `icons/`, named after each achievement's id (for example `jarvis.svg`). Any icon that isn't there yet falls back to a built-in placeholder. `icons/README.txt` lists every file name and the format rules.

- `icons/<id>.svg`: one per achievement, square canvas.
- `icons/frame.svg`: featured frame, drawn behind the icon.
- `icons/frame-front.svg`: optional, drawn over the icon.

Keep source files (.ai, .psd, .fig and so on) out of the repo; `.gitignore` blocks the common ones.

## Testing locally

Opening `index.html` by double-clicking won't load the SVGs, because browsers block local files from reading the folder next to them. Use a local server such as VS Code's Live Server, or check the live site.
