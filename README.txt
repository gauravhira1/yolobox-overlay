Two-URL overlay for YoloBox Pro

Files
-----
- clock.html  : Transparent overlay with Perth ↔ New Delhi clock (alternates every 3s)
- ticker.html : Transparent overlay with scrolling text (reads ticker.txt)
- ticker.txt  : The scrolling text content (can be edited any time)

How to deploy on Netlify (one site, two URLs):
---------------------------------------------
1) Upload ALL THREE files (clock.html, ticker.html, ticker.txt) to a single Netlify site.
2) In YoloBox Pro → Web URL Overlay → Add:
   - For clock overlay  : use https://YOUR-SITE.netlify.app/clock.html
   - For ticker overlay : use https://YOUR-SITE.netlify.app/ticker.html
3) To update ticker text later, just re-upload ticker.txt to the same Netlify site.
   The ticker page refreshes the file every ~30 seconds.

Tweaks (edit inside each HTML at the top :root section)
-------------------------------------------------------
In clock.html:
  --clock-bottom, --clock-right, --clock-size

In ticker.html:
  --ticker-bottom, --ticker-size, --ticker-speed, --left-pad, --right-pad
