# Thumbnail Maker

A browser tool for building 1280×720 YouTube thumbnails from a League of Legends gameplay screenshot and a character image.
Everything lives in a single `index.html`. Images are processed locally and never uploaded anywhere.

## Usage

1. Open `index.html` in Chrome or Edge, or visit the GitHub Pages link.
2. Add a gameplay screenshot and a character image: click, drag and drop, or paste with `Ctrl+V`.
3. **Game** — place the focus point on your champion (`F`), then pick a skill color (`I`) to boost or recolor only that effect. The gameplay itself stays ungraded.
4. **Character** — choose a layout: cutout, soft blend, frame, diagonal slash, or pop-out.
5. **Look** — channel color, speed lines, screentone, film grain.
6. **Text** — hook text, logo or champion icon, item build row.
7. **Styles** — save your settings and star one to load it every time the tool opens.
8. Download as PNG, or JPG to stay under YouTube's 2 MB limit.

Press `?` inside the tool for all keyboard shortcuts.

## Notes

- Saved styles live in the browser's localStorage. To move them between machines, or from the local file to GitHub Pages, use **Export / Import** on the Styles tab.
- Fonts load from Google Fonts, so an internet connection is needed for the full font list.
- Image files are excluded in `.gitignore` so copyrighted source art never ends up in the repo.
