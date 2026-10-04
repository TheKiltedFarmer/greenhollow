reenhollow — Improved

This is an enhanced version of Greenhollow with the following upgrades:

Improvements

Visuals & UX





Stronger facing-tile highlight — filled amber outline + directional chevron so you always know which tile your tool will hit



Slightly larger default zoom — more of the valley is readable at a glance



Action juice — dust particles and floating text on till, plant, water, harvest, chopping, mining, and filling the can

Guided first morning

A short progressive tutorial that appears after you press Begin:





Move with WASD



Till with the hoe



Plant turnip seeds



Fill the can and water



Sleep and check the Board



Welcome message

Existing saves skip the tutorial automatically.

Technical





Save key bumped to greenhollow-v5-improved so it does not overwrite your original progress



Particle / floating-text FX system (spawnFloat, spawnDust, spawnSplash) ready for further polish

How to run

Serve the folder with any static server, e.g.:

npx serve .
# or
python3 -m http.server 8080

Then open http://localhost:8080 (or the port shown).

You can also open index.html directly in a browser; localStorage and audio will still work.

Original

All credit for the world, writing, systems, and art direction belongs to the original Greenhollow at thepeoplesvoices.org.
