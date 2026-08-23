# 🐰 Rabbit on Wheels

A rabbit wearing a flower ribbon, riding a bicycle — animated entirely with a
single self-contained HTML file (inline SVG + SMIL animations, no JavaScript,
no dependencies).

## Features

- Pedaling legs precomputed to track the pedal circle exactly (rot is the
  synced-to-crank keyframe set; feet land on the pedals to within ~0.4u)
- Spinning wheels with counter-rotating (level) pedals, road speed matched to wheel speed
- Steering arms: far arm behind the body + near arm gripping the handlebar with a paw
- Floppy ears, bobbing head, puffball tail, flower ribbon with bow
- Scrolling road, drifting clouds, pulsing sun
- Rotation centers baked into the animations (`animateTransform`), so it stays
  pixel-perfect at any window size or zoom level

## Run it

Just open `index.html` in any modern browser — no build step, no server needed.

Or view the live page: **https://laiyewfai.github.io/pelican-bicycle/**

## License

MIT
