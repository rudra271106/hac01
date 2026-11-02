# AGENTS.md

## Architecture

This is a static, single-file site. `public/index.html` holds all the markup, CSS (in a `<style>` block), and JavaScript (in an inline IIFE). `netlify.toml` publishes `public/` and has no build command.

## Conventions

- Keep the site dependency-free with no build step, unless the owner asks for more.
- Theme colors live in the `:root` CSS variables.
- The Telegram invite URL is duplicated in the `#join-link` anchor and in `targetUrl` in the script. Keep the two in sync.
- The countdown length is `totalTime` (15 seconds). The ring's circumference is computed from radius 54, which matches the SVG circle `r`.
