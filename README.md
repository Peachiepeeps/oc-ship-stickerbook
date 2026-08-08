# OC Ship Stickerbook

## Adding a new sticker

1. Open the `stickers` folder in this GitHub repository.
2. Click **Add file → Upload files**.
3. Upload the new sticker PNG.
4. Commit the change.

That's it.

GitHub Actions will automatically rebuild `stickers.json`.
After the Pages deployment refreshes, the new sticker will appear in the sticker drawer.

You do not need to edit `index.html`.

## Important

Keep decorative/site files such as:
- notebook.png
- left-page.png
- right-page.png

outside the `stickers` folder.

Only actual draggable stickers belong inside `stickers`.
