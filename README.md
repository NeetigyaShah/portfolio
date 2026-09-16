# neetigya.vercel.app

My portfolio. One self-contained HTML file, no build step, no framework.

Play Pac-Man in the hero maze, scroll past the eating rail, and read what each
project actually does in plain English.

## What is in here

- `index.html` — the whole site: inline CSS, inline JavaScript, inline SVG.
  The only external request is Google Fonts (Bricolage Grotesque, Outfit,
  JetBrains Mono).

## Run it locally

Open `index.html` in a browser. That is the whole setup.

## Deploy

Hosted on Vercel as a static site (project `neetigya`). To ship a change:

```
vercel --prod
```

## The maze

- Pac plays on his own until you take over (arrows, WASD, or swipe).
- Small dots 10, big dots 50 and turn the ghosts blue for a while.
- Once you are playing you get three lives. Score is stored on your device only.
- Left and right edges of the third row are tunnels.

## Contact

neetigyashah@gmail.com
