# Wheel Reveal — Railway / OBS

A 16:9 animated partnership-reveal overlay.

## What it does
- Uses the generated blue cyber-casino wheel scene as the visual source.
- Spins the wheel continuously and slowly: one full rotation every 42 seconds.
- Adds reactive blue energy, particles, radial streaks and pulsing light.
- Designed to sit in an OBS Browser Source.

## Railway
1. Put this project in a GitHub repository.
2. Create a new Railway service from that GitHub repository.
3. Railway will detect Node and install dependencies from `package.json`.
4. Start command is `npm start`.
5. Open the generated Railway domain.

## OBS
Add a Browser Source using:
`https://YOUR-RAILWAY-DOMAIN/?clean=1`

Recommended:
- Width: 1920
- Height: 1080
- Custom CSS: leave blank
- Shutdown source when not visible: OFF if you want it to keep animating

The wheel is intentionally slow: 42 seconds per rotation.
Change `42s` in `public/index.html` to make it faster/slower.

## Important
The six casino names/logos are part of the generated source artwork. If you want pixel-perfect official logos, replace the artwork with properly licensed logo assets.
