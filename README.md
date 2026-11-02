# Toss Hacker™

A single-page landing site for the Toss Hacker™ cricket and toss predictions Telegram channel. Visitors see a branded card with a 15-second countdown ring, then get redirected automatically to the Telegram invite link. They can also tap "Join Telegram Channel Now" to go straight there.

## Technologies

- Plain HTML, CSS, and a small inline JavaScript countdown. There's no framework and no build step.
- Hosted on Netlify as a static site, published from `public/`.

## Running locally

Open `public/index.html` in a browser, or serve the folder:

```bash
netlify dev --port 8889
```

## Changing the Telegram link

The invite URL appears twice in `public/index.html`: in the button's `href` and in `targetUrl` in the script. Change both.
