# Pages that are Places

A small museum of one long night — **seven interactive rooms**, each one a page that behaves like a place. Built by hand in the browser. Pure static HTML / SVG / Canvas2D. No build step, zero dependencies, nothing to install.

You arrive at the gallery by falling. The sky celebrates that you made it. A fire reads you. The sea delivers. Your wandering becomes a country. A flower opens, briefly. Before you leave, you look up.

**Live:** [heydavid.github.io/pages-that-are-places](https://heydavid.github.io/pages-that-are-places/)

---

## The rooms

| # | File | Title | What it is |
|---|------|-------|------------|
| Gallery | `index.html` | Pages that are Places | The museum itself — scroll from orbit into the ocean, shatter asteroids, feed the kelp; seven framed cards walk you into each room. |
| №01 | `deep.html` | Going Deeper | Scroll from starfield through atmosphere into the abyss; shatter asteroids, summon tadpoles; a HUD tracks your descent from orbit to the abyssal zone. |
| №02 | `fireworks.html` | Fuse | Pick a shell, draw any line on the night sky as the fuse, release to launch — the rocket rides your exact path and blooms; drone swarm, grand finale, and a show you can share as a link. |
| №03 | `ember.html` | Ember | A poem whose lines glow from ash to gold based on how long you linger; the fire hands back only the lines you actually read, as a link or a pressed-paper PNG. |
| №04 | `driftmail.html` | Driftmail | A night beach with the moon's real phase; write one sentence, cork it, and the tide carries it out — the whole message lives in the link, no server, no accounts. |
| №05 | `cartographer.html` | The Cartographer | A blank dark-vellum canvas where moving your pointer grows terrain; name what you drew, press the map, and the link regenerates the same country for whoever opens it. |
| №06 | `pressing.html` | The Pressing | One generative flower blooms per calendar day for sixty seconds, leaning toward how you hold it; when it dies you keep the pressed PNG with its invented Latin name and date. |
| №07 | `nightsky.html` | That Night's Sky | Type any date that mattered and the room renders that night's sky — moon in its true phase, a constellation for that date alone; keep the poster or send the sky as a link. |
| The other door | `workshop.html` | The Workshop | The working side of the bench — the Radar and Signal instruments, the production sites, and open tools, shown as themselves with no theater. |

---

## How it's built

Every room is a single HTML file. Canvas2D for the scenes, WebAudio for generative sound (always opt-in), a few CSS custom properties for theming. No framework, no bundler, no runtime dependencies — open any file in a browser and it works. Shareable links encode all state (firework shows, poems, maps, skies) into the URL fragment, so nothing ever touches a server.

Fonts: Newsreader + Space Mono, from Google Fonts. That's the only external request.

---

## Run it locally

```
# just open the files — or spin up any static server:
npx serve .
python -m http.server
```

No build step, no `npm install`.

---

## License

Code: MIT. **Artworks © 2026 David Russell — all rights reserved.**
[davidrussell.co](https://davidrussell.co) · South Florida
