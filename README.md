# Wedding website

Standalone HTML, CSS, and JavaScript inspired by the supplied cinematic scroll template. No build step or package dependencies.

Run `python3 -m http.server 8000 --bind 0.0.0.0` from `/workspace/Wedding_Site`. Validate JavaScript with `node --check script.js`.

Venue: The Skylands Manor, Ringwood, New Jersey.

Scroll sequence: manor entrance → upper garden → lower garden → wedding details over the chair-free first-level garden. Names, date, personal story, travel details, and RSVP remain placeholders. A map is still awaited. There is no RSVP submission backend.

Image sources supplied by the user:

- Entrance: https://media-api.xogrp.com/images/12322ff5-0a61-42c0-8c2e-61829e96a3ca~sc_675.375?quality=90
- Upper garden: https://www.frungillo.com/wp-content/uploads/2026/09/1-1.png
- Lower garden: https://images.trvl-media.com/lodging/3000000/2080000/2071800/2071739/29ea3928.jpg?impolicy=resizecrop&rw=575&rh=575&ra=fill:
- Chair-free first-level garden: `assets/skylands-garden-first-level.png`, retouched from the user's photograph. Photographer credit retained.

The external images and Ogg font require network access to their hosts. The cloud proxy currently blocks the three new image hosts; their allowlist additions are saved in the configuration draft and require the user to save/apply settings. Image loading and crop checks must be repeated after access is enabled.
