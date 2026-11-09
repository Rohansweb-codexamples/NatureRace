# Nature Race

## Project overview
Single-file static HTML racing quiz game with inline CSS/JavaScript and one local MP3 audio track. The game supports one or two players, five nature-quiz levels, lives, keyboard/touch answers, and short driving sections with collectible acorns and obstacles. No build step, backend, or package manager is required.

## Running
- Serve the repository root with any static web server.
- For the included container setup: `docker compose -f docker-compose.base44.yml up -d` serves the repo on host port 3000.
- Keep `index.html` and `331music-disco-dancing-energy-603091.mp3` together; the audio is loaded with a relative path.

## Verifying
- Open the site and confirm the Nature Race start screen appears.
- Test both single-player and two-player modes.
- Check answer selection, Enter, touch controls, music toggle, settings modal, drive steering, obstacles, acorn collection, and race completion.
