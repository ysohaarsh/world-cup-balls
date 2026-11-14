# World Cup Balls

Every FIFA World Cup match ball from 1930 to 2026, rendered in 3D in the browser.

Open `index.html`. No build step, no dependencies, no image assets.

- Drag to rotate, scroll or `+` / `−` to zoom.
- Slider or arrow keys to move between tournaments.
- 24 balls: all 23 tournaments, with 1930 split into the Tiento and the T-Model (one per half of the final).

## How it works

One WebGL2 fragment shader ray-traces a sphere and draws each ball procedurally: panel layout, seams, laces, printed graphics and surface texture. Name stamps come from a small text atlas drawn on a 2D canvas at load. Lighting is a procedural photo studio with four softboxes, a lacquer layer on the modern balls and a reflective floor.

## Accuracy

Panel counts follow the published record. Panel layouts for 1934–1966 and the printed graphics on later balls are stylised reconstructions, not traced from the originals. No manufacturer logos are reproduced.
