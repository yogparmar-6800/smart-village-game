SMART VILLAGE SIMULATOR WEBSITE
================================

Files:
- index.html : responsive landing page with tropical-inspired cinematic hero
- game.html  : your original playable Three.js game

PREVIEW LOCALLY
1. Keep index.html and game.html in the same folder.
2. Because the game imports Three.js as an ES module, run a local web server rather than opening file:// directly.
3. If Python is installed, open a terminal in this folder and run:
       python -m http.server 8000
4. Visit http://localhost:8000

PUBLISH ONLINE
- Upload the contents of this folder to a static web host such as GitHub Pages, Netlify, or Cloudflare Pages.
- Make sure both index.html and game.html are uploaded at the same site root.
- The Play Now buttons open game.html inside the site's game player.

NOTE
The supplied game is Smart Village Simulator (farming, water, crop harvesting, vehicles, workers, poultry, and village trade). The landing page copy describes those existing features rather than claiming survival crafting systems that are not currently in the game.
