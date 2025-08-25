# YoloBox Overlay (Clock + Auto-Speed Ticker)

## Files
- `clock.html` → Clock only (Perth ↔ New Delhi, alternates every 3s)
- `ticker.html` → Scrolling text only (reads ticker.txt, adjusts speed automatically)
- `ticker.txt` → The message for ticker.html
- `index.html` → Helper page with links

## Usage
Upload all files to your GitHub repo linked with Netlify (or drag to Netlify Drop).

### YoloBox Pro URLs
- Clock → https://YOUR-SITE.netlify.app/clock.html
- Ticker → https://YOUR-SITE.netlify.app/ticker.html

### Update ticker text
- Edit `ticker.txt` in GitHub (via mobile app or browser).
- Commit changes → Netlify redeploys automatically.
- Ticker overlay updates within ~30s.

### Adjust positions/sizes
Open the HTML file → top `:root` section → edit variables like:
```css
--clock-bottom: 24px;
--clock-right: 24px;
--clock-size: 22px;
--ticker-bottom: 72px;
--ticker-size: 26px;
```

Enjoy smooth overlays on your YoloBox! 🎥
